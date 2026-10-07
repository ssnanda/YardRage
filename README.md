# Yard Rage for iPhone

Yard Rage is a satirical HOA game from ITSpector LLC: patrol the neighborhood, investigate complaints, photograph evidence, manage residents, survive board politics, and try to keep your seat.

This public repository contains installation files and release notes only. The source code is maintained privately.

Official website: [yardrage.com](https://yardrage.com)

## Install with AltStore

Yard Rage requires iOS 13 or later. Xcode is not required. You need a Mac or Windows PC, an Apple ID, a USB cable for initial setup, and AltStore Classic.

### macOS

1. Download [AltServer for macOS](https://altstore.io/) and copy it to **Applications**.
2. Launch AltServer. Its icon will appear in the macOS menu bar.
3. Connect your unlocked iPhone to the Mac with USB and tap **Trust** on both devices if prompted.
4. In Finder, select the iPhone and enable **Show this iPhone when on Wi-Fi**, then apply the change.
5. From the AltServer menu, choose **Install AltStore**, select the iPhone, and enter the Apple ID AltServer should use for signing.
6. On the iPhone, approve the developer profile under **Settings → General → VPN & Device Management** if prompted.
7. On iOS 16 or later, enable **Settings → Privacy & Security → Developer Mode** and follow the restart prompt.

See AltStore’s official [macOS installation guide](https://faq.altstore.io/altstore-classic/how-to-install-altstore-macos) for current screenshots and troubleshooting.

### Windows

1. Install Apple’s desktop versions of [iTunes](https://www.apple.com/itunes/) and [iCloud for Windows](https://support.apple.com/en-us/103232). AltStore recommends the direct Apple installers rather than the Microsoft Store versions.
2. Download [AltServer for Windows](https://altstore.io/), extract the installer, run `Setup.exe`, and launch AltServer as administrator.
3. Connect your unlocked iPhone to the PC with USB and tap **Trust** on both devices if prompted.
4. Open iTunes, select the iPhone, enable **Sync with this iPhone over Wi-Fi**, and apply the change.
5. From the AltServer taskbar icon, choose **Install AltStore**, select the iPhone, and enter the Apple ID AltServer should use for signing.
6. On the iPhone, approve the developer profile under **Settings → General → VPN & Device Management** if prompted.
7. On iOS 16 or later, enable **Settings → Privacy & Security → Developer Mode** and follow the restart prompt.

See AltStore’s official [Windows installation guide](https://faq.altstore.io/altstore-classic/how-to-install-altstore-windows) for current screenshots and troubleshooting.

### Add the Yard Rage source and install

1. Open AltStore on the iPhone.
2. Open **Sources**, tap **+**, and add this URL:

   ```text
   https://raw.githubusercontent.com/ssnanda/YardRage/main/altstore.json
   ```

3. Open the Yard Rage listing and tap **Install**.
4. Keep AltServer running and the computer and iPhone on the same network when AltStore needs to install or refresh the app.

### Install the IPA manually

1. Download `yardrage.ipa` from the [latest Yard Rage release](https://github.com/ssnanda/YardRage/releases/latest).
2. Open AltStore and select **My Apps**.
3. Tap **+** and select the downloaded `yardrage.ipa`.
4. Keep AltServer available while AltStore signs and installs the app.

## Releases

Each GitHub release contains an immutable, versioned Yard Rage IPA. Release downloads and the AltStore source are public; the game source code is not included.

Yard Rage is developed by ITSpector LLC in North Carolina, USA.
