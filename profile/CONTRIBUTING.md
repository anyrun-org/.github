# Contributing to Anyrun

This document is for people wanting to contribute to anyrun repositories, or to write their own anyrun plugins.

## Overview

This document provides general Contributing Guidelines.
Check out the specific submodules Contributing Guidelines for further information.

* [anyrun](https://github.com/anyrun-org/anyrun/blob/main/README.md): Main project repository that contains all the information required for using Anyrun.

## Conventions

The general process for contributing is as follows:

1. Fork the repository you want to work on
1. Create a new branch descriptive of you changes
1. Commit all changes
1. Open a pull request to the upstream repo
1. Wait for your code to be reviewed and merged, be open to dialog on changes, update your branch if necessary

<!--
### Branch Conventions

Most changes should go to the `main` branch.
-->

<!--
### Commit Conventions

-->

### Code Conventions

Format your code with [rustfmt](https://github.com/rust-lang/rustfmt).

Catch mistakes and improve your code with [clippy](https://github.com/rust-lang/rust-clippy),
use the `--all-targets -- --deny warnings` flags and resolve all errors and warnings.
