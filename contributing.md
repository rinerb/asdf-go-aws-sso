# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

# TODO: adapt this
asdf plugin test go-aws-sso https://github.com/rinerb/asdf-go-aws-sso.git "go-aws-sso --help"
```

Tests are automatically run in GitHub Actions on push and PR.
