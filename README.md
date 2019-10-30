# ESLint Configuration

## TypeScript Projects

Install dependencies:

```
$ yarn add --dev eslint @ftw/eslint-config-ts
```

Create an `.eslintrc.js` file in the root of your project:

```javascript
module.exports = {
  extends: ['@ftw/eslint-config-ts']
};
```

Add a `lint` script to your `package.json`:

```
"scripts": {
  "lint": "eslint \"client/**/*.{js,ts,tsx}\""
}
```
