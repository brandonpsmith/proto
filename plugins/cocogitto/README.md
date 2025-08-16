# Cocogitto plugin

[cocogitto](https://docs.cocogitto.io) plugin for [proto](https://github.com/moonrepo/proto).

## Installation

This is a community plugin and is thus not built-in to proto. In order to use it, first either add it to your global or project-based `.prototools` by running:

### Global install

```shell
proto plugin add cocogitto "source:https://raw.githubusercontent.com/circle9r/proto/main/plugins/cocogitto/plugin.toml" --global
proto install cocogitto
```

## Per-project install

```shell
proto plugin add cocogitto "source:https://raw.githubusercontent.com/circle9r/proto/main/plugins/cocogitto/plugin.toml"
proto pin cocogitto latest --resolve
```