# Changelog

## MOSAlloc 1.2.6

### News
- Added automatic filling of missing opts parameters.
- Added Example 10 to mosalloc.R.
- Added a paragraph to mosalloc.R concerning numerical issues arising from extreme heterogeneity in the input data.
- Added a test for equality cost constraints.

### Bug fixes
- Avoided numerical discrepancies arising from division and matrix multiplication.
- Fixed the return of lower and upper cost bounds in mosallocSTRS.R.

---

## MOSAlloc 1.2.5

### News
- Added installation instructions to `README.md`.

### Bug fixes
- Correct tolerance calculations to align with sampling theory.

---

## MOSAlloc 1.2.4

### News
- Added a `NEWS.md` file to track changes to the package.
- Added URL for BugFixes to DESCIPTION file for better troubleshooting.

### Bug fixes
- Fixed a numerical instability that caused errors on macOS arm64 (Apple Silicon).
- Linux and macOS x86_64 platforms were unaffected.

---

## MOSAlloc 1.2.3

- Initial release.
