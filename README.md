# ⚡ Telegram Serverless Bots

A collection and showcase of open-source Telegram bots built specifically for Telegram Serverless (@tgcloud/bot).

---

## 📦 Projects

| Project | Description | Stack | Status |
| :--- | :--- | :--- | :--- |
| [telegram-uploader-bot](https://github.com/AZiPA/telegram-uploader-bot) | Serverless file storage and sharing bot with protected deep links, PIN codes, and multi force-join channels. | @tgcloud/bot + Drizzle ORM | 🟢 Active |
| *Upcoming Project* | Planned serverless utility bot. | @tgcloud/bot | 🟡 In Development |

---

## 💡 Architecture & Philosophy

All bots in this collection are engineered under zero-serverless principles:
- Zero Cost & VPS: 100% execution in native V8 isolates.
- Zero Runtime Dependencies: Powered strictly by native serverless SDK bindings.
- Dynamic Configuration: Zero process.env dependencies; fully dynamic database settings.
