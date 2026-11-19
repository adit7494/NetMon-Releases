# NetMon — Network Speed Monitor for Windows

NetMon is a network speed monitor and data usage tracker for Windows 10 and 11.
See live download and upload speeds on your desktop or taskbar, check which apps are using bandwidth,
and review connection problems after they happen.

[**Download NetMon v0.2.0 for Windows x64**](https://github.com/adit7494/NetMon-Releases/releases/download/v0.2.0/NetMon-Setup-0.2.0.exe)
· [Latest release and notes](https://github.com/adit7494/NetMon-Releases/releases/latest)

## What you can monitor

- **Live network speed.** View download and upload rates in a desktop widget or on the Windows
  taskbar, including secondary monitors.
- **Bandwidth by app and network.** See estimated usage by app and recorded totals by Windows
  network profile, such as your home or work Wi-Fi.
- **Connection quality.** Track latency, jitter, and packet loss. Open the connection log to review
  outages and periods of high latency.
- **Monthly data usage.** Set a data limit and billing day to see usage for your billing cycle and
  your remaining daily budget. If your plan renews on the 15th, set **Settings → Data plan → Billing day** to `15`.
- **Reports and backups.** Export usage history to CSV or generate a PDF report for a selected date
  range. NetMon can make automatic backups and copy them to a folder you choose.

## Install NetMon

1. Download the Windows x64 installer above. When browsing releases, look for `NetMon-Setup-*.exe`
   under **Assets**.
2. Run Windows Setup. NetMon installs for your Windows account and requires x64 support.
   You can install it without administrator rights.
3. Open NetMon from the Start menu. Click the tray icon to show or hide the widget, or right-click it
   to open usage history and settings.

The current installer is unsigned. Windows SmartScreen may show a warning.

## Automatic updates

NetMon `0.2.0` and newer check for stable releases at startup and daily while the app runs. To check
manually, choose **Check for updates…** in the tray or widget menu. After you approve an update,
NetMon verifies the downloaded installer against the SHA-256 checksum and opens Windows Setup.

## Usage history

NetMon records traffic seen by this PC while the app is running. Enable **Start with Windows** in
Settings to track usage from sign-in. Usage history and settings are stored locally in
`%APPDATA%\NetMonWidget`.

## Report a problem

Include your NetMon version, Windows version, and the steps to reproduce it. Remove personal details
from any logs or screenshots you share. [Open a GitHub issue](https://github.com/adit7494/NetMon-Releases/issues/new)
