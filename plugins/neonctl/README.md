# Neon CLI plugin

[neonctl](https://neon.com/docs/reference/neon-cli) plugin for [proto](https://github.com/moonrepo/proto).

## Installation

This is a community plugin and is thus not built-in to proto. In order to use it, first either add it to your global or project-based `.prototools` by running:

### Global install

```shell
proto plugin add neonctl "source:https://raw.githubusercontent.com/circle9r/proto/main/plugins/neonctl/plugin.toml" --global
proto install neonctl
```

## Per-project install

```shell
proto plugin add neonctl "source:https://raw.githubusercontent.com/circle9r/proto/main/plugins/neonctl/plugin.toml"
proto pin neonctl latest --resolve
```