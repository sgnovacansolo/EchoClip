# EchoClip

**Capture the moments that matter.**

EchoClip is a lightweight, native macOS instant replay application designed to make saving gameplay moments effortless. Instead of recording entire gaming sessions, EchoClip continuously captures your display in the background and allows you to save the last 30 seconds whenever something worth keeping happens.

Whether it's an unexpected win, an impressive play or a funny moment with friends, EchoClip makes sure you don't miss it.

## ✨ Features

- **Instant Replay:** Save the previous 30 seconds of gameplay with a single keypress.
- **60 FPS Recording:** Capture smooth, high-frame-rate footage.
- **High Video Quality:** H.264 encoding with a 24 Mbps target bitrate.
- **Native Resolution:** Capture your display without intentionally downscaling the footage.
- **Rolling Recording Buffer:** Continuously keeps recent footage available without saving an entire session.
- **Simple Interface:** Choose your display and save replays through a straightforward interface.
- **Keyboard Shortcut:** Press the backtick (\`) key to save a replay instantly.
- **MP4 Export:** Saved replays are exported as MP4 video files.

## 🎮 How It Works

EchoClip uses a rolling recording buffer to continuously capture your selected display.

1. **Choose your display** using the macOS screen-sharing picker.
2. **Start capturing** and let EchoClip run in the background.
3. **Play your game** as usual.
4. **Press \`** whenever something happens that you want to save.
5. **Your replay is saved** as an MP4 video containing the previous 30 seconds.

You don't need to predict when something interesting will happen or manually start a recording beforehand.

## 🛠️ Built With

EchoClip is built using Apple's native macOS technologies:

- **Swift** – Core application logic.
- **AppKit** – Native macOS interface.
- **ScreenCaptureKit** – Display capture.
- **VideoToolbox** – Hardware-accelerated video encoding.
- **AVFoundation** – MP4 video export.
- **Carbon** – Global keyboard shortcut handling.

## 💻 Platform

- macOS
- Apple Silicon (ARM64)

## 🚧 Development

EchoClip is an ongoing project focused on creating a simple, reliable and high-quality instant replay experience on macOS.

More features and improvements may be introduced as development continues.

---

**EchoClip — Never miss a moment worth saving.**
