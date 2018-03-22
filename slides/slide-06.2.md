#### Template Syntax
##### Property Binding

```html
<img [src]="avatarUrl" />
<button type="submit" [disabled]="formInvalid">Submit</button>
```
notes:
property binding is used when setting values of view elements, such as the src of an image, or the disabled attibute of a button

like interpolation the values are updated automatically when the data changes on the view model