# OrangeFox R12 Builder for Samsung Galaxy A51 (A515F)

Build OrangeFox Recovery for Galaxy A51 using GitHub Actions
Only supports OrangeFox 12.1/11
*** WARNING***: the fox_14.1 branch is EXPERIMENTAL! Also, syncing will take a VERY long time


![OrangeFox Banner](https://wiki.orangefox.tech/banner.svg)

---

## 📱 Device Support
- **Device:** Samsung Galaxy A51 4G
- **Codename:** a51
- **Model:** SM-A515F
- **Chipset:** Exynos 9611

---

## ✨ Features
- Auto updates in background
- Beautiful Material Design 2 UI
- Internal Storage decryption support
- External Storage (OTG and MicroSD)
- ADB Sideload & MTP
- Magisk patch included
- Password protection
- Fully open-source

---

## 🚀 Quick Build

### Via GitHub Actions (Recommended)

1. **Fork** this repository
2. Go to **Actions** tab
3. Click **"OrangeFox - Build"** → **"Run workflow"**
4. Use default parameters (already configured for A51)
5. Wait ~1-2 hours for build to complete
6. Download from **Releases**

### Parameters (Pre-configured)

| Parameter | Value |
|-----------|-------|
| MANIFEST_BRANCH | 12.1 |
| DEVICE_TREE | https://github.com/Yilliee/recovery_a51.git |
| DEVICE_TREE_BRANCH | fox_10.0 |
| DEVICE_PATH | device/samsung/a51 |
| DEVICE_NAME | a51 |
| BUILD_TARGET | recovery |
| RECOVERY_TAR | true ✅ |

---

## 📦 Output

Build artifacts will be available in the **Releases** section as:
- `OrangeFox-R12.1-a51.tar` (for Odin flashing)
- `recovery-installer.zip` (optional)

---

## ⚠️ Important Notes

- **Bootloader must be unlocked** before flashing
- Use **Odin** to flash the `.tar` file
- Backup your data before flashing!
- This is based on [Yilliee's device tree](https://github.com/Yilliee/recovery_a51)

---

## 🙏 Credits

- [@Yilliee](https://github.com/Yilliee) - Device tree maintainer
- [OrangeFox Recovery Project](https://gitlab.com/OrangeFox)
- [TeamWin Recovery Project](https://github.com/TeamWin)
- [kinguser981](https://github.com/kinguser981) - Original builder template

---

## 📝 License

This project follows the same license as OrangeFox Recovery.
