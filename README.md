
# 🎬 Video Dubber AI - Lồng Tiếng & Phụ Đề Việt Tự Động

**Ứng dụng web tự động dịch và lồng tiếng video sang tiếng Việt** sử dụng AI. Hỗ trợ tải video từ máy tính hoặc link YouTube, Drive, v.v.

![Demo](https://img.shields.io/badge/Status-Developing-orange)
![Python](https://img.shields.io/badge/Python-3.10%2B-blue)
![FastAPI](https://img.shields.io/badge/FastAPI-0.115-green)

## ✨ Tính năng nổi bật

- **Nhận diện giọng nói** đa ngôn ngữ chính xác nhờ **OpenAI Whisper**
- **Dịch tự động** sang tiếng Việt (Google Translate)
- **Lồng tiếng AI** giọng Việt Nam tự nhiên (Microsoft Edge TTS)
- **Đồng bộ thời gian** chính xác giữa giọng lồng và video
- **Phụ đề SRT** + **chèn phụ đề cứng** vào video
- **Hỗ trợ URL** từ YouTube, Google Drive và hơn 1000 nền tảng khác
- **Giao diện tối ưu di động** (PWA-ready)
- **Xử lý nền** (Background task) – không cần giữ tab
- **Giới hạn an toàn**: tối đa 2GB và 60 phút/video

## 🛠 Công nghệ sử dụng

### Backend
- **FastAPI** + Uvicorn
- **Whisper** (OpenAI)
- **Edge-TTS** (Microsoft)
- **FFmpeg** (xử lý video/âm thanh)
- **yt-dlp** (tải video từ URL)
- Python 3.10+

### Frontend
- HTML5 + Tailwind CSS
- Vanilla JavaScript
- Hỗ trợ kéo thả, tải file theo chunk, đồng bộ media

## 📁 Cấu trúc thư mục
