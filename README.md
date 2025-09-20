# Karabiner-Elements Configuration

This repository contains a custom Karabiner-Elements configuration optimized for power users who want advanced keyboard functionality on macOS.

## 🔧 Configuration Overview

### Hardware Setup
- **Apple Internal Keyboard/Trackpad** (VID: 1452, PID: 641) - Built-in MacBook keyboard
- **Razer BlackWidow Chroma** (VID: 5426, PID: 515) - External mechanical keyboard with Apple-style modifier mappings
- **Logitech USB Receiver** (VID: 1133, PID: 50475) - Wireless mouse

### Keyboard Layout
- **Virtual HID Keyboard Type**: ANSI
- **Hold-down Threshold**: 150ms for modifier key activation

## ⌨️ Key Mappings & Shortcuts

### 1. Home Row Modifiers
Transform your home row keys into powerful modifiers while preserving their normal typing function:

#### Left Hand (ASDF)
- **A** (hold) → **Left Control** 
- **S** (hold) → **Left Option**
- **D** (hold) → **Left Command**
- **F** (hold) → **Left Shift**

#### Right Hand (JKL;)
- **J** (hold) → **Right Shift**
- **K** (hold) → **Right Command** 
- **L** (hold) → **Right Option**
- **;** (hold) → **Right Control**

#### Multi-Key Combinations
Hold multiple home row keys simultaneously for combined modifiers:
- **A+S** → **Ctrl + Option**
- **S+D** → **Option + Command**
- **D+F** → **Command + Shift**
- **A+S+D** → **Ctrl + Command + Option**
- **A+S+D+F** → **All modifiers** (Ctrl + Opt + Cmd + Shift)

*Similar combinations work for the right hand (J,K,L,;)*

### 2. Hyper Key (Super Modifier)
- **Caps Lock** → **Hyper Key** (enables custom shortcuts)

### 3. Hyper + Navigation
When Caps Lock (Hyper) is active:
- **Hyper + H** → **← Left Arrow**
- **Hyper + J** → **↓ Down Arrow**  
- **Hyper + K** → **↑ Up Arrow**
- **Hyper + L** → **→ Right Arrow**

### 4. Caps Lock Alternative
- **Double-tap Right Shift** → **Caps Lock toggle**

### 5. Razer Keyboard Modifiers (Apple-style)
The Razer BlackWidow Chroma is configured to behave like an Apple keyboard:
- **Left Windows Key** → **Left Option (⌥)**
- **Left Alt Key** → **Left Command (⌘)**
- **Right Windows Key** → **Right Option (⌥)** 
- **Right Alt Key** → **Right Command (⌘)**

### 6. Layout Fixes
- **` (Grave/Tilde)** → **Non-US Backslash** (fixes layout inconsistencies)

## 🚀 Usage Examples

### Text Editing
- Hold **D** + **C** = **Cmd + C** (Copy)
- Hold **D** + **V** = **Cmd + V** (Paste)
- Hold **A** + **Z** = **Ctrl + Z** (Undo in many apps)

### Window Management  
- **Caps Lock + H/J/K/L** = Navigate with arrows anywhere
- Hold **D** + **Tab** = **Cmd + Tab** (App switcher)

### Advanced Combinations
- Hold **A+S** + **T** = **Ctrl + Option + T** (Terminal in many apps)
- Hold **D+F** + **Space** = **Cmd + Shift + Space** (Spotlight/Alfred)

## 📁 File Structure
```
karabiner/
├── karabiner.json          # Main configuration file
└── README.md              # This documentation
```

## 🔄 Changes Made

### Device Configuration Updates
1. **Updated device identifiers** to match actual hardware (Razer keyboard, Logitech mouse)
2. **Configured Razer BlackWidow Chroma** with Apple-style modifier key mappings
3. **Removed duplicate device entries** and cleaned up configuration

### Key Mapping Enhancements  
1. **Maintained advanced home row mods** for power-user efficiency
2. **Added device-specific modifications** for the Razer keyboard
3. **Preserved Hyper key functionality** with Caps Lock
4. **Kept navigation shortcuts** (Hyper + HJKL)

### Layout Optimizations
1. **Set keyboard type to ANSI** for proper key recognition
2. **Configured proper hold-down threshold** (150ms) for responsive modifier activation
3. **Added layout fixes** for international key compatibility

## 🛠️ Installation

1. Install [Karabiner-Elements](https://karabiner-elements.pqrs.org/)
2. Replace the default configuration file:
   ```bash
   cp karabiner.json ~/.config/karabiner/karabiner.json
   ```
3. Restart Karabiner-Elements or reload the configuration

## ⚠️ Important Notes

- **Learning Curve**: Home row mods require practice to master
- **Timing Sensitivity**: The 150ms threshold balances responsiveness with accidental activation
- **Device Specific**: Some mappings only apply to the configured Razer keyboard
- **Hyper Key**: Caps Lock behavior is completely replaced - use Right Shift double-tap for actual Caps Lock

## 🔗 Compatibility

- **macOS**: All versions supported by Karabiner-Elements
- **Applications**: Works system-wide with all applications
- **Hardware**: Optimized for Razer BlackWidow Chroma but adaptable to other keyboards

---

*Last Updated: September 2025*
*Configuration optimized for power users seeking maximum keyboard efficiency*