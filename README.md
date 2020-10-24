## yew-wasm-demo

## preinstall

```bash
# install nightly cargo
cargo install nightly
# install wasm-pack
curl https://rustwasm.github.io/wasm-pack/installer/init.sh -sSf | sh
```

## usage

```bash
# step 1
rustup run nightly wasm-pack build
# step 2
cd www
npm install
npm run start
```

## refs

- [build-simple-app-with-yew](https://yew.rs/docs/en/getting-started/build-a-sample-app)
- [start-with-wasm-game-of-life](https://rustwasm.github.io/book/game-of-life/hello-world.html)
- [use-setinterval](https://rustwasm.github.io/wasm-bindgen/api/wasm_bindgen/closure/struct.Closure.html)