<div align="center">

# asdf-go-pagerduty [![Build](https://github.com/ORCID/asdf-go-pagerduty/actions/workflows/build.yml/badge.svg)](https://github.com/ORCID/asdf-go-pagerduty/actions/workflows/build.yml) [![Lint](https://github.com/ORCID/asdf-go-pagerduty/actions/workflows/lint.yml/badge.svg)](https://github.com/ORCID/asdf-go-pagerduty/actions/workflows/lint.yml)


[go-pagerduty](https://github.com/ORCID/asdf-go-pagerduty) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Why?](#why)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `unzip`: generic POSIX utilities.

# Install

Plugin:

```shell
asdf plugin add go-pagerduty https://github.com/ORCID/asdf-go-pagerduty.git
```

go-pagerduty:

```shell
# Show all installable versions
asdf list-all go-pagerduty

# Install specific version
asdf install go-pagerduty latest

# Set a version globally (on your ~/.tool-versions file)
asdf global go-pagerduty latest

# Now go-pagerduty commands are available
go-pagerduty --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

