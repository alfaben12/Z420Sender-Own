# Z420Sender
## Z420 Sender Bulk Email Spammed

## Requirements

- An API Key
    - Add from: https://www.facebook.com/riqlfa
- PHP 5.6 up
- PHP Server (XAMPP) / IIS
- Text Editor
- Command Line Interface (CLI)

## Feature
- Random Number
- Random String
- Random Sender Name
- Random Sender Mail
- Random Subject 
- Random Browser
- Random Country
- Random IP 
- Get Date
- Get Email 
- Add Attachment
- Remove Duplicate Email (Y/n)
- Remove Email After Send (Y/n)
- Multi Link (get random)
- Multi SMTP (only google relay)
- Sensor Email Received
- Ratio send email / a sec
- etc

## Usage

### Input Parameter Descriptions
# In your Gemfile
| Apikey       | Hostname    | Username | Password | Secure | Port |
| --------------- | ------- | -------- |--------|--------|--------|
|Z4209350-6fa-4200-91bb-xxxxxxxxxxxx|smtp-relay.gmail.com|admin@z420.com|xxxxxxxx|tls or ssl|587 (TLS) or 465 (SSL)|

### Running on CLI Mode
```ruby
php Z420.php
```  

## Update step by step on date
| Attribute       | Type    | Description |
| --------------- | ------- | -------- |
|`is_listed`|boolean|Is this IP on a blocklist|
|`list_count`|integer|The number of blocklists the IP is listed on|
|`last_seen`|integer|The last time this IP was seen on a blocklist (in Unix time or 0 if not listed recently)|
|`is_proxy`|boolean|IP has been detected as an anonymous web proxy or anonymous HTTP proxy|
|`is_tor`|boolean|IP is coming from a Tor node|
|`is_vpn`|boolean|IP has been detected as coming from a VPN hosting provider|
|`is_malware`|boolean|IP is involved in distributing malware|
|`is_spyware`|boolean|IP is being used by spyware, malware, botnets or for other malicious activities|
|`is_dshield`|boolean|IP has been flagged on DShield (dshield.org)|
|`is_hijacked`|boolean|hijacked netblocks or netblocks controlled by criminal organizations|
|`is_spider`|boolean|IP is a hostile spider or crawler|
|`is_bot`|boolean|IP is hosting a malicious bot or is part of a botnet|
|`is_spam_bot`|boolean|IP address is hosting a spam bot, comment spamming or other spamming software|
|`is_exploit_bot`|boolean|IP is hosting an exploit finding bot or exploit scanning software|

