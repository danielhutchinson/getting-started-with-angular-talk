```Typescript
@Component({
    selector: 'my-component',
    template: `<h1>{{conferenceName}}</h1>`,
    styles: [`
        h1 {
            color: #f00;
        }    
    `]
})
export class MyComponent {
    public message: string = 'Mikefest 2018';
}
```