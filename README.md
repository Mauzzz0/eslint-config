# ESLint Config
The ESLint Configuration package for the Node.js TypeScript Developers

## Installation
### Install dependencies
```shell
npm i -D \
  @eslint/js@9 \
  @types/eslint__js@8 \
  @typescript-eslint/eslint-plugin@8 \
  @typescript-eslint/parser@8 \
  eslint@9 \
  eslint-config-prettier@9 \
  eslint-plugin-import@2 \
  eslint-plugin-prettier@5 \
  eslint-plugin-simple-import-sort@12 \
  eslint-plugin-unused-imports@4 \
  eslint-import-resolver-typescript@3 \
  prettier@3 \
  typescript-eslint@8
```

### ESLint flat config
Create `eslint.config.js` file and paste content from [index.js](./index.js) file

### Prettier config
Paste this `Prettier` config into your `package.json` file:
```json
  "prettier": {
    "singleQuote": true,
    "trailingComma": "all",
    "printWidth": 120,
    "tabWidth": 2,
    "endOfLine": "lf"
  },
```

It should be like this
```json
{
  "name": "name",
  "version": "x.x.x",
  "scripts": {},
  "prettier": {
    "singleQuote": true,
    "trailingComma": "all",
    "printWidth": 120,
    "tabWidth": 2,
    "endOfLine": "lf"
  },
  "devDependencies": {},
  "dependencies": {}
}
```