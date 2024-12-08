# deb.rail5.org

This repository contains the following packages for **amd64**, **i386**, and **arm64** architectures:

| Package                                                       | Description                                                           |
| ------------------------------------------------------------- | --------------------------------------------------------------------- |
| [liesel](https://github.com/rail5/liesel)                     | Converts PDFs to booklets *(terminal)*                                |
| [bookthief](https://github.com/rail5/bookthief)               | Converts PDFs to booklets *(GUI)*                                     |
| [polonius](https://github.com/rail5/polonius)                 | A text editor for very large files                                    |
| [autobuild](https://github.com/rail5/autobuild)               | Automatically builds & distributes Debian packages                    |
| [autobuild-web](https://github.com/rail5/autobuild)           | A web front-end for autobuild                                         |
| [ocrshot](https://github.com/rail5/ocrshot)                   | Copies text from videos & photos by screenshotting                    |
| [evolution-notify](https://github.com/rail5/evolution-notify) | Provides a systray icon displaying unread email count for *Evolution* |
| [stepgrampa](https://github.com/rail5/stepgrampa)             | Replaces MATE's *engrampa* with GNOME's *file-roller*                 |

You can configure Debian to use this repository as follows:

```shell
sudo curl -s -o /etc/apt/trusted.gpg.d/rail5-signing-key.gpg "https://deb.rail5.org/rail5-signing-key.gpg"

sudo curl -s -o /etc/apt/sources.list.d/rail5.list "https://deb.rail5.org/rail5.list"

sudo apt update
```

And from there, `sudo apt install {package}`

