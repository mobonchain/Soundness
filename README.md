 <h1 align="center">Hi 👋, I'm Mob</h1>
<h3 align="center">Join the Cryptocurrency Market, make money from Airdrop - Retroactive with me</h3>

- <p align="left"> <img src="https://komarev.com/ghpvc/?username=mobonchain&label=Profile%20views&color=0e75b6&style=flat" alt="mobonchain" /> <a href="https://github.com/mobonchain"> <img src="https://img.shields.io/github/followers/mobonchain?label=Follow&style=social" alt="Follow" /> </a> </p>

- [![TopAME | Bullish - Cheerful](https://img.shields.io/badge/TopAME%20|%20Bullish-Cheerful-blue?logo=telegram&style=flat)](https://t.me/xTopAME)

# Hướng Dẫn Cài Đặt Testnet Soundness

Làm theo các bước dưới đây để tham gia **Testnet Soundness** và bắt đầu tham gia:

## 🚀 Các Bước Đăng Ký

1. **Đăng Ký Trên Soundness**
   - Truy cập **[Đăng Ký Soundness](https://soundness.xyz)** và submit mail.

2. **Tạo Khóa Của Bạn**
   - Tải về và làm theo hướng dẫn từ **[Soundness CLI GitHub](https://github.com/SoundnessLabs/soundness-layer/tree/main/soundness-cli)** để tạo khóa của bạn
   - Lưu **Phrase** và **Pubkey** của bạn để tham khảo sau này
     
* Có thể cài đặt trực tiếp bằng **Codespaces** của **GitHub**

3. **Tham Gia Discord**
   - Tham gia Discord của Soundness: **[Soundness Discord](https://discord.gg/HC3aDHrA93)**

4. **Nhập Khóa Công Khai**
   - Truy cập kênh **`#testnet-access`** và gửi `!access <Pubkey>` là hoàn tất.

---

## 🛠️ Hướng Dẫn Cài Đặt

### Bước 1: Cài Đặt Các Phụ Thuộc

Chạy các lệnh dưới đây để cài đặt các phụ thuộc cần thiết:

```bash
sudo apt update && sudo apt install -y pkg-config libssl-dev
```

### Bước 2: Cài Đặt Rust

Cài đặt Rust bằng các lệnh sau:

```bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
source $HOME/.cargo/env
rustc --version
cargo --version
```

### Bước 3: Cập Nhật Hồ Sơ Bash

Để đảm bảo Rust được tải mỗi khi bạn bắt đầu phiên làm việc mới, chạy lệnh sau:

```bash
echo 'source $HOME/.cargo/env' >> ~/.bashrc
source ~/.bashrc
```

### Bước 4: Cài Đặt Soundness

Cài đặt Soundness bằng cách chạy các lệnh sau:

```bash
curl -sSL https://raw.githubusercontent.com/soundnesslabs/soundness-layer/main/soundnessup/install | bash
source ~/.bashrc
soundnessup
```

### Bước 5: Cài Đặt & Cập Nhật Soundness

Chạy các lệnh dưới đây để cài đặt và cập nhật công cụ Soundness:

```bash
soundnessup install
soundnessup update
```

### Bước 6: Tạo Phrase & Pubkey

```bash
soundness-cli generate-key --name my-key
```

---

## Nếu gặp phải bất kỳ vấn đề nào có thể hỏi thêm tại **[TopAME | Chat - Supports](https://t.me/yTopAME)**
