# Slate

![loc](https://sloc.xyz/github/nektro/slate)
[![license](https://img.shields.io/github/license/nektro/slate.svg)](https://github.com/nektro/slate/blob/master/LICENSE)
[![discord](https://img.shields.io/discord/551971034593755159.svg?logo=discord)](https://discord.gg/P6Y4zQC)
[![goreportcard](https://goreportcard.com/badge/github.com/nektro/slate)](https://goreportcard.com/report/github.com/nektro/slate)

A new programming langauge made by me. Used as a tool to learn about compilers.

## Using

Dependencies
- Golang 1.14
- LLVM 10

Running `./start_local.sh` will build and run Slate on the x86_64 Hello World. Feel free to edit either file.
```
go build
./slate -run {path/to/src_file.slate}
llvm-as-10 out.ll
lli-10 out.bc
```

## Inspirations
- https://github.com/golang/go
- https://github.com/ziglang/zig
- https://github.com/denoland/deno

## Contributing
Issues and Pull Requests welcome. As the project progresses I will make a list of focus areas.

## Contact
- hello@nektro.net
- https://twitter.com/nektro

## License
MIT
