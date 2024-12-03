# software-updater


# Binance & Proton Applications Updater

This repository contains a set of shell scripts to help you automate the process of updating **Binance** and **Proton** applications on Linux.

---

## ⚙️ Features

- Automates the update process for **Proton Pass** and **Binance** applications.
- Reduces manual intervention by following the official update instructions.

---

## 📚 Official Manuals

To better understand the setup and manual installation process, refer to the official documentation:

- **Proton Pass:** [Proton Pass Setup for Linux](https://proton.me/support/set-up-proton-pass-linux)
- **Binance:** [Binance Download Page](https://www.binance.com/en/download)

---

## ⚠️ Disclaimer

Use these scripts at your own risk. By using this repository, you agree that the author holds no responsibility for any issues or damages caused by the usage of the scripts.

---

## 🚀 How to Use

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/binance-proton-updater.git
   cd software-updater
   ```


2. Make the scripts executable:
   ```
   chmod +x proton/update-proton-pass
   chmod +x  binance/update-binance
   ```


3. Optionaly create symlink or use directly as you want:
   ```
   sudo ln -s $(pwd)/proton/update-proton-pass /usr/local/bin/update-proton-pass
   sudo ln -s $(pwd)/binance/update-binance /usr/local/bin/update-binance
   ```

