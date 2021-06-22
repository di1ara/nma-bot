# nma-bot
The Neuromatch Academy Discord Bot.

## Dependencies

* os
* email
* base64
* pandas
* google
* discord
* logging
* gspread
* oauth2client
* googleapiclient
* google_auth_oauthlib


## Commands

To issue a command, begin a discord message with `--nma ` followed by one of the following commands:

Command | Function | Display
------------ | ------------- | -------------
`auth` | Checks whether user is authorized to use admin commands. | Context Channel.
`debug` | Prints out debugging information. | Console
`init` | Creates new channels for registered pods. | #bot-log
`testmail` | Tests email functionality. | #bot-log
`quit` | Shuts down the bot. | Context Channel.

## Feature List

- [x] Server initialization. (`--nma init`)
- [x] Debug functionality. (`--nma debug`)
- [x] Student verification.
- [ ] Dynamic multi-guild support.
- [ ] Smart initialization.
- [x] Add email notifications to user verification.
