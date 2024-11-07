# @slavamak/tsconfig

Shareable TSConfig configurations.

## Installation

To use these configurations in your project, install the package via pnpm:

```bash
pnpm add -D @slavamak/tsconfig
```

## Usage

To use the TSConfig configurations, add the desired config to the `extends` property in your `tsconfig.json` file:

```json
{
  "extends": "@slavamak/tsconfig/remix",
  "compilerOptions": {
    "baseUrl": "."
  },
  "include": [
    "**/*",
    "**/.*"
  ],
  "exclude": [
    "build"
  ]
}
```

## Available Configurations

This package includes a variety of configurations to suit different project needs. You can extend from any of the following:

- `base.json`: Basic configuration for TypeScript/JavaScript projects.
- `remix.json`: Configuration for Remix applications.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
