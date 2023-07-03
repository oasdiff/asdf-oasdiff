<div align="center">

# asdf-oasdiff [![Build](https://github.com/oasdiff/asdf-oasdiff/actions/workflows/build.yml/badge.svg)](https://github.com/oasdiff/asdf-oasdiff/actions/workflows/build.yml) [![Lint](https://github.com/oasdiff/asdf-oasdiff/actions/workflows/lint.yml/badge.svg)](https://github.com/oasdiff/asdf-oasdiff/actions/workflows/lint.yml)

[oasdiff](https://github.com/tufin/oasdiff) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [asdf-oasdiff  ](#asdf-oasdiff--)
- [Contents](#contents)
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
asdf plugin add oasdiff
# or
asdf plugin add oasdiff https://github.com/oasdiff/asdf-oasdiff.git
```

oasdiff:

```shell
# Show all installable versions
asdf list-all oasdiff

# Install specific version
asdf install oasdiff latest

# Set a version globally (on your ~/.tool-versions file)
asdf global oasdiff latest

# Now oasdiff commands are available
oasdiff --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/oasdiff/asdf-oasdiff/graphs/contributors)!

# License

See [LICENSE](LICENSE)
