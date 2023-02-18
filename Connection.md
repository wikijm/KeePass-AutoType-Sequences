# Connexion
| Service | URL | TOTP | Sequence | Explanation | Last edit |
| ------ | ------ | ------ | ------ | ------ | ------ |
| Cloudflare | https://dash.cloudflare.com/login | Yes | {TAB 5}{USERNAME}{TAB}{PASSWORD}{ENTER}{DELAY 6000}{TOTP}{ENTER} | Type username and password with validation, then wait 3 sec and type TOTP code | 2023/02/18 |
| GitHub | https://github.com/login/ | Yes | {USERNAME}{TAB}{PASSWORD}{ENTER}{DELAY 1000}{TOTP}{ENTER} | Type username and password with validation, then wait 1 sec and type TOTP code | 2019/04/19 |
| GitHub | https://github.com/login/ | No | {USERNAME}{TAB}{PASSWORD}{ENTER} | Type username and password with validation | 2019/04/19 |
| OVH | https://www.ovh.com/manager/web/login/ | Yes | {USERNAME}{TAB}{PASSWORD}{ENTER}{DELAY 2500}{TOTP}{ENTER} | Type username and password with validation, then wait 2,5 sec and type TOTP code | 2020/01/05 |
| Microsoft Azure portal | https://portal.azure.com/ | Yes | {USERNAME}{ENTER}{DELAY 2500}{PASSWORD}{ENTER}{DELAY 5000}{TOTP}{ENTER}{DELAY 2500}{ENTER} | | 2019/04/19 |
| Microsoft Azure portal | https://portal.azure.com/ | No | {USERNAME}{ENTER}{DELAY 2500}{PASSWORD}{ENTER}{DELAY 5000}{TOTP}{ENTER}{DELAY 2500}{ENTER} | | 2019/04/19 |
| Microsoft Office 365 portal | https://portal.office365.com | Yes | {USERNAME}{ENTER}{DELAY 2500}{PASSWORD}{ENTER}{DELAY 5000}{TOTP}{ENTER}{DELAY 2500}{ENTER} | | 2019/04/19 |
| Microsoft Office 365 portal | https://portal.office365.com | No | {USERNAME}{ENTER}{DELAY 2500}{PASSWORD}{ENTER} | | 2019/04/19 |
| Netflix | https://www.netflix.com/fr/login | No | {TAB}{TAB}{USERNAME}{TAB}{PASSWORD}{ENTER} | | 2019/04/19 |
| TCL | https://www.tcl.fr/tickets-abonnements/demander-une-attestation#main-content | No | {TAB 4}{S:e-mail}{TAB}{S:birthdate}{TAB 3}{S:cardid}{TAB 5}{SPACE}{TAB 2}{SPACE} | Requires to create string fields for e-mail,birthdate and cardid | 2020/11/07 |
