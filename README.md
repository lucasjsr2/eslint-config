# ESLint config

## Whats included?

- React plugin;
- React Hooks plugin;
- JSX a11y plugin;
- Prettier;

## My rules
- Semi-colons 😌
- Double quotes 🧐
- 2 spaces 🫡

## Setup

### React (with Next.js)

Install dependencies:
```
npm i -D eslint @lucasjsr/eslint-config
```

```
yarn add -D eslint @lucasjsr/eslint-config
```
Inside `.eslintrc.json`

### React (with Next.js)

Install dependencies:
```
npm i -D eslint @rocketseat/eslint-config
```
Inside `.eslintrc.json`
```
{
  "extends": [
    "@rocketseat/eslint-config/next",
    "next/core-web-vitals"
  ]
}
```

### React (without Next.js)

Install dependencies:
```
npm i -D eslint @rocketseat/eslint-config
```
Inside `.eslintrc.json`
```
{
  "extends": "@rocketseat/eslint-config/react"
}
```

### Node.js

Install dependencies:
```
npm i -D eslint @rocketseat/eslint-config
```
Inside `.eslintrc.json`
```
{
  "extends": "@rocketseat/eslint-config/node"
}
```
