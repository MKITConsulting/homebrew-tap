# MKITConsulting Homebrew Tap

Homebrew tap for [MKITConsulting](https://github.com/MKITConsulting) command-line tools.

## Install

```bash
brew install --cask mkitconsulting/tap/<name>
```

Auto-taps; or run `brew tap mkitconsulting/tap` first. Upgrade with
`brew upgrade --cask <name>`. Casks support macOS and Linux, Intel and Apple Silicon.

## Available casks

| Cask | Description | Source repo |
|------|-------------|-------------|
| [`zensu`](Casks/zensu.rb) | GitHub-CLI-style terminal client for the Zensu Product Lifecycle Manager | [MKITConsulting/zensu-cli](https://github.com/MKITConsulting/zensu-cli) |

## Maintenance

Casks in `Casks/*.rb` are generated and pushed automatically by
[GoReleaser](https://goreleaser.com/) from each tool's own repository on every
tagged release — do not edit them by hand. Adding a tool means a new
`homebrew_casks` block in that tool's `.goreleaser.yaml` pointing at this tap.
