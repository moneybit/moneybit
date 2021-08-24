# Moneybit - Personal Finance Software

## Project Layout

### Branches (dev, release/, feature/, fix/, experimental/, integration)

- dev contains all merges for the next release and all tests must pass
- release/alpha is the current alpha version
- release/beta is the current beta version
- release/current is the current stable version
- release/lts is the current long-term support (LTS) stable version
- feature only merges to dev once considered stable
- fix may merge directly to release if considered critical or at the maintainer team discretion
- experimental is for any code that may or may not become a feature and must not be merged to the integration branch
- integration automatically receives merges from all branches, except experimental, with conflicts manually resolved
- only critical fixes are merged to the LTS release branch

### Directories

- crates - Rust code
- docs - Documentation
- packages - Typescript code
