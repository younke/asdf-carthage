<div align="center">

# asdf-carthage

[![Build](https://github.com/younke/asdf-carthage/actions/workflows/build.yml/badge.svg)](https://github.com/younke/asdf-carthage/actions/workflows/build.yml) [![Lint](https://github.com/younke/asdf-carthage/actions/workflows/lint.yml/badge.svg)](https://github.com/younke/asdf-carthage/actions/workflows/lint.yml) [![Mise](https://github.com/younke/asdf-carthage/actions/workflows/test-mise.yml/badge.svg)](https://github.com/younke/asdf-carthage/actions/workflows/test-mise.yml)

[carthage](https://github.com/Carthage/Carthage) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).
- [Xcode 10.0 (Swift 4.2)](https://github.com/Carthage/Carthage#installing-carthage)

# Install

Plugin:

```shell
asdf plugin add carthage
# or
asdf plugin add carthage https://github.com/younke/asdf-carthage.git
```

carthage:

```shell
# Show all installable versions
asdf list-all carthage

# Install specific version
asdf install carthage latest

# Set a version globally (on your ~/.tool-versions file)
asdf set -u carthage latest

# Now carthage commands are available
carthage
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/younke/asdf-carthage/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Vasily Ptitsyn](https://github.com/younke/)
