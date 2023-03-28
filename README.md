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
curl -s --compressed "https://deb.rail5.org/rail5.gpg" | gpg --dearmor | sudo tee /etc/apt/trusted.gpg.d/rail5.gpg >/dev/null

sudo curl -s --compressed -o /etc/apt/sources.list.d/rail5.sources "https://deb.rail5.org/debian/rail5.sources"

sudo apt update
```

And from there, `sudo apt install {package}`
