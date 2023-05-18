<div align="center">

# asdf-njs [![Build](https://github.com/4141done/asdf-njs/actions/workflows/build.yml/badge.svg)](https://github.com/4141done/asdf-njs/actions/workflows/build.yml) [![Lint](https://github.com/4141done/asdf-njs/actions/workflows/lint.yml/badge.svg)](https://github.com/4141done/asdf-njs/actions/workflows/lint.yml)


[njs](https://nginx.org/en/docs/njs/) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add njs
# or
asdf plugin add njs https://github.com/4141done/asdf-njs.git
```

njs:

```shell
# Show all installable versions
asdf list-all njs

# Install specific version
asdf install njs latest

# Set a version globally (on your ~/.tool-versions file)
asdf global njs latest

# Now njs commands are available
njs -v
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/4141done/asdf-njs/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Javier Evans](https://github.com/4141done/)
