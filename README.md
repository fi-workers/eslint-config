# Development
```sh
$ yarn install
$ yarn install-husky
```

# Installation

> ~~yarn add eslint @fi-workers/eslint-config --dev~~

or

> ~~npm install eslint @fi-workers/eslint-config --save-dev~~

현재는 npm 에 업로드 되어있지 않기 때문에 npm 설치 방식으로는 사용하지 않음

> yarn add https://github.com/fi-workers-corp/eslint-config.git --dev


## Recommends

### Frontend
```js
  ...
  extends: [
    "@fi-workers/eslint-config",
    "@fi-workers/eslint-config/react/typescript",
    "@fi-workers/eslint-config/prettier"
  ]
  ...
```

### Backend
```js
  ...
  extends: [
    "@fi-workers/eslint-config",
    "@fi-workers/eslint-config/typescript",
    "@fi-workers/eslint-config/prettier"
  ]
  ...
```

## ESLint extends

### JavaScript
```js
  ...
  extends: [
    "@fi-workers/eslint-config"
  ],
  ...
```

### TypeScript
```js
  ...
  extends: [
    "@fi-workers/eslint-config",
    "@fi-workers/eslint-config/typescript"
  ],
  ...
```

### React
```js
  ...
  extends: [
    "@fi-workers/eslint-config",
    "@fi-workers/eslint-config/react"
  ],
  ...
```

### React with TypeScript
```js
  ...
  extends: [
    "@fi-workers/eslint-config",
    "@fi-workers/eslint-config/react/typescript"
  ],
  ...
```

### Prettier
```js
  ...
  extends: [
    "@fi-workers/eslint-config",
    "@fi-workers/eslint-config/prettier"
  ]
  ...
```

## Prettier extends
```js
// .prettierrc
"@fi-workers/eslint-config/prettier-config"
```

## TSConfig extends
### TypeScript
```js
// tsconfig.json
{
  "extends": "@fi-workers/eslint-config/tsconfig.json",
  "compilerOptions": {    
    ...
  },
}
```

### React with TypeScript
```js
// tsconfig.json
{
  "extends": "@fi-workers/eslint-config/react/tsconfig.json",
  "compilerOptions": {    
    ...
  },
}
```
