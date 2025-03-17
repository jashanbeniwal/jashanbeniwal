# Jass_beniwal Save Restricted Bot

*A Telegram Bot, Which can send you restricted content by it's post link with <b>login feature</b>*
- 👋 Hi, I’m @jashanbeniwal

---

## Variables

- `API_HASH` : Your API Hash From [Telegram Website](https://my.telegram.org)
- `API_ID` : Your API ID From [Telegram Website](https://my.telegram.org)
- `BOT_TOKEN` : Your Bot Token From [BotFather](https://telegram.me/BotFather)
- `ADMINS` : Your Admin Id For Broadcasting Message
- `DB_URI` : Your Mongodb Database Url From [Mongodb](https://mongodb.com) Watch [Video Tutorial](https://youtu.be/DAHRmFdw99o) ( Warning - Give Db uri in deploy server environment variable, don't give in repo )
- `ERROR_MESSAGE` : Set True Or False, If You Want Error Message Then True Else False.

---

## Commands

- `/start` : Check Bot Is Working Or Not
- `/help` : Check How To Use Bot
- `/login` : Login Your Telegram String Session 
- `/logout` : Logout Your Session 
- `/cancel` : Cancel Your Any Ongoing Task
- `/broadcast` : Broadcast Message To User (Admin Only)

---

## Usage

__FOR PUBLIC CHATS__

_just send post/s link_


__FOR PRIVATE CHATS__

_first send invite link of the chat (unnecessary if the account of string session already member of the chat)
then send post/s link_


__FOR BOT CHATS__

_send link with '/b/', bot's username and message id, you might want to install some unofficial client to get the id like below_

```
https://t.me/b/botusername/4321
```

__MULTI POSTS__

_send public/private posts link as explained above with formate "from - to" to send multiple messages like below_


```
https://t.me/xxxx/1001-1010

https://t.me/c/xxxx/101 - 120
```

_note that space in between doesn't matter_

---

## Credits

- <b>Thanks To @Jass_beniwal
<!---
jashanbeniwal/jashanbeniwal is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
