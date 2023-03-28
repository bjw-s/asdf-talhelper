<div align="center">

# asdf-talhelper [![Build](https://github.com/bjw-s/asdf-talhelper/actions/workflows/build.yml/badge.svg)](https://github.com/bjw-s/asdf-talhelper/actions/workflows/build.yml) [![Lint](https://github.com/bjw-s/asdf-talhelper/actions/workflows/lint.yml/badge.svg)](https://github.com/bjw-s/asdf-talhelper/actions/workflows/lint.yml)


[talhelper](https://github.com/budimanjojo/talhelper) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.

# Install

Plugin:

```shell
asdf plugin add talhelper
# or
asdf plugin add talhelper https://github.com/bjw-s/asdf-talhelper.git
```

talhelper:

```shell
# Show all installable versions
asdf list-all talhelper

# Install specific version
asdf install talhelper latest

# Set a version globally (on your ~/.tool-versions file)
asdf global talhelper latest

# Now talhelper commands are available
talhelper --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/bjw-s/asdf-talhelper/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Bernd Schorgers](https://github.com/bjw-s/)
