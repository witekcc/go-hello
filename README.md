nstall:
installation files in c:/go
set GOROOT = C:\Go
set PATH: ;C:\Go\bin

workspace (expected):
create folders:
src
bin
pkg
set GOPATH = C:\gocode
set PATH: %GOPATH%/bin
set if needed


Example 1:
create the file:
/src/github.com/witekcc/hello/hello.go
package main
import "fmt"
func main() {
    fmt.Printf("1 hello, world\n")
}
install it:
go install github.com\witekcc\hello
file is created in the pkg folder
    run it
    hello
assuming that PATH contains %GOPATH%/bin
