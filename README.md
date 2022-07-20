# WebAssembly Landscape

Date: 2022-07-20


## Supported Languages


### First class citizens:

* [C](http://www.open-std.org/jtc1/sc22/wg14/)
* [C++](https://isocpp.org/)
* [Rust](https://github.com/rust-lang/rust) 
* [AssemblyScript](https://github.com/AssemblyScript/assemblyscript)
* [TinyGo](https://github.com/tinygo-org/tinygo)
* [Zig](https://github.com/ziglang/zig)
* [Solidity](https://github.com/ethereum/solidity)
* [Fe](https://github.com/ethereum/fe)

### Second class citizens:

* [JavaScript](https://wasmedge.org/book/en/dev/js.html)
* [C#](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/)
* [F#](https://fsharp.org/)
* [Go](https://github.com/golang/go)
* [Python](https://github.com/python)
* [Java]()
* [Kotlin](https://github.com/JetBrains/kotlin)
* [Swift](https://github.com/apple/swift)
* [D](https://dlang.org/)
* [Pascal](http://www.pascal-programming.info/)


## Supported Browsers

* Chrome
* Safari
* Firefox
* Edge
* Opera
* QQ 

> Soure: https://caniuse.com/?search=webassembly 

## WebAssembly VMs
* [Gasm](https://github.com/mathetake/gasm)
* [Lucet/wasmtime](https://github.com/bytecodealliance/lucet)
* [WasmEdge](https://github.com/WasmEdge/WasmEdge)
* [Swam](https://github.com/satabin/swam)
* [V8](https://github.com/v8/v8)
* [WAMR](https://github.com/bytecodealliance/wasm-micro-runtime)
* [wasm3](https://github.com/wasm3/wasm3)
* [wasmer](https://github.com/wasmerio/wasmer)
* [wasmi](https://github.com/paritytech/wasmi)
* [WAVM](https://github.com/WAVM/WAVM)

## Toolchains
* [Cargo](https://github.com/rust-lang/cargo)
* [Cranelift](https://github.com/bytecodealliance/cranelift)
* [Emscripten](https://github.com/emscripten-core/emscripten)
* [Solang](https://github.com/hyperledger-labs/solang)
* [SOLL](https://github.com/second-state/SOLL)
* [rustwasmc](https://github.com/second-state/rustwasmc)
* [wasm-pack](https://github.com/rustwasm/wasm-pack)

## WebAssembly Extensions

* [DWARF](https://lucumr.pocoo.org/2020/11/30/how-to-wasm-dwarf/)
* [ewasm](https://github.com/ewasm)
* [Nanoprocess](https://bytecodealliance.org/articles/1-year-update)
* [SIMD](https://github.com/WebAssembly/simd)
* [WASI](https://wasi.dev/)
* [wasi-nn](https://github.com/WebAssembly/wasi-nn)
* [wasi-socket](https://radu-matei.com/blog/towards-sockets-networking-wasi/)
* [wasi-storage](https://github.com/second-state/ssvm-napi-extensions)
* [wasi-tensorflow](https://github.com/second-state/ssvm-napi-extensions)

## Debugging
* DWARF

## Registries
* Solo.io
* WAPM

## Observability
* Sentry
* Envoy

## Orchestrations
* Atmo
* [K8s](https://wasmedge.org/book/en/kubernetes.html)
* Krustlet
* OCI
* OpenEuler/iSula
* waSCC

## Security
* none

## Testing
* none

## Popular Libraries Compiled to WebAssembly
* TensorFlow
* FFMPG
* SQLite
* ONNX.js

## Popular Products Using WebAssembly
* Figma
* Zoom
* Google Meeting
* Bilibili
* Privoce
* Master
* Squoosh
* Shopify

## Application Servers
* Node.js
* Deno
* Wasm-joey
* Blazor WebAssembly

## Cloud Providers
* Cloudflare
* Fastly
* TencentCloud Serverless
* Second State Functions

## Blockchains
* Cosmos-wasm
* Definity
* Ethereum
* EOS
* Near
* Oasis Labs
* ParaState
* Substrate 
* Solana


## Adding to this landscape

Please ensure your pull request adheres to the following guidelines:

- Search previous suggestions before making a new one, as yours may be a duplicate.
- Make an individual pull request for each suggestion.
- Use the following format: `[Name](link)`
- Link additions should be added to the bottom of the relevant category, with the exception of date ordered categories.
- New categories or improvements to the existing categorization are welcome.
- Check your spelling and grammar.
- Make sure your text editor is set to remove trailing whitespace.
- The pull request and commit should have a useful title.
- The body of your commit message should contain a link to the repository.

Thank you for your suggestions!
