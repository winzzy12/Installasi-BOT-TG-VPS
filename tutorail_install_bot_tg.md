# ☕ Cara Installasi Script Telegram VPS BOT

* Jika sudah mendapatkan repository nya boleh siapkan 🗒
  * Siapkan BOT telegram kamu terlebih dahulu bisa lewat (@BotFather)
  * Copy Token BOT yang sudah kamu buat
  * Copy ID telegram kamu untuk izinkan akses, bisa lewat (@userinfobot)
  * Lanjut ke installasi yang sudah dibuat sesimple mungkin 👍

 * Jika sudah mendapatkan repository nya bisa lanjut ke step berikutnya

 * Masuk ke Directory
```bash
cd TELEGRAM_VPS_BOT
```
 * Jalankan perintah berikut ini untuk installasi BOT
```bash
chmod +x install_bot.sh
./install_bot.sh
```
 * Tunggu proses nya dan masukan BOT Token & Telegram user ID sebagai Admin
 * Jika sudah selesai BOT akan berjalan Otomatis

 * Cek Status
```bash
sudo systemctl status telegrambot
```
 * Cek Log
 ```bash
journalctl -u telegrambot -f
```
* Stop & Restart Bot
```bash
sudo systemctl stop telegrambot
```
```bash
sudo systemctl restart telegrambot
```
# Semoga BOT ini bisa membantu memudahkan pekerjaan kamu ☺️
Winzzy
