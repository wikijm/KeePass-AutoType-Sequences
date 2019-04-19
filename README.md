# KeePass-AutoType-Sequences
Lists the automatic typing sequences used in the KeePass password manager. Proposes sequences with or without the use of the MFA by TOTP.


## Auto-typing sequences
### Connexion
| Service | URL | TOTP | Sequence | Explanation | Addition date |
| ------ | ------ | ------ | ------ | ------ | ------ |
| GitHub | https://github.com/login/ | Yes | {USERNAME}{TAB}{PASSWORD}{ENTER}{DELAY 1000}{TOTP}{ENTER} | Type username and password with validation, then wait 1 sec and type TOTP code | 2019/04/19 |
| GitHub | https://github.com/login/ | No | {USERNAME}{TAB}{PASSWORD}{ENTER} | Type username and password with validation | 2019/04/19 |
| Microsoft Azure portal | https://portal.azure.com/ | Yes | {USERNAME}{ENTER}{DELAY 2500}{PASSWORD}{ENTER}{DELAY 5000}{TOTP}{ENTER}{DELAY 2500}{ENTER} | | 2019/04/19 |
| Microsoft Azure portal | https://portal.azure.com/ | No | {USERNAME}{ENTER}{DELAY 2500}{PASSWORD}{ENTER}{DELAY 5000}{TOTP}{ENTER}{DELAY 2500}{ENTER} | | 2019/04/19 |
| Microsoft Office 365 portal | https://portal.office365.com | Yes | {USERNAME}{ENTER}{DELAY 2500}{PASSWORD}{ENTER}{DELAY 5000}{TOTP}{ENTER}{DELAY 2500}{ENTER} | | 2019/04/19 |
| Microsoft Office 365 portal | https://portal.office365.com | No | {USERNAME}{ENTER}{DELAY 2500}{PASSWORD}{ENTER} | | 2019/04/19 |
| Neflix | https://www.netflix.com/fr/login | No | {TAB}{TAB}{USERNAME}{TAB}{PASSWORD}{ENTER} | | 2019/04/19 |


### Password change
| Service | URL | TOTP | Sequence | Explanation | Addition date |
| ------ | ------ | ------ | ------ | ------ | ------ |
| GitHub | https://github.com/settings/admin | N/A | {TAB 25}{PASSWORD}{TAB}{NEWPASSWORD}{TAB}{NEWPASSWORD}{TAB 2}{ENTER} | Type actual password, then twice an automatic-generated password with validation | 2019/04/19 |
