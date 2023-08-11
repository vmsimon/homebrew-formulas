<div align="center">

# vmsimon's Homebrew Tap
My personal Homebrew tap housing formulas for all my Homebrew projects.

<img src="https://raw.githubusercontent.com/vmsimon/homebrew-formulas/HEAD/showcase.png" alt="Showcase">

</div>

[Homebrew](https://brew.sh) is a fantastic package manager for macOS and Linux. I release some of my projects via Homebrew as it is widely used and easy to deploy to. This tap is a "self hosted" collection of Homebrew packages. For specific details about a formula contained in this tap, visit that formula's homepage or see the table below.

This repos is completely automated and inspired by [Homebrew Releaser](https://github.com/Justintime50/homebrew-releaser). If you are looking for a way to publish your own Homebrew formula on your behalf, you should check it out!

## Usage

```bash
# Setup tap
brew tap vmsimon/formulas

# Check the tap for available formulas
brew search vmsimon/formulas
```

<!-- project_table_start -->
| Project                                                                      | Description                                                                      | Install                             |
| ---------------------------------------------------------------------------- | -------------------------------------------------------------------------------- | ----------------------------------- |
<!-- project_table_end -->

## Development

```bash
# Audit a formula (lint)
brew audit --strict --online <formula_name>

# Test a formula
brew test <formula_name>

# Create a tar
tar -czf name-of-tar.tgz path/to/content

# Get the checksum of an archive
shasum -a 256 name-of-tar.tgz
```
