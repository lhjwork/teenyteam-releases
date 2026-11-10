# TeenyTeam releases

Installers and update files for [TeenyTeam](https://teenyteam.com/), a small always-on panel that shows what your Claude Code subagents are doing (macOS and Windows).

## Install

Download from the [latest release](https://github.com/lhjwork/teenyteam-releases/releases/latest):

- **macOS** (Apple silicon and Intel): `TeenyTeam_<version>_universal.dmg` — open it and drag TeenyTeam to Applications.
- **Windows** (64-bit): `TeenyTeam_<version>_x64-setup.exe` — run it.

The app is not code-signed yet, so your OS warns once:

- **macOS**: the first open is blocked. Go to System Settings › Privacy & Security, scroll down and click **Open Anyway**.
- **Windows**: SmartScreen shows "Windows protected your PC". Click **More info › Run anyway**.

Then click **Connect** on the first screen. It adds the TeenyTeam recorder to your Claude Code settings (a backup is kept, and you can disconnect anytime). 14-day free trial, no account needed.

Updates install automatically. The other files here (`latest.json`, `.tar.gz`, `.sig`) are for the updater.

## 설치 (한국어)

[최신 릴리스](https://github.com/lhjwork/teenyteam-releases/releases/latest)에서 받으세요. 맥은 `.dmg`(응용 프로그램 폴더로 끌어 넣기), 윈도우는 `-setup.exe`.
아직 서명 전이라 처음 한 번 경고가 떠요. 맥은 시스템 설정 › 개인정보 보호 및 보안 › **그래도 열기**, 윈도우는 **추가 정보 › 실행**.
첫 화면에서 **연결하기**를 누르면 끝. 14일 무료 체험, 계정 없이 돼요.

---

This repository holds release files only. The app source is private. The free hook logger is at [lhjwork/teenyteam-hooks](https://github.com/lhjwork/teenyteam-hooks).

TeenyTeam is an independent project, not affiliated with Anthropic.
