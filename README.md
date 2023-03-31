# Package repository
A Debian repository for my packages

This repository contains the following packages:

  - liesel
  - bookthief
  - polonius
  - ocrshot
  - randomtext

You can configure Debian to use this repository as follows:

```
sudo curl -s -o /etc/apt/trusted.gpg.d/rail5.gpg "https://deb.rail5.org/rail5.gpg"

sudo curl -s -o /etc/apt/sources.list.d/rail5.list "https://deb.rail5.org/debian/rail5.list"

sudo apt update
```

And from there, `sudo apt install {package}`
