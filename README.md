# wasm-rust-demo
러스트 wasm 데모


## Prerequisites
#### wasm-pack
https://rustwasm.github.io/wasm-pack/installer/

### Installation
```sh
git clone https://github.com/esllo/wasm-rust-demo.git
cd wasm-rust-demo
yarn install
```
  
  

## build
### 데모 빌드
web(no-modules) 
```sh
# for wasm-rust-demo
wasm-pack build --target no-modules
```
### 기타 빌드
web(module)
```sh
wasm-pack build --target web
```
CommonJS(node)
```sh
wasm-pack build --target nodejs
```
Module (ES6)
```sh
wasm-pack build
```



## run
```sh
yarn start

# other cmd/termianl
# Windows
start http://localhost:3000
# Mac
open http://localhost:3000
```
