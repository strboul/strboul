Import my PGP/GnuPG key to your keyring and verify it as follows:

```sh
wget https://raw.githubusercontent.com/strboul/strboul/master/gpg/4C884872307BB096C0EB226D9DFB9FAB33E2BB02.key
gpg --import 4C884872307BB096C0EB226D9DFB9FAB33E2BB02.key
gpg --fingerprint me@strboul.com
```
