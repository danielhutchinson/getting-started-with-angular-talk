```Typescript
@Component({
    selector: 'my-component',
    template: `<h1>{{conferenceName}}</h1>`
})
export class MyComponent {
    public conferenceName: string = 'Mikefest 2018';
}
```


Notes:
Data Binding to a template using public properties