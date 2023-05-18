# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

#
asdf plugin test njs https://github.com/4141done/asdf-njs.git "njs -v"
```

Tests are automatically run in GitHub Actions on push and PR.
