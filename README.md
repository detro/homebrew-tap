# Homebrew Tap by Zio Ivan (a.k.a. Detro)

A [Homebrew](https://brew.sh) tap for [detro](https://github.com/detro)'s projects.

Everything in here is published automatically by the release pipeline of the
project it belongs to, so the files under `Casks/` are generated and should
never be edited by hand.

## Available casks

| Cask      | Project                                           | Description                                                                  |
|-----------|---------------------------------------------------|------------------------------------------------------------------------------|
| `spelunk` | [detro/spelunk](https://github.com/detro/spelunk) | Retrieve secrets from Kubernetes, Vault, AWS, GCP, Azure, 1Password and more |

## How do I install these?

```shell
brew install detro/tap/<Cask Name>
```

Or tap first, then install:

```shell
brew tap detro/tap
brew install <Cask Name>
```

Or, in a `brew bundle` `Brewfile`:

```ruby
tap "detro/tap"
cask "spelunk"
```

## Documentation

`brew help`, `man brew` or check [Homebrew's documentation](https://docs.brew.sh).
