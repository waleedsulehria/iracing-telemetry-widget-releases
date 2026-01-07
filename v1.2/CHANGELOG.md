# 🎉 iRacing Input Telemetry v1.2 - Changelog

**Release Date:** January 7, 2026

---

## ✨ What's New in v1.2

### 🎮 New Features

#### **1. Track Markers with Audio Alerts**
- **Set markers** at any point on the track using a customizable hotkey (keyboard or wheel button)
- **Audio beep** plays when approaching markers (configurable warning distance)
- **Clear markers** individually (clear closest) or all at once
- **Persistent storage** - markers are saved between sessions
- Perfect for marking braking points, turn-in points, or danger zones!

#### **2. Car-Specific Steering Wheels**
- **Mercedes AMG GT3** - Shows authentic AMG steering wheel
- **Porsche 992 Cup** - Shows Porsche Cup steering wheel
- **Generic wheel** for all other cars
- Automatically switches when you change cars

#### **3. Improved Steering Wheel Display**
- **Smoother rotation** - eliminated micro-jitter/shake
- **Better scaling** - Porsche wheel no longer clips at edges
- More responsive and realistic feel

---

## 🔧 Bug Fixes

- Fixed steering wheel micro side-to-side shake
- Fixed Porsche Cup wheel being cut off at the edges during rotation
- Fixed "Clear Closest Marker" button not working with wheel buttons
- Fixed joystick monitor to support multiple simultaneous hotkeys

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
- `F6` - Close overlay
- `Alt+F7` - Toggle visibility

### **Wheel Button Hotkeys:**
- `joy0_btn12` - Button 12 on your first joystick/wheel
- `joy0_btn13` - Button 13 on your first joystick/wheel
- The app will show you the button name when you press it during setup

**Tip:** You can mix keyboard and wheel buttons! For example:
- Mark position: `joy0_btn12` (wheel button)
- Clear closest: `joy0_btn13` (wheel button)
- Clear all: `Ctrl+Shift+X` (keyboard)

---

## 📋 System Requirements

- **OS:** Windows 10 or Windows 11
- **Game:** iRacing (active subscription required)
- **RAM:** 4GB minimum, 8GB recommended
- **Storage:** ~100MB free space
- **iRacing Mode:** Windowed or Borderless Windowed (required for overlay)

---

## 🚀 Installation

1. **Download** `iracing_telemetry.exe` from this release
2. **Run** the executable - no installation needed!
3. **Start** iRacing and join a session
4. **Enjoy** real-time telemetry overlay

> **Note:** Windows may show a security warning for unsigned executables. Click "More info" → "Run anyway"

---

## 💡 Tips & Tricks

1. **Marker Strategy:**
   - Mark your braking points for each corner
   - Set warning distance to 20-30m for braking zones
   - Use different markers for different track conditions

2. **Reference Laps:**
   - Load a fast lap from a coach or alien driver
   - Compare your inputs to see where you can improve
   - Focus on brake application points and throttle timing

3. **Widget Layout:**
   - Hide widgets you don't use to reduce clutter
   - The overlay automatically resizes based on visible widgets
   - Drag the overlay to your preferred screen position

4. **Wheel Buttons:**
   - Use wheel buttons for markers so you don't need to reach for the keyboard
   - Most wheels have extra buttons on the back or sides
   - The app detects all connected joysticks/wheels automatically

---

## 🐛 Known Issues

None at this time! Report issues on GitHub.

---

## 🙏 Credits

Developed with ❤️ for the iRacing community.

**Enjoy your racing! 🏁**

