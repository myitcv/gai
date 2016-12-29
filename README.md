## `gai`

`gai` is work-in-progress pipeline wrapper around `go generate`, `go install`, [`gotype`](https://github.com/golang/tools/tree/7a49e427c87609bb42725524c71c89b244c5fa87/cmd/gotype)
and various vetters and linters.

### `gotype`

In https://github.com/golang/tools/commit/f5a6ee1ea9f7b3a91e3e70dc1b9706886d0e0ae3 `gotype` was removed
`golang.org/x/tools`. We reproduce a copy of it here temporarily. A copy of the relevant license file can
be found in the `gotype` directory.
