# webassembly-demo

A simple WebAssembly app rendering `printf` method from C language to HTML.

[![WebAssembly](https://img.shields.io/badge/WebAssembly-white?logo=webassembly&style=flat)](https://webassembly.org/)

## Prerequisites
- [Emscripten Setup](https://emscripten.org/docs/getting_started/downloads.html)
- [http-server](https://www.npmjs.com/package/http-server)

## Development

1. Modify the `index.c` file

2. Rebuild the JS code
```shell
emcc index.c -o index.js
```