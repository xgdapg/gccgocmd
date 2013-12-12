Install
==========

```bash
git clone https://github.com/xgdapg/gccgocmd.git
cd gccgocmd
gccgo -c -g -o gccgocmd.o build.go clean.go discovery.go doc.go env.go fix.go fmt.go get.go go11.go help.go http.go list.go main.go pkg.go run.go signal.go signal_unix.go test.go testflag.go tool.go vcs.go version.go vet.go && gccgo -o go gccgocmd.o
```