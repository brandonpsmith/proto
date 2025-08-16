# buf plugin

[buf](https://github.com/bufbuild/buf) plugin for [proto](https://github.com/moonrepo/proto).

## Installation

This is a community plugin and is thus not built-in to proto. In order to use it, first either add it to your global or project-based `.prototools` by running:

### Global install

```shell
proto plugin add buf "source:https://raw.githubusercontent.com/brandonpsmith/proto/main/plugins/buf/plugin.toml" --global
proto install buf
```

## Per-project install

```shell
proto plugin add buf "source:https://raw.githubusercontent.com/brandonpsmith/proto/main/plugins/buf/plugin.toml"
proto pin buf latest --resolve
```
