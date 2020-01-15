# acmefmt

This is an expanded fork of [acmego](https://github.com/9fans/go/blob/master/acme/acmego/main.go) by Russ Cox and the Go authors.

It removes the the go import-only stuff (since I always want the gofmt as well) and adds the same on-save format functionality for more file types.

It uses `js-beautify` (npm package) for code formatting of `.html`, `.css` and `.js` files and `dartfmt` for flutter/dart code.

Go and dart have pretty undisputable formatting rules, but the others are more mayhem. I like tabs, so I have forced the formatting into that for each one. To change the arguments to each command (and to add new ones and change the main command) is just a matter of changing the if-statement in the for-loop in main().

This is for me a replacement for acmego and a tool to code format whatever language I am currently working in.

## License

A form of BSD license from the Go authors. See LICENSE, which is copied from the https://github.com/9fans/go source tree.
