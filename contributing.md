# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

#
asdf plugin test clusterawsadm https://github.com/deas/asdf-clusterawsadm.git "clusterawsadm --help"
```

Tests are automatically run in GitHub Actions on push and PR.
