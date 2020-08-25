# Eslint / Prettier Setup of koassi 📦

Publish my React eslint & prettier config to npm

## `package.json`

```json
  "peerDependencies": {
    "babel-eslint": "^10.1.0",
    "eslint": "^7.7.0",
    "eslint-config-prettier": "^6.11.0",
    "eslint-plugin-jsx-a11y": "^6.3.1",
    "eslint-plugin-prettier": "^3.1.4",
    "eslint-plugin-react": "^7.20.6",
    "eslint-plugin-react-hooks": "^4.1.0",
    "eslint-plugin-simple-import-sort": "^5.0.3",
    "prettier": "^2.1.0"
  },
  "devDependencies": {
    "babel-eslint": "^10.1.0",
    "eslint": "^7.7.0",
    "eslint-config-prettier": "^6.11.0",
    "eslint-plugin-jsx-a11y": "^6.3.1",
    "eslint-plugin-prettier": "^3.1.4",
    "eslint-plugin-react": "^7.20.6",
    "eslint-plugin-react-hooks": "^4.1.0",
    "prettier": "^2.1.0"
  },
```

## Local / Per Project Install (Usage)

```bash
npx install-peerdeps --dev @koassi/react-eslint-config
```

Update `eslintrc` file

```json
{
  "extends": ["@koassi/react-eslint-config"]
}
```

And you can add two scripts to your package.json to lint and/or fix:

```json
"scripts": {
  "lint": "eslint .",
  "lint:fix": "eslint . --fix"
},
```
