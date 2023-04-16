## Folder Structure I

```
- src/
  - components/
    - Button/
      - Button.tsx
      - Button.test.tsx
  - domain/
    - models/
      - User.ts
    - repositories/
      - UserRepository.ts
  - infrastructure/
    - api/
      - graphql.ts
    - state/
      - store.ts
      - slice.ts
  - usecases/
    - login/
      - Login.ts
      - Login.test.ts
  - App.tsx
  - index.tsx
```

## Libraries to include
- https://refine.dev/
- https://redux-toolkit.js.org/
- https://reactrouter.com/
- https://www.apollographql.com/apollo-client