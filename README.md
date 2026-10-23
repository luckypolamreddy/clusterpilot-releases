# ClusterPilot

The AI agent that finds why your Kubernetes clusters break, fixes it safely, and proves it worked.
These are the installers for the ClusterPilot desktop app.

## Download the latest version

| System | Download | Notes |
| --- | --- | --- |
| **Windows** 10 and 11 (64-bit) | [ClusterPilot-windows-x64-setup.exe](https://github.com/luckypolamreddy/clusterpilot-releases/releases/latest/download/ClusterPilot-windows-x64-setup.exe) | Installer, no admin rights needed |
| Windows (IT deployment) | [ClusterPilot-windows-x64.msi](https://github.com/luckypolamreddy/clusterpilot-releases/releases/latest/download/ClusterPilot-windows-x64.msi) | For Intune or Group Policy |
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

## Trial and plans

Every installation includes 14 days of every feature. Plans, prices and the product tour:
[clusterpilot.nprd.cicdorchestrator.com](https://clusterpilot.nprd.cicdorchestrator.com/download)
