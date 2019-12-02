# ESLint Configuration

## TypeScript Projects

Install dependencies:

```
$ yarn add --dev eslint @ftw/eslint-config-ts
```

Create an `.eslintrc` file in the root of your project:

```json
{
  "extends": ["@ftw/eslint-config-ts"],
  "env": {
    "node": true,
    "browser": true
  }
}
```

Add a `lint` script to your `package.json`:

```
"scripts": {
  "lint": "eslint \"client/**/*.{js,ts,tsx}\""
}
```
