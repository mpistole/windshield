# Windshield

A desktop coding app for Claude, OpenAI and Grok. Point a project at a folder,
pick a model, and it reads, edits and runs commands in that folder.

## Download

- **Windows:** [Windshield-Setup.exe](https://github.com/mpistole/windshield/releases/latest/download/Windshield-Setup.exe)
- **macOS (Apple silicon):** [Windshield.dmg](https://github.com/mpistole/windshield/releases/latest/download/Windshield.dmg)

The app tells you when a newer version is out.

## First run

1. Open **Settings** (the gear icon, top left).
2. Paste any of: an Anthropic key, an OpenAI key, an xAI (Grok) key. Or press
   **Sign in to Claude Code** to use a Claude subscription (this needs
   [Claude Code](https://claude.com/code) installed).
3. Add a project with **+**, and choose its folder.

Keys are kept in your computer's own credential store (Windows Credential
Manager, macOS Keychain) and only go to the provider they belong to.

## Unsigned builds

These installers are not code-signed yet.

- **Windows:** if SmartScreen stops it, press **More info**, then **Run anyway**.
- **macOS:** open the .dmg and drag the app to Applications. The first time you
  open it, right-click it, choose **Open**, then **Open** again. If macOS says
  it is damaged, run `xattr -cr "/Applications/Windshield.app"` in Terminal, then open it.
