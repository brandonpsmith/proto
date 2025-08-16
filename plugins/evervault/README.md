# Evervault CLI plugin

[evervault-cli](https://github.com/evervault/evervault-cli) plugin for [proto](https://github.com/moonrepo/proto).

## Installation

This is a community plugin and is thus not built-in to proto. In order to use it, first either add it to your global or project-based `.prototools` by running:

### Global install

```shell
proto plugin add evervault "source:https://raw.githubusercontent.com/brandonpsmith/proto/main/plugins/evervault/plugin.toml" --global
proto install evervault
```

## Per-project install

```shell
proto plugin add evervault "source:https://raw.githubusercontent.com/brandonpsmith/proto/main/plugins/evervault/plugin.toml"
proto pin evervault latest --resolve
```
