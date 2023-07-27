<div align="center">

# asdf-not-a-real-asdf-plugin [![Build](https://github.com/Riatre/asdf-not-a-real-asdf-plugin/actions/workflows/build.yml/badge.svg)](https://github.com/Riatre/asdf-not-a-real-asdf-plugin/actions/workflows/build.yml) [![Lint](https://github.com/Riatre/asdf-not-a-real-asdf-plugin/actions/workflows/lint.yml/badge.svg)](https://github.com/Riatre/asdf-not-a-real-asdf-plugin/actions/workflows/lint.yml)

[not-a-real-asdf-plugin](https://github.com/Riatre/not-a-real-asdf-plugin) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add not-a-real-asdf-plugin
# or
asdf plugin add not-a-real-asdf-plugin https://github.com/Riatre/asdf-not-a-real-asdf-plugin.git
```

not-a-real-asdf-plugin:

```shell
# Show all installable versions
asdf list-all not-a-real-asdf-plugin

# Install specific version
asdf install not-a-real-asdf-plugin latest

# Set a version globally (on your ~/.tool-versions file)
asdf global not-a-real-asdf-plugin latest

# Now not-a-real-asdf-plugin commands are available
not-a-real-asdf-plugin --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/Riatre/asdf-not-a-real-asdf-plugin/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Riatre Foo](https://github.com/Riatre/)
