# CHANGELOG

## 1.33.0+

- Merged upstream changes through c375e30 into fork
- Preserved fork-specific arm64 Lambda deployment support
- Kept `lambda_architecture` support for `x86_64` and `arm64`
- Kept arm64 packaging via `manylinux2014_aarch64`
- Kept Lambda architecture updates on `UpdateFunctionCode`

## 1.32.0+

* feature:Lambda:Add `lambda_architecture` config support for `x86_64` and `arm64` (#1)
* feature:Python:Drop support for Python 3.9 and add Python 3.14 (#2)
* bugfix:Resolve datetime deprecation warnings (#3)
* bugfix:Avoid local auth warning and pytest return warning (#4)
