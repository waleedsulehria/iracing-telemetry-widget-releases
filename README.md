# 🏎️ iRacing Input Telemetry Widget

Telemetry overlay for iRacing with real-time input visualization and performance analysis.

![Version](https://img.shields.io/github/v/release/waleedsulehria/iracing-telemetry-widget-releases)
![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Downloads](https://img.shields.io/github/downloads/waleedsulehria/iracing-telemetry-widget-releases/total)

---

## ✨ Features

### 🏁 Real-Time Input Visualization, Controls and Performance analysis
- **Steering Wheel Display** - Visual representation of steering angle with smooth animations
- **Input Bars** - Live throttle and brake input monitoring, also displays ABS on the wherever it is activated.
- **Reference Lap Loading** - Load and compare against saved reference laps (Requires downloading csv lap files from Garage61)
- **Precision Tracking** - See exactly what inputs you're making in real-time
- **Gear & RPM Display** - Current gear and engine RPM with visual indicators
- **Brake Bias Display** - Real-time brake bias percentage
- **TC & ABS Levels** - Traction control and ABS settings display
- **ABS Activation Indicator** - Real-time visual feedback when ABS is actively engaged
- **Telemetry Markers On Track** - Mark points of interests, custom brake points etc while on track.

---

## 📥 Download

**[⬇️ Download Latest Release](https://github.com/waleedsulehria/iracing-telemetry-widget-releases/releases/latest)**

### System Requirements
- **OS:** Windows 10 or Windows 11
- **Game:** iRacing (active subscription required)
- **RAM:** 4GB minimum, 8GB recommended
- **Storage:** ~100MB free space

---

## 🚀 Installation

1. **Download** the latest `iracing_telemetry.exe` from the [Releases](https://github.com/waleedsulehria/iracing-telemetry-widget-releases/releases) page
2. **Run** the executable - no installation needed!
3. **Start** iRacing and begin your session
4. **Enjoy** real-time telemetry overlay

> **Note:** The app automatically detects when iRacing is running and connects to the telemetry feed.

---

## 🎯 Usage

### First Launch
1. Run `iracing_telemetry.exe`
2. The overlay window will appear
3. Start iRacing and join a session
4. The overlay will automatically connect and display telemetry

### How to
- **Move Windows:** Drage from the top black bar to move window
- **Resize:** Use small yellow box on the bottom right to resize
- **Toggle Widgets:** Turn On/Off specific widgets from the settings icon
- **Lap Comparison:** Download a lap from Garage61 (export to csv) -> Settings -> Pick Reference CSV (Dashed lines are comparison lap inputs while solid lines are your real time inputs)
- **ABS and Pitlimiter:** Whenever `ABS` is activated while braking , brake lines, brake bar and top bar will start pulsating on activation. Whenever pit limiter is turned on RPM Widget will start blinking.

---

## ⚙️ Settings Guide

### **How to Access Settings**
Click the **⚙️ gear icon** in the top-left corner of the overlay.

---

### **Widget Visibility**
Toggle which widgets appear on your overlay:
- ✅ **Driver Info** - Your name, car number, and manufacturer logo
- ✅ **Input Bars** - Throttle and brake bars (changes color when ABS activates)
- ✅ **Steering Wheel** - Real-time steering visualization
- ✅ **Lap Times** - Current, last, and best lap times
- ✅ **Gear/RPM** - Current gear with RPM gauge and shift lights
- ✅ **Driver Controls** - Brake bias, TC level, ABS level

**Tip:** Uncheck widgets you don't need to make the overlay smaller!

---

### **Comparison Settings**

#### **Reference Lap**
- Click **"Load Reference Lap"** to select a CSV file from a previous lap
- The overlay will compare your current inputs to the reference lap
- Shows brake/throttle comparison graphs in real-time

#### **Toggle Comparison**
- Use the **"Show/Hide Comparison"** button to toggle the comparison graphs
- Hotkey: **Alt+C** (customizable)

---

### **Track Markers**

#### **What are Track Markers?**
Track markers let you set audio alerts at specific points on the track. When you approach a marker, you'll hear a beep to remind you of important points (braking zones, turn-in points, etc.).

#### **Setting Up Markers**

**1. Set the "Mark Position" Hotkey:**
- Click the **green "Mark Position"** button in settings
- Press a key (e.g., `Alt+M`) or a wheel button
- The button will show your chosen hotkey

**2. Mark a Position:**
- Drive to the point you want to mark
- Press your hotkey
- You'll hear a beep confirming the marker was set
- If there's already a marker within 50 meters, it will be replaced

**3. Clear Markers:**

**Clear Closest Marker:**
- Click the **orange "Clear Closest"** button to set a hotkey
- Press the hotkey while driving to remove the nearest marker
- Great for removing one marker without clearing all

**Clear All Markers:**
- Click the **red "Clear All"** button to set a hotkey
- Press the hotkey to remove ALL markers at once
- Use this to start fresh

#### **Warning Distance**
- Adjust the slider to set how far before a marker the beep plays
- Range: 1-100 meters
- Default: 50 meters
- Example: If set to 30m, the beep plays when you're 30 meters away from the marker

---

## 🎮 Hotkey Examples

### **Keyboard Hotkeys:**
- `Alt+M` - Mark position
- `Alt+C` - Toggle comparison
- `Ctrl+Shift+X` - Clear all markers
- `Alt+F7` - Toggle visibility

### **Wheel Button Hotkeys:**
- `joy0_btn12` - Button 12 on your first joystick/wheel
- `joy0_btn13` - Button 13 on your first joystick/wheel
- The app will show you the button name when you press it during setup

**Tip:** You can mix keyboard and wheel buttons! For example:
- Mark position: `joy0_btn12` (wheel button)
- Clear closest: `joy0_btn13` (wheel button)
- Clear all: `Ctrl+Shift+X` (keyboard)

## 📸 Screenshots
<img width="957" height="144" alt="Screenshot 2025-12-22 033926" src="https://github.com/user-attachments/assets/954b43e6-ed42-455f-a4d6-0d2559ac318c" />

<img width="957" height="144" alt="Screenshot 2025-12-22 050846" src="https://github.com/user-attachments/assets/c2f4e1d7-fe87-4fb5-87b8-557ea36f7c0e" />

<img width="215" height="585" alt="Screenshot 2026-01-06 201745" src="https://github.com/user-attachments/assets/34a1df7c-0db0-46d2-8981-d4a3996576bb" />


---

## ❓ FAQ

### Does this work with all cars?
Yes! The overlay works with all iRacing cars and tracks.

### Does it affect game performance?
No! The overlay runs as a separate process with minimal CPU/RAM usage.

### Can I run this on a second monitor?
Absolutely! You can move the overlay to any monitor.

---

## 🐛 Troubleshooting

### Overlay doesn't connect to iRacing
- Make sure iRacing is running and you're in a session (not in the UI)
- Try restarting both iRacing and the overlay
- Check that iRacing telemetry is enabled in settings

### Overlay is laggy
- Close other unnecessary applications
- Reduce the number of visible widgets
- Check your system meets the minimum requirements

### Can't see the overlay
- Check if the overlay is minimized to system tray
- Make sure it's not hidden behind iRacing window
- Try moving it to a different monitor

---

## 📝 Changelog

See [Releases](https://github.com/waleedsulehria/iracing-telemetry-widget-releases/releases) for version history and changes.

---

## 💬 Support

Found a bug or have a feature request? Please open an issue on the [Issues](https://github.com/waleedsulehria/iracing-telemetry-widget-releases/issues) page.

---

## 📄 License

This project is licensed under the MIT License.

---

## 🙏 Acknowledgments

- Built with [PySide6](https://www.qt.io/qt-for-python)
- Uses [pyirsdk](https://github.com/kutu/pyirsdk) for iRacing telemetry
- Special thanks to Team Exiled for all the support in development of this overlay.
- Inspired by professional racing telemetry systems used by a dear friend Michael Shumway in his Lamborghini GT3 RaceCar

  [![IMAGE ALT TEXT](http://img.youtube.com/vi/Se3z8jnuCMo/0.jpg)](http://www.youtube.com/watch?v=Se3z8jnuCMo "LVRY GT3 - 2:50.73 Qualifying Lap at BBM")


