# 🇰🇭 Kairozen SMM Bot

Telegram Bot សម្រាប់ SMM Panel — Views · Likes · Followers
បង់លុយតាម **KHQR (CamRapidPay)**

---

## ⚙️ ដំឡើង (Setup)

### 1. Clone repo
```bash
git clone https://github.com/your-username/kairozen-smm-bot.git
cd kairozen-smm-bot
```

### 2. Install dependencies
```bash
pip install pyTelegramBotAPI requests flask qrcode pillow --break-system-packages
```

### 3. បង្កើត .env file
```bash
cp .env.example .env
```
រួចកែ `.env` ដាក់ values របស់អ្នក:
```
BOT_TOKEN=your_telegram_bot_token
ADMIN_ID=your_telegram_id
CAMRAPID_API_KEY=your_camrapidpay_key
CONTROL_KEY=your_random_secret
```

### 4. Run bot
```bash
python kairozen_smm_bot_v2.py
```

---

## 🔑 Environment Variables

| Variable | ពិពណ៌នា |
|---|---|
| `BOT_TOKEN` | Telegram Bot Token (BotFather) |
| `ADMIN_ID` | Telegram User ID របស់ Admin |
| `CAMRAPID_API_KEY` | CamRapidPay API Key |
| `WEBHOOK_URL` | Webhook URL (optional) |
| `CONTROL_KEY` | Secret key សម្រាប់ Flask API |

---

## 📦 Features

- ✅ SMM Panel — TikTok · Facebook · Instagram · YouTube
- ✅ បង់លុយតាម KHQR (ABA · Bakong · Wing · ACLEDA)
- ✅ Auto-detect payment
- ✅ Admin Panel — បន្ថែម/កាត់ Balance, Broadcast
- ✅ Promo Code system
- ✅ ភាសាខ្មែរ + English

---

## ⚠️ សំគាល់

កុំ push `.env` ឬ `*.json` files ទៅ Github ព្រោះមាន data ឯកជន។
