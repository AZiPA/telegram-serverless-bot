# ⚡ Telegram Serverless Bots

A collection and showcase of open-source Telegram bots built specifically for [Telegram Serverless](https://core.telegram.org/bots/serverless) (@tgcloud/bot).

---

## 📦 Projects

| Project | Description | Stack | Status |
| :--- | :--- | :--- | :--- |
| [Telegram-Uploader-Bot](https://github.com/AZiPA/telegram-uploader-bot) | Serverless file storage and sharing bot with protected deep links, PIN codes, and multi force-join channels. | @tgcloud/bot + Drizzle ORM | 🟢 Active |
| [Telegram-Serverless-Bot-Template](https://github.com/AZiPA//Telegram-Serverless-Bot-Template) | A Template for creating bot on Telegram Serverless. | @tgcloud/bot + Drizzle ORM | 🟡 In Development |
| *Upcoming Project* |  | @tgcloud/bot | 🟡 In Development |

---

## 💡 Architecture & Philosophy

All bots in this collection are engineered under zero-serverless principles:
- Zero Cost & VPS: 100% execution in native V8 isolates.
- Zero Runtime Dependencies: Powered strictly by native serverless SDK bindings.
- Dynamic Configuration: Zero process.env dependencies; fully dynamic database settings.
