# 🦀 Rust Cross Build Cheatsheet
---
```bash
# 📌 Cek arsitektur
uname -m
# contoh output: aarch64 (Raspberry Pi / Termux Android)

# 📦 Install cross (kalau belum)
cargo install cross

# ➕ Tambah target x86_64
rustup target add x86_64-unknown-linux-gnu

# 🏗️ Cross build ke x86_64 Linux
cross build --target x86_64-unknown-linux-gnu --release

# 📂 Hasil ada di:
# target/x86_64-unknown-linux-gnu/release/
