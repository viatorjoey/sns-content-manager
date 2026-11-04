## SNS Content Manager v1.2.2

### Fixed in v1.2.2
- Downloads no longer get stuck at “Queued”: if one download fails (for example when the disk is full), the queue keeps going and the item shows a clear “Not enough disk space” message.
- Checks free space before downloading (needs at least 2 GB).
- 다운로드가 ‘대기 중’에서 멈추던 문제를 고쳤어요. 저장 공간이 부족하면 그 항목에 안내가 뜨고 나머지는 계속 받아요.

---
### v1.2.1

### Fixed in v1.2.1
- **Windows:** the app window closed immediately on launch (window icon was passed as PNG; Windows needs .ico). Thanks to the user who reported it!
- 윈도우에서 앱 창이 뜨기 직전에 꺼지던 문제를 고쳤어요.

---
### v1.2.0

**Downloads** — one zip contains both the Mac and Windows installers.
- 🇺🇸 English: **SNSContentManager_EN.zip**
- 🇰🇷 한국어: **SNSContentManager_KO.zip**

#### What's new in v1.2.0
- 📱 **iPhone connection** — send links from the iPhone Share button (Shortcuts) or a phone page; the Mac/Windows computer records or downloads them. Works on the same Wi-Fi, or anywhere with Tailscale.
- 🌐 English edition
- Fixes: login window freeze on Mac, “Continue with Facebook” login, removed cookie-file import

### Install
- **Mac** (macOS 11+): unzip → double-click `Install for Mac.command` (KO: `Mac 설치.command`). If macOS warns about an unidentified developer: right-click → Open.
- **Windows** (10/11): extract the zip first → double-click `Install for Windows.bat` (KO: `Windows 설치.bat`). If SmartScreen appears: More info → Run anyway.

Guide: https://claude.ai/artifact/NwLnBJVfiDEF9oamDkisGP
