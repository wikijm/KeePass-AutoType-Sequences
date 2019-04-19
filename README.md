# KeePass-AutoType-Sequences
Lists the automatic typing sequences used in the KeePass password manager. Proposes sequences with or without the use of the MFA by TOTP.

## Auto-typing sequences

| Service | URL | TOTP | Sequence | Explanation |
| ------ | ------ | ------ | ------ | ------ |
| GitHub | https://github.com/login/ | Yes | {USERNAME}{TAB}{PASSWORD}{ENTER}{DELAY 1000}{TOTP}{ENTER} | Type username and password with validation, then wait 1 sec and type TOTP code
| GitHub | https://github.com/login/ | No | {USERNAME}{TAB}{PASSWORD}{ENTER} | Type username and password with validation
| Microsoft Azure portal | https://portal.azure.com/ | Yes | {USERNAME}{ENTER}{DELAY 2500}{PASSWORD}{ENTER}{DELAY 5000}{TOTP}{ENTER}{DELAY 2500}{ENTER} | |
| Microsoft Azure portal | https://portal.azure.com/ | No | {USERNAME}{ENTER}{DELAY 2500}{PASSWORD}{ENTER}{DELAY 5000}{TOTP}{ENTER}{DELAY 2500}{ENTER} | |
| Microsoft Office 365 portal | https://portal.office365.com | Yes | {USERNAME}{ENTER}{DELAY 2500}{PASSWORD}{ENTER}{DELAY 5000}{TOTP}{ENTER}{DELAY 2500}{ENTER} | |
| Microsoft Office 365 portal | https://portal.office365.com | No | {USERNAME}{ENTER}{DELAY 2500}{PASSWORD}{ENTER} | |
