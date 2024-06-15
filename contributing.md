# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

asdf plugin test pixi https://github.com/pavelzw/asdf-pixi.git "pixi --help"
```

Tests are automatically run in GitHub Actions on push and PR.
