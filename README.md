# ekza-bevy
NFText visualization prototype

![image](https://user-images.githubusercontent.com/10486621/157743314-b81a2d4a-5aac-49c8-93f2-48a70a0d3a32.png)

## run the demo
- `% cargo build`
- `% cargo run`

## build app
- `cargo build release`

### wasm

```
cargo build --release --target wasm32-unknown-unknown
wasm-bindgen --out-name wasm_example --out-dir target/ --target web target/wasm32-unknown-unknown/release/ekza-bevy-engine.wasm
```
then run server and access app via index.html

build one file and other options:
```
https://github.com/bevyengine/bevy/discussions/4176
```
## run on android:
- `% cargo apk run`

more info about building app [here](https://github.com/bevyengine/bevy/tree/latest/examples#games)

### requirements
android-sdk:
`sudo apt update && sudo apt install android-sdk`
