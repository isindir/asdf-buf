<div align="center">

# asdf-buf [![Build](https://github.com/isindir/asdf-buf/actions/workflows/build.yml/badge.svg)](https://github.com/isindir/asdf-buf/actions/workflows/build.yml) [![Lint](https://github.com/isindir/asdf-buf/actions/workflows/lint.yml/badge.svg)](https://github.com/isindir/asdf-buf/actions/workflows/lint.yml)

[buf](https://github.com/bufbuild/buf) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Dependencies

- `go`, `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add buf
# or
asdf plugin add buf https://github.com/isindir/asdf-buf.git
```

buf:

```shell
# Show all installable versions
asdf list-all buf

# Install specific version
asdf install buf latest

# Set a version globally (on your ~/.tool-versions file)
asdf global buf latest

# Now buf commands are available
buf --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/isindir/asdf-buf/graphs/contributors)!
