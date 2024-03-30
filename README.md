# GitHub CLI

`gh` is GitHub on the command line. It brings pull requests, issues, and other GitHub concepts to the terminal next to where you are already working with `git` and your c

GitHub CLI is supported for users on GitHub.com and GitHub Enterprise Server 2.20+ with support for macOS, Windows, and Linux.

 for usage instructions [see the manual][manual].

## Contributing

If anything feels off, or if you feel that some functionality is missing, please check out the [contributing page][contributing]. There you will find instructions for sharing your feedback, building the tool locally, and submitting pull requests to the project.

If you are a hubber and are interested in shipping new commands for the CLI, check out our [doc on internal contributions][intake-doc].

<!-- this anchor is linked to from elsewhere, so avoid renaming it -->
## Installation

### macOS

`gh` is available via [Homebrew][], [MacPorts][], [Conda][], [Spack][], [Webi][], and as a downloadable binary from the [releases page][].

#### Homebrew

| Install:          | Upgrade:          |
| ----------------- | ----------------- |
| `brew install gh` | `brew upgrade gh` |

#### MacPorts

| Install:               | Upgrade:                                       |
| ---------------------- | ---------------------------------------------- |
| `sudo port install gh` | `sudo port selfupdate && sudo port upgrade gh` |

#### Conda

| Install:                                 | Upgrade:                                |
|------------------------------------------|-----------------------------------------|
| `conda install gh --channel conda-forge` | `conda update gh --channel conda-forge` |

Additional Conda installation options available

#### Spack

| Install:           | Upgrade:                                 |
| ------------------ | ---------------------------------------- |
| `spack install gh` | `spack uninstall gh && spack install gh` |

#### Webi

| Install:                            | Upgrade:         |
| ----------------------------------- | ---------------- |
| `curl -sS https://webi.sh/gh \| sh` | `webi gh@stable` |

For more information about the Webi installer se

### Linux & BSD

`gh` is available via:
- [our Debian and RPM repositor

#### WinGet

| Install:            | Upgrade:            |
| ------------------- | --------------------|
| `winget install --id GitHub.cli` | `winget upgrade --id GitHub.cli` |

> **Note**  
> The Windows installer modifies your PATH. When using Windows Terminal, you will need to **open a new window** for the changes to take effect. (Simply opening a new tab will _not_ be sufficient.)

#### scoo

MSI installers are available for download on the [releases page][].

### Codespaces

To add GitHub CLI to your codespace, add the following t

```json
"features": {
  "ghcr.io/devcontainers/features/github-cli:1": {}
}
`

### Other platformsom source].

## Comparison with hub

For many years, [hub][] was the unofficial GitHub CLI tool. `gh` is a new project that helps us explore
what an official GitHub CLI tool can look like with a fundamentally different design. While bot//www.macports.org
[winget]: https://github.com/microsoft/winget-cli
[scoop]: https://scoop.sh
[Chocolatey]: https://chocolatey.org
[Conda]: https://docs.conda.io/en/latest/
[Spack]: https://spack.io
[Webi]: https://webinstall.dev
[relea
