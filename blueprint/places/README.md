# blueprint/base1

## Description
base test blueprint

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] blueprint/base1`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree blueprint/base1`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init blueprint/base1
kpt live apply blueprint/base1 --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
