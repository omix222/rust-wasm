# Rust、wasmを試すサンプルプロジェクト

## Rustとしてビルドと実行
- $ rustc src/lib.rs # ./lib というバイナリにCompile
- $ ./lib # 実行

## wasmとしてビルド
- cargo build --target wasm32-unknown-unknown

## 参考
- https://ryonkmr.com/15488406480
