#### Templates
```html
<section *ngIf="showGreeting">
    <h1>Welcome to {{conferenceName}}!</h1>
    <button (click)="changeMessage()">Click me!</button>
</section>
```
notes:
standard HTML, enhanced with bindings and direcives
plays the role of the view in an MVVM architecture
