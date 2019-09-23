## やったこと

```
$ asdf plugin-add bazel
$ asdf install bazel 0.29.1
$ asdf global bazel 0.29.1
$ asdf plugin-add golang
$ asdf install golang 1.13
$ asdf global golang 1.13
$ go mod init github.com/zu-min/golang_echo
$ bazel run //hello
$ GO111MODULE=on go get github.com/labstack/echo/v4
$ bazel run //:gazelle -- update-repos -from_file=go.mod
$ bazel run //echo_server
```
