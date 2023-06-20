# deb.rail5.org
A Debian repository for my packages

All of these packages work on Debian Stable (**Bookworm**) and OldStable (**Bullseye**)

This repository contains the following packages for **amd64**, **i386**, and **arm64** architectures:

  - [liesel](https://github.com/rail5/liesel) - *Convert PDFs to booklets (command-line)*
  - [bookthief](https://github.com/rail5/bookthief) - *Convert PDFs to booklets (GUI)*
  - [polonius](https://github.com/rail5/polonius) - *A uniquely memory-efficient text editor*
  - [ocrshot](https://github.com/rail5/ocrshot) - *Copy text from videos &amp; photos by screenshotting*
  - [randomtext](https://github.com/rail5/randomtext) - *Converts output from /dev/urandom to printable ASCII*
  - [evolution-notify](https://github.com/rail5/evolution-notify) - *Provides a systray icon displaying unread email count for Evolution*
  - [stepgrampa](https://github.com/rail5/stepgrampa) - *Replaces MATE's engrampa with GNOME's file-roller*

You can configure Debian to use this repository as follows:

```
sudo curl -s -o /etc/apt/trusted.gpg.d/rail5.gpg "https://deb.rail5.org/rail5.gpg"

sudo curl -s -o /etc/apt/sources.list.d/rail5.list "https://deb.rail5.org/debian/rail5.list"

sudo apt update
```

And from there, `sudo apt install {package}`
