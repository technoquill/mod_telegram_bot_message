# Telegram bot message for Joomla 4.2.0 +

**Joomla! 4/5 Module** for quick integration with **Telegram Bot API**.  
This module allows you to send messages to a selected Telegram chat directly from your Joomla site. Perfect for notifications, feedback, or integration with other services.

---

## Features
- Send messages via **Telegram Bot API**.
- Easy configuration: **Bot Token** & **Chat ID**.
- Supports Joomla! **4.x – 5.x**.
- Lightweight, no external dependencies.
- Can be used as a frontend widget (module position) or for system notifications.

---

## Installation
1. Download the latest release from [Releases](https://github.com/technoquill/mod_telegram_bot_message/releases/tag/v1.0.0).
2. In Joomla Admin → **Extensions → Manage → Install**, upload the ZIP file.
3. Enable the module in the desired position.

---

## Configuration
In the module parameters:
- **Bot Token** – your bot’s unique token (generated via [@BotFather](https://t.me/BotFather)).
- **Chat ID** – ID of the user or group to receive messages.
- **Message Template** – the text of the message (you can include dynamic data).

---

## Usage
Once activated, the module automatically sends messages to Telegram whenever it is triggered according to your setup.  
Possible use cases:
- Notify the site admin about new requests.
- Integrate with contact forms.
- Send automated site messages.

---

## Technical Requirements
- PHP 7.4+
- Joomla 4.2 / 5.x
- Uses **cURL** for HTTP requests to Telegram API

---

## License
Released under the [GPL v3 License](LICENSE).
