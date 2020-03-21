# go-playground
Playing with golang

## Sources
https://golang.org/doc/code.html

## hello world
What I did for init commit, other than creating `hello.go`:
```
// Creating go.mod
go mod init example.com/user/hello

// Installing binary of `hello.go` in `$HOME/go/bin/hello`:
go install example.com/user/hello
```
So that running `$HOME/go/bin/hello` will print `hello, world`
