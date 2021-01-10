<div align="center">

# asdf-mongosh ![Build](https://github.com/itspngu/asdf-mongosh/workflows/Build/badge.svg) ![Lint](https://github.com/itspngu/asdf-mongosh/workflows/Lint/badge.svg)

[mongosh](https://github.com/mongodb-js/mongosh) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [License](#license)

# Dependencies

- `curl`, `git` - for mongosh downloads from upstream releases
- `bash` - asdf-vm is built on this

# Install

Plugin:

```shell
asdf plugin add mongosh https://github.com/itspngu/asdf-mongosh.git
```

mongosh:

```shell
# Show all installable versions
asdf list-all mongosh

# Install specific version
asdf install mongosh latest

# Set a version globally (on your ~/.tool-versions file)
asdf global mongosh latest
```

Refer to the [upstream mongosh repository](https://github.com/mongodb-js/mongosh) for documentation and
usage instructions of the included tools.

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# License

See [LICENSE](LICENSE)
