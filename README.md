# rnd-example

## Description
sample description

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] rnd-example`
Details: https://googlecontainertools.github.io/kpt/reference/pkg/get/

### View package content
`kpt cfg tree rnd-example`
Details: https://googlecontainertools.github.io/kpt/reference/cfg/tree/

### List setters
`kpt cfg list-setters rnd-example`
Details: https://googlecontainertools.github.io/kpt/reference/cfg/list-setters/

### Set a value
`kpt cfg set rnd-example NAME VALUE`
Details: https://googlecontainertools.github.io/kpt/reference/cfg/set/

### Apply the package
```
kpt live init rnd-example
kpt live apply rnd-example --reconcile-timeout=2m --output=table
```
Details: https://googlecontainertools.github.io/kpt/reference/live/
