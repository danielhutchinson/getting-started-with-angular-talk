#### Template Syntax
##### Event Binding

<small>Template Declaration</small>
```html
<button type="submit" (click)="submitForm()">Submit</button>
```

<small>Component Declaration</small>
```typescript
    // component declaration code
    public submitForm(): void {
        console.info('The form has been submitted');
    }
    // component declaration code
```
notes:
you can also bind to events raised by DOM elements, for example a button click event. In this scenario when the event is raised, the submitForm() method is called on the component