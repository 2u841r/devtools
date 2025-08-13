# DevTools – Tauri Version
This branch contains a Tauri-based build of DevTools.
Compared to Electron (~170+ MB), the Tauri build is only ~1.8 MB while keeping the same features.  

[Download link](https://github.com/2u841r/devtools/releases/tag/latest) 

## 🚀 Requirements
Before running, install these:

Rust (with cargo)
Install via: https://rustup.rs

Verify:
```bash
rustc --version
cargo --version
```

## 🖥 Windows extra setup
If you’re on Windows, you need to install Microsoft’s C++ build tools before running Tauri:

Download & run:
https://visualstudio.microsoft.com/visual-cpp-build-tools/

In the installer, select:
✅ Desktop development with C++
✅ Windows 10/11 SDK

Restart your terminal after install.

## Tauri CLI

```bash
cargo install tauri-cli
```

### ▶️ Run in Development Mode
```bash
npm run dev
```
This will launch the app with live reload.

### 🏗 Build Release
```bash
npm run build
```
The built application will be in the src-tauri/target/release/ folder.

### 💡 Notes for Newbies
Rust handles the backend (fast, small size)

Tauri bundles your existing frontend (React, Vue, Svelte, etc.) into a native shell

No need to know deep Rust — most work stays in your JS/TS code

For more info:
📖 https://tauri.app/


![](https://rs2.deno.dev/2u841r/devtools)
