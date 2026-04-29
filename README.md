<p align="center">
  <img src="https://img.shields.io/badge/LonelyHub-v2.0.0-blueviolet?style=for-the-badge&logo=discord&logoColor=white" alt="Version"/>
  <img src="https://img.shields.io/badge/Python-%3E%3D3.13-339933?style=for-the-badge&logo=python&logoColor=white" alt="Node"/>
  <img src="https://img.shields.io/badge/License-Proprietary-red?style=for-the-badge" alt="License"/>
</p>

<h1 align="center">🔮 Lonely Hub — Discord Quest Auto Claim</h1>

<p align="center">
  <b>Công cụ tự động hoàn thành và nhận thưởng Quest trên Discord</b><br/>
  <i>Auto-complete & auto-claim Discord Quests — fast, silent, and effortless.</i>
</p>

---

## ✨ Giới thiệu

**Lonely Hub** là một bot discord / web được viết bằng Python, giúp bạn **tự động hoàn thành** các Discord Quest và **nhận thưởng (claim)** mà không cần thao tác thủ công.

### 🎯 Tính năng chính

| Tính năng | Mô tả |
|-----------|-------|
| 🎬 **Auto Watch Video** | Tự động xem video quest với tiến trình giả lập chính xác |
| 🎮 **Auto Play on Desktop** | Giả lập heartbeat cho quest dạng chơi game trên desktop |
| 📡 **Auto Stream** | Hỗ trợ quest dạng stream trên desktop |
| 🕹️ **Auto Play Activity** | Hỗ trợ quest dạng chơi Activity |
| ⭐ **Auto Claim Rewards** | Tự động nhận thưởng ngay khi hoàn thành quest |
| 🔮 **Orbs Tracking** | Theo dõi số Orbs trước và sau khi hoàn thành |
| 📊 **Live Dashboard** | Giao diện CLI real-time hiển thị tiến trình từng quest |

---

## 📋 Yêu cầu hệ thống

- **Python** >= 3.13
- **Discord User Token** (token tài khoản người dùng)
- **Discord Bot Token** (token bot discord)
---

## 🚀 Hướng dẫn cài đặt & sử dụng

### Bước 1: Clone hoặc tải source code

```bash
git clone https://github.com/LongHip12/Discord-Auto-Quest.git
cd Discord-Auto-Quests
```

### Bước 2: Cài đặt dependencies

```bash
pip install requirements.txt
```

### Bước 3: Cấu hình Token

Tạo file `.env` trong thư mục gốc của project với nội dung:

```env
DISCORD_BOT_TOKEN=your_discord_bot_token_here
```

> ⚠️ **Lưu ý bảo mật**: Không bao giờ chia sẻ token của bạn cho bất kỳ ai. Token cho phép truy cập toàn bộ tài khoản Discord của bạn.

### Bước 4: Chạy Tool

```bash
python main.py
```

---
## ❓ Câu hỏi thường gặp (FAQ)

<details>
<summary><b>Cách lấy Discord User Token?</b></summary>

1. Mở Discord trên trình duyệt hoặc ứng dụng Desktop
2. Nhấn `Ctrl + Shift + I` để mở Developer Tools
3. Chuyển sang tab **Network**
4. Thực hiện bất kỳ hành động nào trên Discord
5. Tìm request đến `discord.com/api` và copy giá trị `Authorization` trong Headers
6. 
</details>

<details>
<summary><b>Tool có an toàn không?</b></summary>

Tool hoạt động bằng cách giả lập các request API giống như Discord Client chính thức. Tuy nhiên, việc sử dụng user token tự động có thể vi phạm Terms of Service của Discord. **Sử dụng có rủi ro bị ban tài khoản.**

</details>

<details>
<summary><b>Tại sao một số quest bị SKIP?</b></summary>

Một số quest có thể chưa được hỗ trợ hoặc đã hết hạn. Tool chỉ xử lý các quest đang hoạt động và chưa hoàn thành.

</details>

---

## 📊 Thống kê dự án

<p align="center">
  <a href="https://github.com/LongHip12/Discord-Auto-Quest/stargazers">
    <img src="https://img.shields.io/github/stars/LongHip12/Discord-Auto-Quest?style=for-the-badge&logo=github&color=f0e68c" alt="Stars"/>
  </a>
  <a href="https://github.com/LongHip12.Discord-Auto-Quests/network/members">
    <img src="https://img.shields.io/github/forks/LongHip12/Discord-Auto-Quest?style=for-the-badge&logo=github&color=87ceeb" alt="Forks"/>
  </a>
  <a href="https://github.com/LongHip12/Discord-Auto-Quest/issues">
    <img src="https://img.shields.io/github/issues/LongHip12/Discord-Auto-Quest?style=for-the-badge&logo=github&color=ffa07a" alt="Issues"/>
  </a>
  <a href="https://github.com/LongHip12/Discord-Auto-Quest/commits">
    <img src="https://img.shields.io/github/commit-activity/m/LongHip12/Discord-Auto-Quest?style=for-the-badge&logo=github&color=98fb98" alt="Commits"/>
  </a>
  <img src="https://img.shields.io/github/last-commit/LongHip12/Discord-Auto-Quest?style=for-the-badge&logo=github&color=dda0dd" alt="Last Commit"/>
  <img src="https://img.shields.io/github/watchers/LongHip12/Discord-Auto-Quest?style=for-the-badge&logo=github&color=c9b1ff" alt="Watchers"/>
</p>

## 📈 Star History

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=LongHip12/Discord-Auto-Quest&type=Date&theme=dark&t=20260311" />
    <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=LongHip12/Discord-Auto-Quest&type=Date&t=20260311" />
    <img alt="Star History Chart" src="https://api.star-history.com/svg?repos=LongHip12/Discord-Auto-Quest&type=Date&t=20260311" />
  </picture>
</p>

---

## 👨‍💻 Tác giả

<p align="center">
  <a href="https://nguyenmanhhieu.info.vn/">
    <img src="https://img.shields.io/badge/Website-lonelyhub.onrender.com-blue?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Website"/>
  </a>
</p>

| | Thông tin |
|---|---|
| 👤 **Tên** | **Nguyễn Hoàng Long** |
| 🌐 **Website** | [lonelyhub.onrender.com](https://lonelyhub.onrender.com) |
| 🛠️ **Dự án** | Lonely Hub — Discord Quest Auto Claim |

> 💬 Nếu bạn muốn sử dụng source code này cho mục đích cá nhân hoặc thương mại, vui lòng **liên hệ tác giả** để xin phép tại [nguyenmanhhieu.info.vn](https://nguyenmanhhieu.info.vn/).

---

## 📜 Bản quyền

Copyright © 2024-2026 **LongHip12**. All rights reserved.

Xem chi tiết tại file [LICENSE](./LICENSE).

---

<p align="center">
  <sub>Made with ❤️ by <a href="https://lonelyhub.onrender.com">LongHip12</a></sub>
</p>
