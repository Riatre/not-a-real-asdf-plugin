# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

# TODO: adapt this
asdf plugin test not-a-real-asdf-plugin https://github.com/Riatre/asdf-not-a-real-asdf-plugin.git "not-a-real-asdf-plugin --help"
```

Tests are automatically run in GitHub Actions on push and PR.
