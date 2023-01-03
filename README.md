# vue-typescript-boilerplate

Followed vuejs.org [Quick start](https://vuejs.org/guide/quick-start.html#creating-a-vue-application) page for creating the project.

### Setup for this boilerplate

```console
✔ Project name: vue-project
✔ Add TypeScript? Yes
✔ Add JSX Support? Yes
✔ Add Vue Router for Single Page Application development? Yes
✔ Add Pinia for state management? No
✔ Add Vitest for Unit testing? No
✔ Add Cypress for both Unit and End-to-End testing? No
✔ Add ESLint for code quality? Yes
✔ Add Prettier for code formatting? Yes
```

### Adjustments after creation

- Add rules in `.prettierrc.json`
- Update `.eslintrc.cjs` to fix malfunctioning linter in `.ts` and `.vue` files
- Allow importing `.vue` file from `.ts`.
```typescript
/* env.d.ts */
declare module '*.vue';
```
