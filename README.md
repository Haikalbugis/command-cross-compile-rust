# 🦀 Rust Cross Build Cheatsheet
---

# 📌 Cek arsitektur
```bash
uname -m
```

## 📦 Install cross (kalau belum)
```bash
cargo install cross
```

# ➕ Tambah target x86_64
```bash
rustup target add x86_64-unknown-linux-gnu  
```

# 🏗️ Cross build ke x86_64 Linux aarch64 (Raspberry Pi / Termux Android)
```bash
cross build --target x86_64-unknown-linux-gnu --release
```
