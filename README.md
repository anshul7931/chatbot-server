1. Under developers.facebook.com create a new app and select messenger->settings and select the facebook page you want to link your bot with and it will give you page access token.

Page Access Token: EAADvw2PvRt0BAHalfhB1lt7oeNDOasOv4uyE6TogZBsDksGwJzMF0xWfILzA2EZBm7UJelg0jFRGBcZC2Gw7TmfBrl1IZAwZCZBnKGygkyfaP1TckS0JLt8hLrDMZCTxlgHooebdiHydHVhxoXalw8azMGGyPsBOzvjUQqabJBgBwZDZD

2. Now we need to set the webhook, if the app is hosted on heroku then the callback url will be appurl suffixed with /webhook 

Webhook callback url: https://parrotbotserver.herokuapp.com/webhook
verify token: Aha_Moment_Labs as mentioned in index.js

