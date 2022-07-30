# Typescript/Eslint/Prettier configs

This is a monorepo.

## Packages

- [@trapcodien/tsconfig](./packages/tsconfig/README.md)
- [@trapcodien/eslint-config](./packages/eslint-config/README.md)
- [@trapcodien/prettier-config](./packages/prettier-config/README.md)

## Usage

### Init the project

```shell
mkdir my-project
cd my-project

npm init -y
```

### Setup typescript

```shell
npm install -D typescript @trapcodien/tsconfig
```

Create a `tsconfig.json` file with:

```json
{
  "extends": "@trapcodien/tsconfig"
}
```

### Setup eslint

```shell
npm install -D eslint @trapcodien/eslint-config
```

Create a `.eslintrc` file with this content:

```json
{
  "extends": ["@trapcodien/eslint-config"]
}
```

### Setup prettier

```shell
npm install -D prettier @trapcodien/prettier-config
```

create a `.prettierrc` file with this content:

```json
{
  "prettier": "@trapcodien/prettier-config"
}
```
