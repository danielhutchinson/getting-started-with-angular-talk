```Typescript
@Component({
    selector: 'my-component',
    templateUrl: 'path/to/my-component.html',
    styleUrls: ['path/to/my-component.css']
})
export class MyComponent {
    public conferenceName: string = 'Mikefest 2018';
}
```

Notes:
Using external references to existing files
By convention you give all files the same name, usually a project is structured as one folder per component, containing all of the relevant files
