# Amharic Telegram Bot

**Type Amharic easily using your regular English keyboard — directly in Telegram inline mode.**

> [!NOTE]
> This bot allows anyone to write in **Amharic (አማርኛ)** without needing an Amharic keyboard layout. Just start typing in English (like "selam" or "tenastalign"), and the bot instantly suggests or converts it to proper Amharic script — usable inline in any private chat, group, or channel.

### Main Features
- **Inline mode support** — works anywhere in Telegram (type `@amharictlbot`)
- Transliteration from **Latin/English characters → Ge'ez (Amharic) script**
- Fast, real-time suggestions as you type
- Simple and lightweight — perfect for quick messaging in Amharic
- No need to switch keyboard layouts or install extra apps

### How to Use
1. Open any chat in Telegram
2. Type `@amharictlbot` (or the bot's current username) followed by your text in English letters  
   Example: `@amharictlbot selam hawote`
3. Select the suggested Amharic version from the inline results
4. Send — done! ሰላም ሃውቶቴ!

### Background
Originally created to help people write Amharic fluently on devices without native Amharic input support.  
Still useful in 2026 for quick, hassle-free Amharic typing in Telegram.

### Technical Details
- Language: JavaScript / Node.js
- Telegram Bot API
- Custom transliteration mapping (see `am.js` / `sleeboard.js`)

### Upcoming Features & To-Do
Some core pieces are already in place from the original implementation (last updated ~2017). Here's the current status + ideas moving forward — contributions very welcome!

- [x] Basic English-to-Amharic transliteration using Latin keyboard input (core logic in `am.js` / `sleeboard.js`)
- [x] Telegram Bot API integration (main bot setup in `index.js`)
- [x] Support for common Amharic phrases and fidels (e.g., "selam" → ሰላም)
- [ ] Update to latest Telegram Bot API version (fix any deprecated methods or webhook/polling issues)
- [ ] Improve handling of ambiguous inputs (e.g., better disambiguation for "s" → ሰ / ሠ / ጸ etc.)
- [ ] Refresh or redeploy the bot instance if the old one (@AmharicBot) is down or unresponsive
- [ ] Add more example phrases and clearer instructions in README / How to Use
- [ ] (Idea) Web-based demo/transliterator (standalone page to test transliteration without Telegram)

**Stars, forks, and pull requests are welcome.**  

Help keep Amharic typing easy and accessible on Telegram

Bot link: [Amharic Bot](https://t.me/amharictlbot) (check if still active)
