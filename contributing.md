# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

#
asdf plugin test lsd https://github.com/argylelabcoat/asdf-lsd.git "lsd --help"
```

Tests are automatically run in GitHub Actions on push and PR.