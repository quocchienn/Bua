# Telegram Ban Words Bot (Render Worker)

Bot Telegram tự động **xoá tin nhắn** chứa từ cấm và **cấm chat** người vi phạm trong X phút.

## Tính năng
- Xoá tin nhắn chứa từ cấm
- Restrict (mute) người vi phạm trong N phút
- Lệnh admin:
  - `/addword từ_cấm`
  - `/delword từ_cấm`
  - `/listwords`
  - `/setmute số_phút`
  - `/unmute` (reply vào user)
  - `/status`

## Triển khai trên Render
1. Fork repo này (hoặc tải mã nguồn và push lên Git).
2. Vào Render Dashboard → **Add New** → **Web Service** → chọn repo
**Build Command**:
`bash`
pip install -r requirements.txt

**Start Command**:
`bash`
python bot.py
