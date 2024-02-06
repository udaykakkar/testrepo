# testu

## Description
uu

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] testu`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree testu`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init testu
kpt live apply testu --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
