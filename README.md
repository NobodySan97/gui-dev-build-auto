# GUI Dev Build Auto

[![Donate Ko-fi](https://img.shields.io/badge/Donate-Ko--fi-ff5e5b.svg)](https://ko-fi.com/nobodysan) [![License](https://img.shields.io/github/license/NobodySan97/tch-nginx-gui.svg?style=flat)](https://github.com/NobodySan97/tch-nginx-gui/blob/master/LICENSE) [![Main Repository](https://img.shields.io/badge/Repository-tch--nginx--gui-blue.svg)](https://github.com/NobodySan97/tch-nginx-gui)

This repository contains automated builds and packaged modular archives of the **Technicolor Nginx Custom GUI** maintained by **NobodySan97**.

## 📥 Installation

Connect via SSH to your rooted Technicolor router and run:

```sh
curl -k https://raw.githubusercontent.com/NobodySan97/gui-dev-build-auto/master/GUI.tar.bz2 --output /tmp/GUI.tar.bz2
bzcat /tmp/GUI.tar.bz2 | tar -C / -xvf -
/etc/init.d/rootdevice force
```

## ☕ Support & Donations

If you appreciate the work on this project and want to support ongoing development:

[![Support on Ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/nobodysan)

---
For issues, contributions, and full source code, please visit the [Main Repository](https://github.com/NobodySan97/tch-nginx-gui).
