### Component

```Typescript
@Component({
    selector: 'my-component',
    template: `<h1>Hello, Codeweavers!</h1>`
})
export class MyComponent {
}
```

```html
<my-component></my-component>
```

Notes:
**Component**

The smallest isolated piece of an application
No Scope, No Controllers, You probably still should use models
Plays the role of the ViewModel in an MVVM architecture

**Decorators**

Tell Angular when and how to instantiate a component
