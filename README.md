# WinLook Plugins

WinLook is a Windows control center that opens from the pill at the top of your screen. Browse the [latest plugin release](https://github.com/Taikutsu-Lyrz/WinLook-Plugins/releases/latest) from WinLook without a GitHub account.

## Manage plugins in WinLook

1. Install and open WinLook for Windows. Click the pill at the top of the screen, choose **All settings**, then **Plugins**.
2. Open a plugin to see its settings and available downloads.
3. Use **Enable**, **Disable**, or **Remove plugin**. To restore a bundled component, choose **Install bundled plugin**. This works offline.

## LanDrop

Send and receive files through the pill with nearby LanDrop, LocalSend, and compatible Android Quick Share devices.

- To send, drop a file onto the pill and pick a device. On Android, open **Quick Share → Receive** so WinLook can find the phone.
- To receive, enable the LanDrop tile in WinLook. Review the incoming offer in the pill and select **Accept**. When it finishes, select **Open file location**.
- To reinstall the helper, open **Plugins → LanDrop** and choose **Download and reinstall**. To install offline, download **LanDrop-WinLook-Plugin_x64.zip** from the latest release and select **Install from file…** in WinLook. Select the ZIP directly. It includes the Quick Share runtime.

## Desktop Lyrics

Show timed lyrics on the desktop while music plays. Choose a style, animation, monitor, placement, text size, and timing offset.

1. Open **Plugins → Desktop Lyrics** in WinLook and enable the bundled component.
2. Turn on **Show desktop lyrics**. Enable **Online lookup** or import an existing `.lrc` or `.ttml` file for the current song.
3. Use **Placement → Arrange** to drag, resize, or snap the lyrics on the selected monitor.

Desktop Lyrics installs through the WinLook setup and can be restored from its plugin page.

## Chrome Companion

Adds YouTube and YouTube Music metadata and playback controls to WinLook.

1. Open **Plugins → Chrome companion** and choose **Open extension folder**. Or download **WinLook-Chrome-Companion.zip** from the latest release and extract it.
2. In Chrome, open `chrome://extensions`, enable **Developer mode**, and select **Load unpacked**. Choose the folder containing `manifest.json`.
3. In **Plugins → Chrome companion**, select **Copy pairing key** and paste it into the extension options.

## File Converter

Convert files locally by dropping them onto the WinLook pill. The optional converter uses [Filee by Myeonggu Kim (KnifeLemon) and contributors](https://github.com/KnifeLemon/Filee).

1. Open **Plugins → File Converter** in a WinLook build that includes the integration.
2. Choose **Download Filee** to get the separate Windows installer or **Locate Filee…** to select `filee-cli.exe` from the official portable download.
3. Under **File drop**, choose **Ask every time**, **Left to share, right to convert**, **Share only**, or **Convert only**.
4. Drop files onto the pill, select an output format and folder, and start the conversion. WinLook preserves the originals.

## Release files

Each release provides a catalog manifest and the downloadable ZIPs. WinLook verifies their size and SHA-256 checksum. The LanDrop release also includes its matching helper source. The Quick Share runtime uses [MultiDrop](https://github.com/digitaldanis/multidrop) under GPL-3.0-or-later.

File Converter is listed in `plugins.json` with `provider: "filee"`. WinLook resolves the Windows installer from [Filee’s official releases](https://github.com/KnifeLemon/Filee/releases).

