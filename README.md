# MultibootOS AmiKit Installer — Public Releases

This repository hosts public releases of the **MultibootOS AmiKit Installer**.

## Download

Go to [**Releases**](https://github.com/dcutugno/MultibootOS_AmiKit_Installer_Public/releases) to download the latest version for your platform:

| Platform | File |
|----------|------|
| Windows  | `MultibootOS_AmiKit_Installer-Windows.zip` |
| macOS    | `MultibootOS_AmiKit_Installer-macOS.zip`   |

## macOS Installation

> **macOS will block the app on first launch** because it is not signed with an Apple Developer certificate.

**Steps to open it:**

1. Extract the ZIP — you will find `MultibootOS_AmiKit_Installer.app` and `READ ME FIRST.txt`
2. **Right-click** `MultibootOS_AmiKit_Installer.app` → **Open** (do NOT double-click)
3. Click **Open** in the warning dialog that appears

If you see *"Apple cannot verify..."* and there is no Open button:
1. Open **Terminal** and run:
   ```sh
   xattr -dr com.apple.quarantine /path/to/MultibootOS_AmiKit_Installer.app
   ```
2. Or go to **System Settings → Privacy & Security** → scroll down → click **Open Anyway**

## Auto-Update

The installer checks this repository for updates on startup and can update itself automatically.

## Source Code

The private source repository is maintained separately. This repository is used exclusively for distributing release builds.
