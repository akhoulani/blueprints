# my-new-package

## Description
learning package initiaton

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] my-new-package`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree my-new-package`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init my-new-package
kpt live apply my-new-package --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
