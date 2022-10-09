<div align="center">

# asdf-clusterawsadm [![Build](https://github.com/deas/asdf-clusterawsadm/actions/workflows/build.yml/badge.svg)](https://github.com/deas/asdf-clusterawsadm/actions/workflows/build.yml) [![Lint](https://github.com/deas/asdf-clusterawsadm/actions/workflows/lint.yml/badge.svg)](https://github.com/deas/asdf-clusterawsadm/actions/workflows/lint.yml)


[clusterawsadm](https://github.com/kubernetes-sigs/cluster-api-provider-aws) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add clusterawsadm
# or
asdf plugin add clusterawsadm https://github.com/deas/asdf-clusterawsadm.git
```

clusterawsadm:

```shell
# Show all installable versions
asdf list-all clusterawsadm

# Install specific version
asdf install clusterawsadm latest

# Set a version globally (on your ~/.tool-versions file)
asdf global clusterawsadm latest

# Now clusterawsadm commands are available
clusterawsadm --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/deas/asdf-clusterawsadm/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Andreas Steffan](https://github.com/deas/)
