# PasteSuiteAI — Releases

Official binary releases for **[PasteSuiteAI](https://pastesuiteai.com/)** — the desktop tool for instant plain-text pasting, AI dictation, and AI text transforms in any app.

**[⬇ Download the latest release](https://github.com/mcaonline/pastesuiteai-releases/releases/latest)** · [All releases](https://github.com/mcaonline/pastesuiteai-releases/releases) · [Website](https://pastesuiteai.com/) · [Documentation](https://pastesuiteai.com/docs/)

Every release includes a 7-day unlimited trial — no account, no card. Non-AI features stay free forever.

---

## Which file do I need?

| Platform | File | Notes |
|---|---|---|
| **Windows 10 / 11** (64-bit) | `PasteSuiteAI_<version>_x64-setup.exe` | Installer, digitally signed by Keynaptic GmbH |
| **macOS** (Apple Silicon & Intel, macOS 11+) | `PasteSuiteAI_<version>_universal.dmg` | Signed by Keynaptic GmbH and notarized by Apple — available from 1.0.5 in a few days |
| **Linux** (x86-64, portable) | `PasteSuiteAI_<version>_amd64.AppImage` | Runs without installation |
| **Debian / Ubuntu** (x86-64) | `PasteSuiteAI_<version>_amd64.deb` | Native package |

---

## Installing on Windows

1. Download `PasteSuiteAI_<version>_x64-setup.exe` and open it.
2. If Windows shows a blue **"Windows protected your PC"** window, click the small **"More info"** link.

   <img src="https://pastesuiteai.com/smartscreen-1-moreinfo.png" width="380" alt="Windows SmartScreen window: click the More info link">

3. The publisher **"Keynaptic GmbH"** then appears — click **"Run anyway"**.

   <img src="https://pastesuiteai.com/smartscreen-2-runanyway.png" width="380" alt="Windows SmartScreen window showing publisher Keynaptic GmbH: click Run anyway">

4. Follow the installer — that's all.

> PasteSuiteAI is digitally signed by Keynaptic GmbH. As a newly founded company our reputation with Windows SmartScreen is still building, which is why this one-time prompt may appear.

<details>
<summary><strong>Business PC, or the file won't open?</strong></summary>

On managed business PCs with stricter security policies, the downloaded file is sometimes additionally blocked. To allow it once:

1. Right-click `PasteSuiteAI_<version>_x64-setup.exe` and choose **Properties**.
2. On the **General** tab, at the bottom under **Security**, tick the **Unblock** box and confirm with **OK**.

   <img src="https://pastesuiteai.com/unblock-windows.png" width="300" alt="Windows file Properties dialog with the Unblock checkbox enabled">

3. Double-click the file to start it; if prompted, choose **More info** → **Run anyway**.
4. Complete the installation normally.

If a central IT policy still blocks the file, your IT department can approve it once.

</details>

Full illustrated guide: [pastesuiteai.com/install-help](https://pastesuiteai.com/install-help)

---

## Installing on macOS

Runs on Apple Silicon (M1 or newer) and Intel Macs with macOS 11 or newer. The app is signed by Keynaptic GmbH and notarized by Apple.

1. Download `PasteSuiteAI_<version>_universal.dmg` and open it.
2. Drag **PasteSuiteAI** into the **Applications** folder.
3. Open PasteSuiteAI from Applications. macOS asks once whether you want to open an app downloaded from the internet — click **Open**.

On first run, grant the **Accessibility** and **Microphone** permissions when macOS asks — they are required for hotkeys, pasting, and dictation.

---

## Installing on Linux

Works on X11 and Wayland. On Wayland your desktop may ask once to allow the hotkeys and pasting.

### AppImage (any x86-64 distribution)

```sh
chmod +x PasteSuiteAI_<version>_amd64.AppImage
./PasteSuiteAI_<version>_amd64.AppImage
```

No installation required. If the AppImage does not start, your distribution may need FUSE 2 (`sudo apt install libfuse2` on Ubuntu 22.04+).

### Debian / Ubuntu package

```sh
sudo apt install ./PasteSuiteAI_<version>_amd64.deb
```

Then launch **PasteSuiteAI** from your application menu.

---

## Support

- Illustrated install guide: [pastesuiteai.com/install-help](https://pastesuiteai.com/install-help)
- Documentation: [pastesuiteai.com/docs](https://pastesuiteai.com/docs/)
- Questions: [support@pastesuiteai.com](mailto:support@pastesuiteai.com)
