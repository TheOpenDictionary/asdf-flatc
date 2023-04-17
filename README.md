<div align="center">

# asdf-flatc [![Build](https://github.com/TheOpenDictionary/asdf-flatc/actions/workflows/build.yml/badge.svg)](https://github.com/TheOpenDictionary/asdf-flatc/actions/workflows/build.yml) [![Lint](https://github.com/TheOpenDictionary/asdf-flatc/actions/workflows/lint.yml/badge.svg)](https://github.com/TheOpenDictionary/asdf-flatc/actions/workflows/lint.yml)

[Flatbuffers](https://flatbuffers.dev) `flatc` plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add flatc
# or
asdf plugin add flatc https://github.com/TheOpenDictionary/asdf-flatc.git
```

flatc:

```shell
# Show all installable versions
asdf list-all flatc

# Install specific version
asdf install flatc latest

# Set a version globally (on your ~/.tool-versions file)
asdf global flatc latest

# Now flatc commands are available
flatc --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/TheOpenDictionary/asdf-flatc/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Tyler Nickerson](https://github.com/TheOpenDictionary/)
