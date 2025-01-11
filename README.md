# Open Ledger BOT
Open Ledger BOT

Register Here : [Open Ledger Dashboard](https://testnet.openledger.xyz/?referral_code=vmgheiodeq)
Download Extension : [Open Ledger Extension](https://chromewebstore.google.com/detail/openledger-node/ekbbplmjjgoobhdlffmgeokalelnmjjc)

## Fitur

  - Auto Get Account Information
  - Auto Run With Auto Proxy if u Choose 1 [Use [Monosans Proxy](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/all.txt)]
  - Auto Run With Manual Proxy if u Choose 2 [Paste Ur personal proxy in manual_proxy.txt]
  - Auto Claim Daily Check-In
  - Auto Send Heartbeat Every 30 Seconds
  - Multi Accounts With Threads

## Prasyarat

Pastikan Anda telah menginstal Python3.9 dan PIP.

## Instalasi

1. **Kloning repositori:**
   ```bash
   git clone https://github.com/vonssy/OpenLedger-BOT.git
   ```
   ```bash
   cd OpenLedger-BOT
   ```

2. **Instal Requirements:**
   ```bash
   pip install -r requirements.txt #or pip3 install -r requirements.txt
   ```

## Konfigurasi

- **accounts.txt:** Anda akan menemukan file `accounts.txt` di dalam direktori proyek. Pastikan `accounts.txt` berisi data yang sesuai dengan format yang diharapkan oleh skrip. Berikut adalah contoh format file:

  ```bash
  your_address_1
  your_address_2
  ```
- **manual_proxy.txt:** Anda akan menemukan file `manual_proxy.txt` di dalam direktori proyek. Pastikan `manual_proxy.txt` berisi data yang sesuai dengan format yang diharapkan oleh skrip. Berikut adalah contoh format file:
  ```bash
    ip:port # Default Protcol HTTP.
    protocol://ip:port
    protocol://user:pass@ip:port
  ```

## Jalankan

```bash
python bot.py #or python3 bot.py
```

## Penutup

Terima kasih telah mengunjungi repository ini, jangan lupa untuk memberikan kontribusi berupa follow dan stars.
Jika Anda memiliki pertanyaan, menemukan masalah, atau memiliki saran untuk perbaikan, jangan ragu untuk menghubungi saya atau membuka *issue* di repositori GitHub ini.

**vonssy**