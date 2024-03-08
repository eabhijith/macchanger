macchanger
==========

![](https://acrogenesis.com/macchanger/preview.png)

Easily change your mac address, for OS X

Usage
---

```
Usage: macchanger [options] device
    -m, --mac MAC                    Set the MAC address, macchanger -m XX:XX:XX:XX:XX:XX en0
    -r, --random                     Set random MAC address, macchanger -r en0
    -s, --show                       Show the MAC address, macchanger -s en0

```

Install
---

1. Install brew (http://brew.sh/)
2. `brew update`
3. `brew install acrogenesis/macchanger/macchanger`

Contributing
---
to create a Mac address use : openssl rand -hex 6 | sed 's/\(..\)/\1:/g; s/.$//'
1. Fork it.
2. Create a branch `git checkout -b my_markup`
3. Commit your changes `git commit -am "Cool new feature"`
4. Push to the branch `git push origin my_markup`
5. Open a [Pull Request][1]
6. Enjoy a refreshing `Insert Favorite Beverage` and wait

[1]: https://github.com/acrogenesis/macchanger/pulls
