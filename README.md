<div align="center">

# asdf-pixi [![Build](https://github.com/pavelzw/asdf-pixi/actions/workflows/build.yml/badge.svg)](https://github.com/pavelzw/asdf-pixi/actions/workflows/build.yml) [![Lint](https://github.com/pavelzw/asdf-pixi/actions/workflows/lint.yml/badge.svg)](https://github.com/pavelzw/asdf-pixi/actions/workflows/lint.yml)

[pixi](https://pixi.sh) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add pixi
# or
asdf plugin add pixi https://github.com/pavelzw/asdf-pixi.git
```

pixi:

```shell
# Show all installable versions
asdf list-all pixi

# Install specific version
asdf install pixi latest

# Set a version globally (on your ~/.tool-versions file)
asdf global pixi latest

# Now pixi commands are available
pixi --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/pavelzw/asdf-pixi/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Pavel Zwerschke](https://github.com/pavelzw/)
