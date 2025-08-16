# dotenvx plugin

[dotenvx](https://github.com/dotenvx/dotenvx) plugin for [proto](https://github.com/moonrepo/proto).

## Installation

This is a community plugin and is thus not built-in to proto. In order to use it, first either add it to your global or project-based `.prototools` by running:

### Global install

```shell
proto plugin add dotenvx "source:https://raw.githubusercontent.com/brandonpsmith/proto/main/plugins/dotenvx/plugin.toml" --global
proto install dotenvx
```

## Per-project install

```shell
proto plugin add dotenvx "source:https://raw.githubusercontent.com/brandonpsmith/proto/main/plugins/dotenvx/plugin.toml"
proto pin dotenvx latest --resolve
```
