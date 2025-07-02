<div align="center">

[<img src="https://localazy.com/directus9/assets/9fc36b9c-81b7-4dbf-bd82-b64cd984090f" width="285" height="50" alt="Localazy" >](https://localazy.com)

### 📦 `@localazy/tsconfig`

_A standardized TypeScript configuration for Localazy projects_

</div>

## 🚀 Quick Start

Install the package using your preferred package manager:

```shell
# Using npm
npm install typescript @localazy/tsconfig --save-dev

# Using yarn
yarn add typescript @localazy/tsconfig --dev

# Using pnpm
pnpm add typescript @localazy/tsconfig --save-dev
```

## 🔧 Usage

In your tsconfig.json, extend the configuration:

```json
{
  "$schema": "https://json.schemastore.org/tsconfig",
  "extends": "@localazy/tsconfig/tsconfig.library.json"
}
```

```json
{
  "$schema": "https://json.schemastore.org/tsconfig",
  "extends": "@localazy/tsconfig/tsconfig.monorepo-library.json"
}
```

```json
{
  "$schema": "https://json.schemastore.org/tsconfig",
  "extends": "@localazy/tsconfig/tsconfig.node.library.json"
}
```

```json
{
  "$schema": "https://json.schemastore.org/tsconfig",
  "extends": "@localazy/tsconfig/tsconfig.node.monorepo-library.json"
}
```

## 📜 License

This project is licensed under the MIT License.

See [LICENSE](LICENSE) for details.
