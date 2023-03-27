# Package repository
A Debian repository for my packages

This repository contains the following packages:

  - liesel
  - bookthief
  - polonius
  - ocrshot
  - randomtext

You can configure your machine to use this repository as follows:

```
curl -s --compressed "https://rail5.org/ppa/debian/KEY.gpg" | gpg --dearmor | sudo tee /etc/apt/trusted.gpg.d/rail5.gpg >/dev/null

sudo curl -s --compressed -o /etc/apt/sources.list.d/rail5.list "https://rail5.org/ppa/debian/rail5.list"

sudo apt update
```

And from there, `sudo apt install {package}`
