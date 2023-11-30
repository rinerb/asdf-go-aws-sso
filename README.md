<div align="center">

# asdf-go-aws-sso [![Build](https://github.com/rinerb/asdf-go-aws-sso/actions/workflows/build.yml/badge.svg)](https://github.com/rinerb/asdf-go-aws-sso/actions/workflows/build.yml) [![Lint](https://github.com/rinerb/asdf-go-aws-sso/actions/workflows/lint.yml/badge.svg)](https://github.com/rinerb/asdf-go-aws-sso/actions/workflows/lint.yml)

[go-aws-sso](https://github.com/theurichde/go-aws-sso) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add go-aws-sso
# or
asdf plugin add go-aws-sso https://github.com/rinerb/asdf-go-aws-sso.git
```

go-aws-sso:

```shell
# Show all installable versions
asdf list-all go-aws-sso

# Install specific version
asdf install go-aws-sso latest

# Set a version globally (on your ~/.tool-versions file)
asdf global go-aws-sso latest

# Now go-aws-sso commands are available
go-aws-sso --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/rinerb/asdf-go-aws-sso/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Bryce Riner](https://github.com/rinerb/)
