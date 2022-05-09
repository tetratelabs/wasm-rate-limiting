# wasm-rate-limiting

A sample Istio WebAssembly plugin for rate limiting.

Istio 1.12 release introduces new Wasm Extension API. This folder contains a sample application of
implementing rate limiting in Golang, and deploy the Wasm Plugin using Istio API. The plugin will
enforce rate limiting for 2 request per second. Extra request beyond the limit will be rejected.

For detailed instructions, checkout https://www.tetrate.io/blog/istio-wasm-extensions-and-ecosystem/.
