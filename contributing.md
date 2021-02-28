# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

#
asdf plugin test swiftgen https://github.com/younke/asdf-swiftgen.git "swiftgen --help"
```

Tests are automatically run in GitHub Actions on push and PR.
