![Preview](https://raw.githubusercontent.com/mschuchard/linter-icinga-validate/master/linter_icinga_validate.png)

### Linter-Icinga-Validate
`Linter-Icinga-Validate` aims to provide functional and robust `icinga2 daemon --validate` linting functionality within Atom.

### Installation
The `icinga2-bin` package is required to be installed before using this. The `Linter` and `Language-Icinga2` Atom packages are also required, but should be automatically installed as dependencies thanks to steelbrain's `package-deps`.

### Usage
- Icinga requires elevated user privileges to execute even though the binary does not actually need them. They have plans to remediate this, but until then this linter requires `sudo` to execute the `icinga2` binary executable. Therefore, this is only compatible with \*nix systems.
