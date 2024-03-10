<div align="center">

# asdf-weed [![Build](https://github.com/jamesandariese/asdf-weed/actions/workflows/build.yml/badge.svg)](https://github.com/jamesandariese/asdf-weed/actions/workflows/build.yml) [![Lint](https://github.com/jamesandariese/asdf-weed/actions/workflows/lint.yml/badge.svg)](https://github.com/jamesandariese/asdf-weed/actions/workflows/lint.yml)

[weed](https://github.com/seaweedfs/seaweedfs) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add weed
# or
asdf plugin add weed https://github.com/jamesandariese/asdf-weed.git
```

weed:

```shell
# Show all installable versions
asdf list-all weed

# Install specific version
asdf install weed latest

# Set a version globally (on your ~/.tool-versions file)
asdf global weed latest

# Now weed commands are available
weed --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/jamesandariese/asdf-weed/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [James Andariese](https://github.com/jamesandariese/)
