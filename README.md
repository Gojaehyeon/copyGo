# ClipGo – Image Copy Extension

A macOS utility that lets you instantly copy the actual image data of a selected file in Finder using the `⌘ + ⇧ + C` shortcut.

## ✨ Features

- ✅ Press `Command + Shift + C` to copy image **data**, not just file path
- ✅ Works directly from Finder – no need to open the file
- ✅ Supports PNG, JPG, JPEG, HEIC, GIF
- ✅ Uses native clipboard – paste directly into any app like Keynote, Notes, etc.
- ✅ Built with [`hotkey`](https://github.com/soffes/HotKey) for simple and reliable shortcut binding

## 🚀 How It Works

1. Select an image file in Finder
2. Press `⌘ + ⇧ + C`
3. The image is now in your clipboard – ready to paste!

## 📦 Requirements

- macOS 12 or later
- Full Disk Access / Accessibility permission required
- Built and signed locally (not App Store-compatible due to Finder access)

## 🔧 Tech Stack

- Swift (AppKit)
- `hotkey` by Sam Soffes
- AppleScript to fetch selected Finder item

## ⚠️ Permissions

You’ll need to allow:
- **Accessibility Access** – to read selection from Finder

## 📜 License

MIT