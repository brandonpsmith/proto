# Fragment CLI plugin

[fragment](https://fragment.dev) plugin for [proto](https://github.com/moonrepo/proto).

## Installation

This is a community plugin and is thus not built-in to proto. In order to use it, first either add it to your global or project-based `.prototools` by running:

### Global install

```shell
proto plugin add fragment "source:https://raw.githubusercontent.com/circle9r/proto/main/plugins/fragment/plugin.toml" --global
proto install fragment
```

## Per-project install

```shell
proto plugin add fragment "source:https://raw.githubusercontent.com/circle9r/proto/main/plugins/fragment/plugin.toml"
proto pin fragment latest --resolve
```