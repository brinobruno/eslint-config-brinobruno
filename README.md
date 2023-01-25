# Bruno Corrêa ESLint config

## What's included?

- Standard config base;
- React plugin;
- React Hooks plugin;
- JSX a11y plugin;
- Node support
- Prettier;

## Setup

1. Install the dependencies
```
npm i -D eslint @brinobruno/eslint-config
```

2. For a React application, create a `.eslintrc.json` file extending the config:
```
{
  "extends": "@brinobruno/eslint-config/react"
}
```

Or, for a Node application, create the same file with:
```
{
  "extends": "@brinobruno/eslint-config/node"
}
```

> You can also use a `.eslintrc.js` instead of JSON if you prefer.

## Recommended

- Prefer using on Visual Studio Code with ESLint extension
- Create a script for linting
- Enable lint on-save

## In consideration/Upcoming

- Node-focused support
- Default eslintrc export