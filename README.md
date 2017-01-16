
The code is extracted from the standard library "go/types" and the tool "golang.org/x/tools/cmd/gotype"

It's meant to be used for experimentations of static analysis.

For building the project, you need GB (so that you don't depend on GOPATH)

```
$ go get github.com/constabulary/gb/...
```
Once you have GB installed,
```
$ cd src/gotype
$ gb build
$ ../../bin/gotype -help
```


