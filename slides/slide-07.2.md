```typescript
@Component({
    selector: 'my-component',
    templateUrl: 'path/to/my-component.html',
})
export class MyComponent {
    public conferenceName: string;

    private _conferenceService: ConferenceService;

    constructor(conferenceService: ConferenceService) {
        this._conferenceService = conferenceService;

        this.conferenceName = 
            this._conferenceService.getConferenceName();
    }
}
```
notes:
example of using a method on the injected in service