# ClusterPilot

The AI agent that finds why your Kubernetes clusters break, fixes it safely, and proves it worked.
These are the installers for the ClusterPilot desktop app.

## Download the latest version

| System | Download | Notes |
| --- | --- | --- |
| **Windows** 10 and 11 (64-bit) | [ClusterPilot-windows-x64-setup.exe](https://github.com/luckypolamreddy/clusterpilot-releases/releases/latest/download/ClusterPilot-windows-x64-setup.exe) | Installs for you only, no admin rights needed |
| Windows for IT (all users, needs admin) | [ClusterPilot-windows-x64.msi](https://github.com/luckypolamreddy/clusterpilot-releases/releases/latest/download/ClusterPilot-windows-x64.msi) | For Intune or Group Policy |
| **macOS** 11+ (Apple silicon) | [ClusterPilot-macos-arm64.dmg](https://github.com/luckypolamreddy/clusterpilot-releases/releases/latest/download/ClusterPilot-macos-arm64.dmg) | M1 and later |
| **Linux** (any 64-bit) | [ClusterPilot-linux-x86_64.AppImage](https://github.com/luckypolamreddy/clusterpilot-releases/releases/latest/download/ClusterPilot-linux-x86_64.AppImage) | No install needed: make it executable and run |
| Linux (Debian, Ubuntu) | [ClusterPilot-linux-amd64.deb](https://github.com/luckypolamreddy/clusterpilot-releases/releases/latest/download/ClusterPilot-linux-amd64.deb) | `sudo apt install ./ClusterPilot-linux-amd64.deb` |
| Linux (Fedora, RHEL, openSUSE) | [ClusterPilot-linux-x86_64.rpm](https://github.com/luckypolamreddy/clusterpilot-releases/releases/latest/download/ClusterPilot-linux-x86_64.rpm) | `sudo dnf install ./ClusterPilot-linux-x86_64.rpm` |

Check your download against [SHA256SUMS.txt](https://github.com/luckypolamreddy/clusterpilot-releases/releases/latest/download/SHA256SUMS.txt):
`sha256sum -c SHA256SUMS.txt --ignore-missing` (Linux/macOS) or `Get-FileHash <file>` (Windows PowerShell).

## All versions

Every version, with its release notes and its own downloads, is on the
[**Releases**](https://github.com/luckypolamreddy/clusterpilot-releases/releases) page.

## First launch

The installers aren't code-signed yet, so the first launch asks you to confirm:
- **Windows:** SmartScreen → *More info* → *Run anyway*.
- **macOS:** right-click the app → *Open* → *Open*.

## Updates

From version 0.8.2, ClusterPilot updates itself. When a new version is out, the app offers *Update now* or *Later*.
Every update is signed and checked before it installs, and your settings and clusters are kept. If you have 0.8.0 or
0.8.1, download the latest version above once; after that, updates arrive in the app.

IT teams that roll out the `.msi` themselves can turn the update check off by setting the environment variable
`CLUSTERPILOT_UPDATES=off`.

## Free and plans

ClusterPilot is free to use, with no account and no time limit, for one cluster (you pick which). Pro comes with a 14-day trial:
in the app, click **Free plan** at the top and choose *Start the 14-day Pro trial*. Plans, prices and the product tour:
[clusterpilot.nprd.cicdorchestrator.com](https://clusterpilot.nprd.cicdorchestrator.com/download)
