# MultibootOS AmiKit Installer — Public Releases

This repository hosts public releases of the **MultibootOS AmiKit Installer**.

## Download

Go to [**Releases**](https://github.com/dcutugno/MultibootOS_AmiKit_Installer_Public/releases) to download the latest version for your platform:

| Platform | File |
|----------|------|
| Windows  | `MultibootOS_AmiKit_Installer-Windows.zip` |
| macOS    | `MultibootOS_AmiKit_Installer-macOS.dmg`   |

## macOS Installation

> **macOS will block the app on first launch** because it is not signed with an Apple Developer certificate.

**Steps to install and open it:**

1. Double-click the DMG to mount it — a Finder window opens showing `MultibootOS_AmiKit_Installer.app` and `READ ME FIRST.txt`
2. Drag `MultibootOS_AmiKit_Installer.app` to your **Applications** folder
3. Eject the DMG
4. **Right-click** `MultibootOS_AmiKit_Installer.app` → **Open** (do NOT double-click on first launch)
5. Click **Open** in the warning dialog that appears

If you see *"Apple cannot verify..."* and there is no Open button:
1. Open **Terminal** and run:
   ```sh
   xattr -dr com.apple.quarantine /Applications/MultibootOS_AmiKit_Installer.app
   ```
2. Or go to **System Settings → Privacy & Security** → scroll down → click **Open Anyway**

## Auto-Update

The installer checks this repository for updates on startup and can update itself automatically.

## Source Code

The private source repository is maintained separately. This repository is used exclusively for distributing release builds.
