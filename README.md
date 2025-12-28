<div align="center">

# asdf-swiftgen

[![asdf](https://github.com/younke/asdf-swiftgen/actions/workflows/build.yml/badge.svg)](https://github.com/younke/asdf-swiftgen/actions/workflows/build.yml)
[![mise](https://github.com/younke/asdf-swiftgen/actions/workflows/test-mise.yml/badge.svg)](https://github.com/younke/asdf-swiftgen/actions/workflows/test-mise.yml)
[![lint](https://github.com/younke/asdf-swiftgen/actions/workflows/lint.yml/badge.svg)](https://github.com/younke/asdf-swiftgen/actions/workflows/lint.yml)

[swiftgen](https://github.com/SwiftGen/SwiftGen) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Why?](#why)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `unzip`: generic POSIX utilities.

# Install

Plugin:

```shell
asdf plugin add swiftgen
# or
asdf plugin add swiftgen https://github.com/younke/asdf-swiftgen.git
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

# Templates

You probably want to copy SwiftGen bundled `templates` into your project directory.

Read [SwiftGen documentation](https://github.com/SwiftGen/SwiftGen#choosing-your-template) on how to use templates.

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/younke/asdf-swiftgen/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Vasily Ptitsyn](https://github.com/younke/)
