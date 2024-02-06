# rere

## Description


## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] rere`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree rere`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init rere
kpt live apply rere --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
