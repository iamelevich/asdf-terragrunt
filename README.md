[![Build Status](https://github.com/iamelevich/asdf-terragrunt/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/ohmer/asdf-terragrunt/actions/workflows/ci.yml)

# asdf-terragrunt

Originally from https://github.com/lotia/asdf-terragrunt where it no longer appears to be maintained.

[Terragrunt](https://github.com/gruntwork-io/terragrunt) plugin for the [asdf](https://github.com/asdf-vm/asdf) version manager.
Check out the [asdf](https://github.com/asdf-vm/asdf) readme for instructions.

### Install

```
asdf plugin-add terragrunt https://github.com/iamelevich/asdf-terragrunt
```

```
# Show all installable versions
asdf list-all terragrunt

# Install specific version
asdf install terragrunt latest

# Set a version globally (on your ~/.tool-versions file)
asdf global terragrunt latest

# Now terragrunt commands are available
terragrunt
```

### Updates

The main difference from https://github.com/ohmer/asdf-terragrunt that there is possible to install old versions.

### Environment Variable Options

- `ASDF_TERRAGRUNT_OVERWRITE_ARCH`: force the plugin to use a specified processor architecture rather than the
  automatically detected value. Useful, for example, for allowing users on M1 Macs to install `amd64` binaries when
  there's no `arm64` binary available.
