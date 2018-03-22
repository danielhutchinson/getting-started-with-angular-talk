#### Template Syntax
##### Built-in Directives

```html
<div *ngIf="showNames">
    <ul>
        <li *ngFor="let name of names">{{name}}</li>
    </ul>
</div>
```
notes:
There are a number of built in directives in angular, two common ones are ngFor for interation and ngIf for conditional display on view elements