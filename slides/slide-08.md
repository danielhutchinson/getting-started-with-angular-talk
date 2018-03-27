#### Modules

Represent all cohesive blocks of code, dedicated to a single domain area.

```typescript
@NgModule({
    imports: [],
    declarations: [],
    providers: []
})
export class AppModule {
}
```
notes:
Angular is modular, and as such as its own modularity system called NgModule.

A module is a container for all cohesive blocks of code dedicated to a single domain. In a nutshell an NgModule ties common functionality together. They are intended to be exported and imported together to create a cohesive solution.
