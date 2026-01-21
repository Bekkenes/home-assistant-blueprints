# Home Assistant Blueprints

This repository contains a collection of scripts and automations developed for my personal Home Assistant setup.

You are free to use, modify, and adapt these configurations for your own environment.

## Available Blueprints

### 💧 Notify on Leak Detection (Advanced)
A robust automation that handles mobile notifications and smart speaker announcements when a water leak is detected.

**Key Features:**
* **Action Selector:** Uses the native Action UI for notifications, allowing you to easily select mobile devices (even those that don't show up in standard dropdowns).
* **Presence Awareness:** Smart speakers (TTS) will **only** announce the warning if someone is actually home.
* **Multi-Device:** Supports notifying multiple phones and playing audio on multiple speakers simultaneously.
* **Safety Delay:** Includes a short delay (e.g., 5s) to prevent false positives from sensor flickers.

## How to Use
1.  Click on the blueprint file you want to use (e.g., `leak_notification.yaml`).
2.  Click the **Raw** button in the top right corner of the file view.
3.  Copy the URL from your browser's address bar.
4.  In Home Assistant, go to **Settings** > **Automations & Scenes** > **Blueprints**.
5.  Click **Import Blueprint** and paste the URL.

## Disclaimer
These configurations are provided "as-is" without warranty. Please review the YAML code to ensure compatibility with your specific devices before importing.
