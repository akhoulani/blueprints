# nikita

## Description
learning package initiaton

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] nikita`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree nikita`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init nikita
kpt live apply nikita --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
