# telegrambot


### What Is this ?
 ```
   A Telegram Bot Written In Python 

 ```
 ### what can it do ?

 ```  
 It Can Upload Your Direct and Supported links into Google Drive.

 ```
### Install Module 
```
  sudo pip3 install -r requirements.txt
```
### Run This bot
```
python3 bot.py
```
 ### How Can We use It 
  - First authorise Bot Using `/auth` command Generate a Key and send it To bot .
  - Now You can Send Supported Link To Bot.

### Avalible Commands
  - `/start` =  Start Message
  - `/auth` = Authorise You
  - `/revoke` = Delete Your Saved credential
  - `/help` =  help Text

## Supported Links : 
 - Direct Link
 - Mega.nz Link
 - openload link (disabled)
 - Dropbox Link

## Requirements
  - [Google Drive api Credential](https://console.cloud.google.com/apis/credentials) (Others type)  `Required`
  - Telegram Bot Token (Using BotFather)  `Required`
  - Openload ftp login and Key  `optional`
  - Mega Email and Password  `Optional`

 ` If You  wanna Change Openload Api and Mega Email Password You Can Change it From Given Path`
   - Mega => Plugins > TEXT.py
   - Openload  => Plugins > dlopenload.py

## Setup Your Own Bot
```
1. Create Your  [Google Drive api Credential](https://console.cloud.google.com/apis/credentials) (other type) and Download  Its json

2. Paste it In Bot Root Directroy  and Rename it "client_secrets.json"

3. Replace Your Bot Token in  [creds.py file](./creds.py)

4. Your Bot is Ready to Host. 
```
### You Can Use Heroku To host It.

 `Make sure You have Changed Your Bot Token and google client api Before Hosting It`


 
# TODO
  - file name need to original file name.
  - rename filename.
  - show download progress with download speed.
  - add support for mega and other file host which are some limitation.
  - add support for searc file
  - add support for copy folder in drive
