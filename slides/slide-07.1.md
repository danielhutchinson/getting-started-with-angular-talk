#### Injecting Dependencies into Components
```typescript
@Component({
    selector: 'my-component',
    templateUrl: 'path/to/my-component.html',
})
export class MyComponent {
    private _conferenceService: ConferenceService;

    constructor(conferenceService: ConferenceService) {
        this._conferenceService = conferenceService;
    }
}
```
notes:
standard dependency injection you've probably seen before, dependencies are specified in the consttuctor.
 angular will handle the dependency injection for you. You can customise and override this in the module.
