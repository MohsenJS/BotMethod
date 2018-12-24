BotMethod _(Telegram Bot Method)_
=================

## BotMethod help you to easily use "_Telegram API v4.1_"


**A Class of all Telegram Bot Methods for PHP**

-----------------------------------

### Functions that is in _BotMethod are_ :

Method Name | Description
---- | ----
[getUpdates](https://core.telegram.org/bots/api#getUpdates) | Use this method to receive incoming updates using long polling.
[setWebhook](https://core.telegram.org/bots/api#setwebhook) | Use this method to specify a url and receive incoming updates via an outgoing webhook
[deleteWebhook](https://core.telegram.org/bots/api#deletewebhook) | Use this method to remove webhook integration if you decide to switch back to getUpdates
[getWebhookInfo](https://core.telegram.org/bots/api#getwebhookinfo) | Use this method to get current webhook status. Requires no parameters
[getme](https://core.telegram.org/bots/api#getme) | A simple method for testing your bot's auth token
[sendMessage](https://core.telegram.org/bots/api#sendmessage) | Use this method to send text messages
[forwardMessage](https://core.telegram.org/bots/api#forwardmessage) | Use this method to forward messages of any kind
[sendPhoto](https://core.telegram.org/bots/api#sendphoto) | Use this method to send photos
[sendAudio](https://core.telegram.org/bots/api#sendaudio) | Use this method to send audio files, if you want Telegram clients to display them in the music player. Your audio must be in the .mp3 format.
[sendDocument](https://core.telegram.org/bots/api#senddocument) | Use this method to send general files
[sendVideo](https://core.telegram.org/bots/api#sendvideo) | Use this method to send video files, Telegram clients support mp4 videos (other formats may be sent as Document)
[sendAnimation](https://core.telegram.org/bots/api#sendAnimation) | Use this method to send animation files (GIF or H.264/MPEG-4 AVC video without sound)
[sendVoice](https://core.telegram.org/bots/api#sendvoice) | Use this method to send audio files, if you want Telegram clients to display the file as a playable voice message. For this to work, your audio must be in an .ogg file encoded with OPUS (other formats may be sent as Audio or Document)
[sendVideoNote](https://core.telegram.org/bots/api#sendvideonote) | As of v.4.0, Telegram clients support rounded square mp4 videos of up to 1 minute long. Use this method to send video messages
[sendMediaGroup](https://core.telegram.org/bots/api#sendmediagroup) | Use this method to send a group of photos or videos as an album
[sendLocation](https://core.telegram.org/bots/api#sendlocation) | Use this method to send point on the map
[editMessageLiveLocation](https://core.telegram.org/bots/api#editmessagelivelocation) | Use this method to edit live location messages sent by the bot or via the bot (for inline bots). A location can be edited until its live_period expires or editing is explicitly disabled by a call to stopMessageLiveLocation
[stopMessageLiveLocation](https://core.telegram.org/bots/api#stopmessagelivelocation) | Use this method to stop updating a live location message sent by the bot or via the bot (for inline bots) before live_period expires.
[sendVenue](https://core.telegram.org/bots/api#sendvenue) | Use this method to send information about a venue
[sendContact](https://core.telegram.org/bots/api#sendcontact) | Use this method to send phone contacts
[sendChatAction](https://core.telegram.org/bots/api#sendchataction) | Use this method when you need to tell the user that something is happening on the bot's side.
[getUserProfilePhotos](https://core.telegram.org/bots/api#getuserprofilephotos) | Use this method to get a list of profile pictures for a user
[getFile](https://core.telegram.org/bots/api#getfile) | Use this method to get basic info about a file and prepare it for downloading. For the moment, bots can download files of up to 20MB in size
getFileLink | Use this method to get File link
[kickChatMember](https://core.telegram.org/bots/api#kickchatmember) | Use this method to kick a user from a group, a supergroup or a channel. In the case of supergroups and channels, the user will not be able to return to the group on their own using invite links, etc., unless unbanned first
[unbanChatMember](https://core.telegram.org/bots/api#unbanchatmember) | Use this method to unban a previously kicked user in a supergroup or channel. The user will not return to the group or channel automatically, but will be able to join via link, etc
[restrictChatMember](https://core.telegram.org/bots/api#restrictchatmember) | Use this method to restrict a user in a supergroup. The bot must be an administrator in the supergroup for this to work and must have the appropriate admin rights
[promoteChatMember](https://core.telegram.org/bots/api#promotechatmember) | Use this method to promote or demote a user in a supergroup or a channel. The bot must be an administrator in the chat for this to work and must have the appropriate admin rights
[exportChatInviteLink](https://core.telegram.org/bots/api#exportchatinvitelink) | Use this method to export an invite link to a supergroup or a channel. The bot must be an administrator in the chat for this to work and must have the appropriate admin rights
[setChatPhoto](https://core.telegram.org/bots/api#setchatphoto) | Use this method to set a new profile photo for the chat. Photos can't be changed for private chats. The bot must be an administrator in the chat for this to work and must have the appropriate admin rights
[deleteChatPhoto](https://core.telegram.org/bots/api#deletechatphoto) | Use this method to delete a chat photo. Photos can't be changed for private chats. The bot must be an administrator in the chat for this to work and must have the appropriate admin rights
[setChatTitle](https://core.telegram.org/bots/api#setchattitle) | Use this method to change the title of a chat. Titles can't be changed for private chats. The bot must be an administrator in the chat for this to work and must have the appropriate admin rights
[setChatDescription](https://core.telegram.org/bots/api#setchatdescription) | Use this method to change the description of a supergroup or a channel. The bot must be an administrator in the chat for this to work and must have the appropriate admin rights
[pinChatMessage](https://core.telegram.org/bots/api#pinchatmessage) | Use this method to pin a message in a supergroup or a channel. The bot must be an administrator in the chat for this to work and must have the ‘can_pin_messages’ admin right in the supergroup or ‘can_edit_messages’ admin right in the channel
[unpinChatMessage](https://core.telegram.org/bots/api#unpinchatmessage) | Use this method to unpin a message in a supergroup or a channel. The bot must be an administrator in the chat for this to work and must have the ‘can_pin_messages’ admin right in the supergroup or ‘can_edit_messages’ admin right in the channel
[leaveChat](https://core.telegram.org/bots/api#leavechat) | Use this method for your bot to leave a group, supergroup or channel
[getChat](https://core.telegram.org/bots/api#getchat) | Use this method to get up to date information about the chat (current name of the user for one-on-one conversations, current username of a user, group or channel, etc.)
[getChatAdministrators](https://core.telegram.org/bots/api#getchatadministrators) | Use this method to get a list of administrators in a chat
[getChatMembersCount](https://core.telegram.org/bots/api#getchatmemberscount) | Use this method to get the number of members in a chat
[getChatMember](https://core.telegram.org/bots/api#getchatmember) | Use this method to get information about a member of a chat
[setChatStickerSet](https://core.telegram.org/bots/api#setchatstickerset) | Use this method to set a new group sticker set for a supergroup. The bot must be an administrator in the chat for this to work and must have the appropriate admin rights
[deleteChatStickerSet](https://core.telegram.org/bots/api#deletechatstickerset) | Use this method to delete a group sticker set from a supergroup. The bot must be an administrator in the chat for this to work and must have the appropriate admin rights
[answerCallbackQuery](https://core.telegram.org/bots/api#answercallbackquery) | Use this method to send answers to callback queries sent from inline keyboards
[answerInlineQuery](https://core.telegram.org/bots/api#answerinlinequery) | Use this method to send answers to an inline query
[editMessageText](https://core.telegram.org/bots/api#editmessagetext) | Use this method to edit text and game messages sent by the bot or via the bot (for inline bots)
[editMessageCaption](https://core.telegram.org/bots/api#editmessagecaption) | Use this method to edit captions of messages sent by the bot or via the bot (for inline bots)
[editMessageMedia](https://core.telegram.org/bots/api#editMessageMedia) | Use this method to edit audio, document, photo, or video messages
[editMessageReplyMarkup](https://core.telegram.org/bots/api#editmessagereplymarkup) | Use this method to edit only the reply markup of messages sent by the bot or via the bot (for inline bots)
[deleteMessage](https://core.telegram.org/bots/api#deletemessage) | Use this method to delete a message
[sendSticker](https://core.telegram.org/bots/api#sendsticker) | Use this method to send .webp stickers
[getStickerSet](https://core.telegram.org/bots/api#getstickerset) | Use this method to get a sticker set
[uploadStickerFile](https://core.telegram.org/bots/api#uploadstickerfile) | Use this method to upload a .png file with a sticker for later use in createNewStickerSet and addStickerToSet methods (can be used multiple times)
[createNewStickerSet](https://core.telegram.org/bots/api#createnewstickerset) | Use this method to create new sticker set owned by a user. The bot will be able to edit the created sticker set
[addStickerToSet](https://core.telegram.org/bots/api#addstickertoset) | Use this method to add a new sticker to a set created by the bot
[setStickerPositionInSet](https://core.telegram.org/bots/api#setstickerpositioninset) | Use this method to move a sticker in a set created by the bot to a specific position
[deleteStickerFromSet](https://core.telegram.org/bots/api#deletestickerfromset) | Use this method to delete a sticker from a set created by the bot
[sendInvoice](https://core.telegram.org/bots/api#sendInvoice) | Use this method to send invoices
[answerShippingQuery](https://core.telegram.org/bots/api#answerShippingQuery) | Use this method to reply to shipping queries
[answerPreCheckoutQuery](https://core.telegram.org/bots/api#answerPreCheckoutQuery) | Use this method to respond to such pre-checkout queries
[setPassportDataErrors](https://core.telegram.org/bots/api#setPassportDataErrors) | Informs a user that some of the Telegram Passport elements they provided contains errors
[sendGame](https://core.telegram.org/bots/api#sendGame) | Use this method to send a game
[setGameScore](https://core.telegram.org/bots/api#setGameScore) | Use this method to set the score of the specified user in a game
[getGameHighScores](https://core.telegram.org/bots/api#getGameHighScores) | Use this method to get data for high score tables


----------------------------------------


### How to use a BotMethod class?

First you need to include class file and initialize the class:
```php
<?php
require_once 'BotMethod.php'; //include class file
$tg = new BotMethod("**YOUR_TOKEN**"); //initialize the class

```



For testing, we send a message and photo
```php
<?php
require_once 'BotMethod.php'; //include class file
$tg = new BotMethod("**YOUR_TOKEN**"); //initialize the class
$tg->sendMessage(123456789, 'Hello World!'); //send message
$tg->sendPhoto(123456789, 'https://www.w3schools.com/html/img_girl.jpg', ':)'); //send photo with caption

```
