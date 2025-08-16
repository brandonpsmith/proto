# Temporal CLI plugin

[temporal](https://github.com/temporalio/cli) plugin for [proto](https://github.com/moonrepo/proto).

## Installation

This is a community plugin and is thus not built-in to proto. In order to use it, first either add it to your global or project-based `.prototools` by running:

### Global install

```shell
proto plugin add temporal "source:https://raw.githubusercontent.com/circle9r/proto/main/plugins/temporal/plugin.toml" --global
proto install temporal
```

## Per-project install

```shell
proto plugin add temporal "source:https://raw.githubusercontent.com/circle9r/proto/main/plugins/temporal/plugin.toml"
proto pin temporal latest --resolve
```