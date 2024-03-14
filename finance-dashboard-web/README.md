# React + TypeScript + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

-   [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
-   [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend updating the configuration to enable type aware lint rules:

-   Configure the top-level `parserOptions` property like this:

```js
export default {
    // other rules...
    parserOptions: {
        ecmaVersion: 'latest',
        sourceType: 'module',
        project: ['./tsconfig.json', './tsconfig.node.json'],
        tsconfigRootDir: __dirname,
    },
};
```

-   Replace `plugin:@typescript-eslint/recommended` to `plugin:@typescript-eslint/recommended-type-checked` or `plugin:@typescript-eslint/strict-type-checked`
-   Optionally add `plugin:@typescript-eslint/stylistic-type-checked`
-   Install [eslint-plugin-react](https://github.com/jsx-eslint/eslint-plugin-react) and add `plugin:react/recommended` & `plugin:react/jsx-runtime` to the `extends` list

# finance-dashboard-web

## Run in Development mode

-   `npm run dev`

## Environment

-   Visual Studio Code
-   Google Chrome

### Visual Studio Code Extensions

-   ES7 + React/Reudx/React-Native snippets
-   ESLint
-   Tailwind Shades

### Google Chrome Extensions

-   Redux DevTools
-   Pesticide for Chrome

# Dependencies

## Production:

-   `npm i react-redux`
-   `npm i @reduxjs/toolkit`
-   `npm i react-router-dom`
-   `npm i @mui/material`
-   `npm i @emotion/react`
-   `npm i @emotion/styled`
-   `npm i @mui/icons-material`
-   `npm i @mui/x-data-grid`

## Development

-   `npm i -D @types/react-dom`
-   `npm i -D eslint eslint-config-react-app`
-   `npm i -D @types/node`
-   `npm install prettier -D --save-exact`
