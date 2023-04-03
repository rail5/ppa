# deb.rail5.org
A Debian repository for my packages

This repository contains the following packages for **amd64**, **i386**, and **arm64** architectures:

  - [liesel](https://github.com/rail5/liesel)
  - [bookthief](https://github.com/rail5/bookthief)
  - [polonius](https://github.com/rail5/polonius)
  - [ocrshot](https://github.com/rail5/ocrshot)
  - [randomtext](https://github.com/rail5/randomtext)

You can configure Debian to use this repository as follows:

```
sudo curl -s -o /etc/apt/trusted.gpg.d/rail5.gpg "https://deb.rail5.org/rail5.gpg"

sudo curl -s -o /etc/apt/sources.list.d/rail5.list "https://deb.rail5.org/debian/rail5.list"

sudo apt update
```

And from there, `sudo apt install {package}`
