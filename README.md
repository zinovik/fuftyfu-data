Main repository: https://github.com/zinovik/fuftyfu-bot

Interface:

```typescript
interface IHedgehog {
  id: number;
  when: string;
  photo: string;
  who: {
    [language: string]: string;
  };
  country: {
    [language: string]: string;
  };
  place: {
    [language: string]: string;
  };
  comment?: {
    [language: string]: string;
  };
  coordinates: number[];
}
```
