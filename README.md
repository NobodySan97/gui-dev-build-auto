# GUI Dev Build Auto

[![Donate Ko-fi](https://img.shields.io/badge/Donate-Ko--fi-ff5e5b.svg)](https://ko-fi.com/nobodysan) [![License](https://img.shields.io/github/license/NobodySan97/tch-nginx-gui.svg?style=flat)](https://github.com/NobodySan97/tch-nginx-gui/blob/master/LICENSE) [![Main Repository](https://img.shields.io/badge/Repository-tch--nginx--gui-blue.svg)](https://github.com/NobodySan97/tch-nginx-gui)

This repository contains automated builds and packaged modular archives of the **Technicolor Nginx Custom GUI** maintained by **NobodySan97**.

## 📥 Installation

Connect via SSH to your rooted Technicolor router and run:

### Stable Release (Recommended)
```sh
curl -k https://raw.githubusercontent.com/NobodySan97/gui-dev-build-auto/master/GUI.tar.bz2 --output /tmp/GUI.tar.bz2
bzcat /tmp/GUI.tar.bz2 | tar -C / -xvf -
/etc/init.d/rootdevice force
```

### Preview Release (Testing)
```sh
curl -k https://raw.githubusercontent.com/NobodySan97/gui-dev-build-auto/master/GUI_preview.tar.bz2 --output /tmp/GUI.tar.bz2
bzcat /tmp/GUI.tar.bz2 | tar -C / -xvf -
/etc/init.d/rootdevice force
```

---

## 📦 Repository Structure

* **`GUI.tar.bz2`**: Full archive for the latest official Stable release.
* **`GUI_preview.tar.bz2`**: Full archive for the latest Preview release.
* **`GUI_dev.tar.bz2`**: Development branch archive.
* **`modular/`**: Individual hardware and service overlay archives (base, GUI files, device-specific LED support for DGA, DGA4131, DGA4331, TG788, TG789, TG799, TG800, and upgrade packs).
* **`*.version`**: Version tracker files (`latest.version`, `stable.version`, `preview.version`).

---

## ☕ Support & Donations

If you appreciate the work on this project and want to support ongoing development:

[![Support on Ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/nobodysan)

---
For issues, bug reports, and full source code, please visit the [Main Repository](https://github.com/NobodySan97/tch-nginx-gui).
