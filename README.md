# Web Fake Book - Client

## Project Setup

```
yarn install
```

### Compiles and hot-reloads for development

```
yarn dev
```

### Compiles and minifies for production

```
yarn build
```

### Run your unit tests

```
yarn test
```

### Run your end-to-end tests

```
yarn cypress
```

##

## Architecture

- React + TypeScript
- Styled Components
- RxJs + Axios Observable
- React-Router-Dom

## Testing Strategy

### E2E Testing

Cypress.io was used for E2E testing for actually testing user flows. I have previously done this with React Testing Library but found that the amount of setup was much heavier than Cypress.

### Unit Testing

I used the standard Jest + React Testing Library set up. However, I really didn't utilize RTL. I primarily tested the reducers and associated actions for each individual container as I felt the E2E tests covered all other user scenarios.
