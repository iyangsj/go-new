# go-new
A go tool for creating a new Go project (similar to cargo new)

## Installation

The tool `new` should be placed in the following directory:
```
$GOROOT/pkg/tool/$(go env GOOS)_$(go env GOARCH)/
```

## Usage
```
  go tool new myapp
  go tool new myapp --module github.com/user/myapp
  go tool new myapp --module github.com/user/myapp --git
```
