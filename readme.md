# tarot-typescript-config

Default TypeScript configuration for [Tarot](https://github.com/codynova/tarot).

This package is automatically used in the Tarot `build` process unless you have provided a custom `tsConfigPath`.

To use in your own custom configuration, install then extend this package in your tsconfig:

```bash
yarn add --dev tarot-typescript-config
```

```jsonc
// tsconfig.json
{ "extends": "tarot-typescript-config" }
```