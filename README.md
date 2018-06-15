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
| Date  | Version    | Status | Type | Description |
| ------- | ------- | -------- |-------- |-------- |
|17 Dec 2017 |`v1.0`|Complete|High|Add feature random and update header email|
|21 Dec 2017 |`v1.1`|Complete|Low|Update header email|
|07 Jan 2018 |`v1.2`|Complete|High|Update all system on sender|
|13 Jan 2018 |`v1.3`|Complete|High|Fix all bug after last update|
|22 Feb 2018 |`v1.4`|Complete|Medium|Add feature multiple relay|
|02 Mar 2018 |`v1.4.1`|Complete|Low|Header update from AssasinSpam|
|01 Jun 2018 |`v1.5`|Failed|Medium|Get score from email AssasinSpam with CURL <a href="http://spamcheck.postmarkapp.com/filter">http://spamcheck.postmarkapp.com/filter</a>|

