# homebrew-tap

Personal Homebrew tap for command-line tools maintained by
[@jaisonerick](https://github.com/jaisonerick).

## Use

```sh
brew tap jaisonerick/tap

brew install macwifi-cli
```

After tapping you can also use the fully-qualified form:

```sh
brew install jaisonerick/tap/macwifi-cli
```

## Available formulas

| Formula | Description |
| ------- | ----------- |
| [`macwifi-cli`](Formula/macwifi-cli.rb) | Drop-in `airport` replacement for macOS 13+. Scans Wi-Fi networks, inspects the current connection, and reads saved Keychain passwords. |

## Updates

Formulas in this repository are updated automatically by
[GoReleaser](https://goreleaser.com/) when the corresponding upstream
project tags a new release. Edits by hand are rare and usually mean
something is being repaired.
