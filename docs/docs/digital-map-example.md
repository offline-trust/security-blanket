# Digital Map Example

## Devices

Laptop/1 - Macbook 12", Space Grey
* ID (clear)
* PW (clear)
* Bio: finger 

Desktop/1 - Dell
* ID (clear)
* PW (clear)

Phone/1 - Pixel 8, Green, Phone Number
* PIN (clear)
* Bio: face

Yubikey/1 - yubikey fido u2f, id desc

Ledger/1 - Ledger Hardware Wallet, id desc
* PIN: (clear)

## Top Level Accounts

Google/1 - xyz@gmail.com
* ID: (clear)
* PW: (clear)
* MFA: @MFA/1, @MFA/2
* backup codes

## Tools

PwdMgr/1 - Google Password Manager via Chrome
* On: @Laptop/1, @Desktop/1, @Phone/1
* ID: @Google/1/ID
* PW: @Google/1/PW

MFA/1 - @Yubikey/1

MFA/2 - Google Authenticator App
* On: @Phone/1
* ID, PW: @Google/1

MFA/3 - SMS 
* On: @Phone/1/PhoneNumber

Wallet/2 - Metamask Software Wallet
* On: @Laptop/1, @Phone/1
* PW: (clear)


## Essential Accounts

BofA/1 - bofa.com
* ID: @PwdMgr/1
* PW: @PwdMgr/1
* MFA: @MFA/3

Coinbase/1 - coinbase.com
* ID: @PwdMgr/1
* PW: @PwdMgr/1
* MFA: @MFA/2