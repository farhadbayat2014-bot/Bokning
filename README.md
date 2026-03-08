npm startnpm start# SMS Bokningsapp - Webbversion

En fullt funktionell webbapp för SMS-bokning av kollegor.

## 🚀 Snabbstart (5 min)

```bash
# 1. Installera dependencies
npm install

# 2. Uppdatera .env med dina API-nycklar
# (Se WEBAPP_GUIDE.md för instruktioner)

# 3. Starta appen
npm start
```

Öppna: **http://localhost:3000**

---

## 📁 Filer

| Fil | Beskrivning |
|-----|-------------|
| `server.js` | Express backend server |
| `public/index.html` | Frontend webbsida |
| `package.json` | Node dependencies |
| `.env` | API-nycklar (ej commit!) |
| `WEBAPP_GUIDE.md` | Fullständig setup-guide |

---

## ✨ Features

- 🎨 Modern, responsiv design
- 📱 Fungerar på mobil & desktop
- 💬 Skicka SMS via Twilio
- 📊 Spara bokningar i Google Sheets
- 📈 Se bokningshistorik

---

## ⚙️ Konfiguration

Redigera `.env`:

```env
TWILIO_ACCOUNT_SID=din_sid
TWILIO_AUTH_TOKEN=din_token
TWILIO_PHONE=+46700383788
GOOGLE_SHEET_ID=ditt_sheet_id
GOOGLE_CREDS_FILE=credentials.json
PORT=3000
```

---

## 🔗 Endpoints

- `GET /api/bookings` - Hämta alla bokningar
- `POST /api/book` - Skapa ny bokning
- `GET /api/health` - Health check

---

## 📖 Full Guid

Se [WEBAPP_GUIDE.md](WEBAPP_GUIDE.md) för:
- Detaljerad installation
- Google Sheets setup
- Twilio configuration
- Troubleshooting
- API documentation

---

**Lycka till! 🎉**
