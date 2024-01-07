# testing-here-again

## Description
learning package initiaton

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] testing-here-again`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree testing-here-again`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init testing-here-again
kpt live apply testing-here-again --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
