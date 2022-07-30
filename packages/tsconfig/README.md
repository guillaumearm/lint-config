# `@trapcodien/tsconfig`

My main tsconfig

## Usage

### Installation

```shell
npm install -D typescript @trapcodien/tsconfig
```

### Basic configuration

Create a `tsconfig.json` file with:

```json
{
  "extends": "@trapcodien/tsconfig/tsconfig.base.json",
  "include": ["src/**/*.ts"],
  "compilerOptions": {
    "rootDir": "src",
    "outDir": "dist"
  }
}
```

### React configuration:

```json
{
  "extends": "@trapcodien/tsconfig/tsconfig.react.json",
  "include": ["src/**/*.ts", "src/**/*.tsx"],
  "compilerOptions": {
    "rootDir": "src",
    "outDir": "dist"
  }
}
```
