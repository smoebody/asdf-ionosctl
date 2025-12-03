<div align="center">

# asdf-ionosctl [![Build](https://github.com/b1-systems/asdf-ionosctl/actions/workflows/build.yml/badge.svg)](https://github.com/b1-systems/asdf-ionosctl/actions/workflows/build.yml) [![Lint](https://github.com/b1-systems/asdf-ionosctl/actions/workflows/lint.yml/badge.svg)](https://github.com/b1-systems/asdf-ionosctl/actions/workflows/lint.yml)

[ionosctl](https://docs.ionos.com/cli-ionosctl) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [asdf-ionosctl  ](#asdf-ionosctl--)
- [Contents](#contents)
- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).

# Install

Plugin:

```shell
asdf plugin add ionosctl
# or
asdf plugin add ionosctl https://github.com/b1-systems/asdf-ionosctl
```

ionosctl:

```shell
# Show all installable versions
asdf list-all ionosctl

# Install specific version
asdf install ionosctl latest

# Set a version globally (on your ~/.tool-versions file)
asdf global ionosctl latest

# Now ionosctl commands are available
ionosctl --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/b1-systems/asdf-ionosctl/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [B1 Systems GmbH](https://github.com/b1-systems/)
