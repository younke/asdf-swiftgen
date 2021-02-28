<div align="center">

# asdf-swiftgen ![Build](https://github.com/younke/asdf-swiftgen/workflows/Build/badge.svg) ![Lint](https://github.com/younke/asdf-swiftgen/workflows/Lint/badge.svg)

[swiftgen](https://github.com/SwiftGen/SwiftGen) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Why?](#why)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add swiftgen
# or
asdf plugin add https://github.com/younke/asdf-swiftgen.git
```

swiftgen:

```shell
# Show all installable versions
asdf list-all swiftgen

# Install specific version
asdf install swiftgen latest

# Set a version globally (on your ~/.tool-versions file)
asdf global swiftgen latest

# Now swiftgen commands are available
swiftgen --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/younke/asdf-swiftgen/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Vasily Ptitsyn](https://github.com/younke/)
