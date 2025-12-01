[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![Go Version](https://img.shields.io/badge/Go-1.23.0+-79D4FD.svg?logo=go)](https://go.dev/)
[![Release](https://img.shields.io/github/tag/the-flx/flx.go.svg?label=release&logo=github)](https://github.com/the-flx/flx.go/releases/latest)
[![Go Reference](https://pkg.go.dev/badge/github.com/the-flx/flx.go.svg)](https://pkg.go.dev/github.com/the-flx/flx.go)

# flx.go
> Rewrite emacs-flx in Go

[![CI](https://github.com/the-flx/flx.go/actions/workflows/test.yml/badge.svg)](https://github.com/the-flx/flx.go/actions/workflows/test.yml)

## 🔨 Usage

```go
import "github.com/the-flx/flx.go"

fmt.Println(flx.Score("switch-to-buffer", "stb").Score)  // 237
```

## 🛠️ Development

To run tests:

```sh
$ go test ./test/
```

## ⚜️ License

`flx.go` is distributed under the terms of the MIT license.

See [`LICENSE`](./LICENSE) for details.


<!-- Links -->

[Mx]: https://github.com/jcs090218/Unity.Mx

[flx]: https://github.com/lewang/flx
