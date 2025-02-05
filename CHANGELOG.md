# Changelog

## 0.13.2

- PR #64 Added base as core dependency

## 0.13.1

- PR #56 Ensure that discovery of R versions on linux is done invoking the command, rather than Rcmd

## 0.13.0

- #52 Added roo environment options to see the available R versions to use when generating an environment
- #50 Added --r-version to environment init to specify the R version to use for the environment


## 0.12.1

- #45 Fixed restrictive detection of R path on linux machines

## 0.12.0

- #43 Added Documentation on usage
- #42 Add local source to use CRAN-like entries on our local disk
- #40 Allow to specify priority in sources
- #38, #39 Improve concurrency issues
- #37 Removed user notifier in favor of full rich console
- #35 Improved logic for automatic detection of R path
- #36 Handle dependencies with R of different versions (support R 4)
- #33 Verify the version of R in the init file, and use the environment data for version info
- #30 Fixed: roo install installs on default environment
- #28 environment init with no value will raise confusing exceptions

## 0.11.0

- First public release
