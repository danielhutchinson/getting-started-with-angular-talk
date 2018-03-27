#### Services
```typescript
@Injectable()
export class ConferenceService {
    public getConferenceName(): string {
        return 'Mikefest 2018';
    }
}
```
notes:
_almost_ like standard typescript classes, they only need the @Injectable() decorator
this tells angular that this can be injected into other components and services as a dependency

@Injectable() decorator actually tells the dependency injector in angular that this class can be injected into other classes, but is most commonly used for services
