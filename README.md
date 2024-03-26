sudo apt install wabt  
wat2wasm mul.wat -o mul.wasm  
base64 mul.wasm > wasmBase64  
