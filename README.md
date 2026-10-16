<p align="center">
  <img src="assets/logo.svg" alt="Rain-Crosshair" width="110">
</p>

<h1 align="center">Rain-Crosshair</h1>

<p align="center">
  <strong>Your crosshair. Your style.</strong><br>
  Create your own crosshair, save your favorite designs, and switch between them while you play.
</p>

<p align="center">
  <a href="https://github.com/AslamChahban/rain-crosshair/releases/latest"><strong>Download for Windows</strong></a>
  &nbsp; · &nbsp;
  <a href="#getting-started">Getting started</a>
  &nbsp; · &nbsp;
  <a href="#troubleshooting">Troubleshooting</a>
  &nbsp; · &nbsp;
  <a href="https://github.com/AslamChahban/rain-crosshair/issues">Report a problem</a>
</p>

<p align="center">
  Windows 10 &amp; 11 · Custom profiles · Keyboard shortcuts · Multiple monitors
</p>

---

## Make it yours

Rain-Crosshair places a customizable crosshair over your screen. Clicks pass straight through the overlay, so you can keep playing normally.

Design your crosshair with a live preview, save it as a profile, and let the app run quietly in your system tray.

| Feature | What you can do |
| --- | --- |
| **Crosshair designer** | Customize colors, line lengths, thickness, gap, opacity, outlines, dots, rings, and rotation. |
| **Presets and profiles** | Start with a preset, create your own designs, and favorite the ones you use most. |
| **Keyboard shortcuts** | Toggle the overlay, cycle profiles, or switch directly to a specific crosshair. |
| **Game profiles** | Automatically switch crosshairs when a configured game is focused. |
| **Game-only mode** | Hide the overlay outside the games you configure. |
| **Monitor and calibration controls** | Choose your display and fine-tune your crosshair's position. |
| **Sharing and backups** | Share a design using a code, or back up your profiles and settings together. |
| **Recovery tools** | Recover unfinished edits and restore recently deleted profiles. |

## Getting started

1. Open the **[latest release](https://github.com/AslamChahban/rain-crosshair/releases/latest)**.
2. Under **Assets**, download the **Rain-Crosshair-Setup** installer—not the “Source code” ZIP.
3. Run the installer and open **Rain-Crosshair**.
4. Choose a preset or create a crosshair in **Designer**.
5. Adjust it to your liking, then press **Save**.
6. Run your game in **Borderless** or **Windowed Fullscreen** mode.

**Download safely:** use the official release page linked above. If Windows displays a security warning, check the file and its publisher before continuing. Do not disable your antivirus to install the app.

## Keyboard shortcuts

| Action | Default shortcut |
| --- | --- |
| Show or hide the crosshair | `F6` |
| Next profile | `F7` |
| Previous profile | `F8` |
| Open or hide the app window | `Ctrl + F6` |
| Save your edits in the app | `Ctrl + S` |

Change shortcuts on the **Shortcuts** page. Click **Set shortcut**, press your preferred keys, and save.

You can also assign a shortcut directly to a saved profile.

## Set up your games

1. Open **Game profiles**.
2. Click **Browse / shortcut** to choose a game executable or desktop shortcut.
3. Alternatively, launch your game and select it from **Running apps**.
4. Choose the crosshair profile you want and click **Add rule**.
5. Enable **Automatic profile switching**.

Steam shortcuts may show several executable candidates. Choose the game itself, not its launcher or a helper program. If you are unsure, use **Running apps** while the game is open.

Enable **Hide outside your games** to show the overlay only while a configured game is focused.

> Automatic switching pauses while you have unfinished edits. Save or discard those edits to resume switching.

## Keep it running in the background

By default, closing the editor keeps Rain-Crosshair running in the system tray. Your overlay and global shortcuts stay available.

To exit completely, right-click the tray icon and choose **Quit Rain-Crosshair**.

You can change startup and tray preferences in **Settings**, including launching with Windows and starting minimized.

## Share your crosshair

Click **Share** to generate a code beginning with `RAIN1:`. Copy the code and send it to a friend.

To import a design:

1. Open **Settings → Share / Import**.
2. Paste the crosshair code.
3. Click **Import code**.

## Back up and recover

Use **Settings → Backup & restore → Export everything** to save your profiles and settings in one file.

Keep that file somewhere safe. Restoring a backup replaces your current profiles and settings after confirmation.

Made a mistake?

- **Unfinished edits:** choose **Restore draft** when a recovery banner appears after reopening the app.
- **Deleted profile:** click **Undo delete** or open **Settings → Recently deleted**.

## Game compatibility

Rain-Crosshair is a separate screen overlay. It does not inject code into games, read game memory, modify game files, or change recoil or weapon accuracy.

For compatibility, use **Borderless** or **Windowed Fullscreen**. Exclusive fullscreen and some protected screens can prevent the overlay from appearing.

Each game sets its own rules for third-party overlays. Check those rules before using Rain-Crosshair, especially in competitive play.

## Updates

Rain-Crosshair periodically checks for new releases and shows a notification when an update is available.

To update:

1. Open the release page from the notification.
2. Download the new installer.
3. Quit Rain-Crosshair completely.
4. Run the installer.

You can also check manually in **Settings → Updates** or visit the **[latest release](https://github.com/AslamChahban/rain-crosshair/releases/latest)**.

## Troubleshooting

<details>
<summary><strong>The crosshair is not showing in my game</strong></summary>

- Make sure the overlay is enabled. Press `F6` if you use the default shortcut.
- Switch the game to **Borderless** or **Windowed Fullscreen**.
- Check that the correct monitor is selected in **Display**.
- If **Hide outside your games** is enabled, make sure the game has a matching rule and is focused.

</details>

<details>
<summary><strong>I cannot find my game when browsing</strong></summary>

Use **Browse / shortcut** to select its desktop shortcut, including Steam `.url` shortcuts.

If the shortcut opens a launcher or cannot be resolved, launch the game normally, click **Running apps**, and refresh the list.

</details>

<details>
<summary><strong>A keyboard shortcut does not work</strong></summary>

Windows or another app may already be using that combination.

Open **Shortcuts**, check its status, choose another combination, and save. Rain-Crosshair must remain running for global shortcuts to work.

</details>

<details>
<summary><strong>The crosshair is not centered where I want it</strong></summary>

The crosshair is centered on your selected monitor, not on an individual game window.

Check your display selection, then use **Calibration** to adjust its position. Click **Reset center** to remove the position offsets, then save the profile.

</details>

<details>
<summary><strong>The overlay flickers or looks wrong</strong></summary>

Try enabling hardware acceleration:

1. Quit Rain-Crosshair completely.
2. Right-click its Windows shortcut and open **Properties**.
3. At the end of **Target**, add a space followed by `--enable-gpu`.
4. If the executable path has quotation marks, add the option after the closing quotation mark.
5. Apply the change and reopen the app using that shortcut.

Remove the added option if it does not help.

</details>

<details>
<summary><strong>I lost an edit or deleted a profile</strong></summary>

If a recovery banner appears when you reopen the app, choose **Restore draft**.

To recover a deleted profile, use **Undo delete** or open **Settings → Recently deleted**.

</details>

## Need help?

**[Report a problem](https://github.com/AslamChahban/rain-crosshair/issues)** and include:

- Your Rain-Crosshair version.
- Your Windows version.
- The game affected.
- What happened and how to reproduce it.
- A screenshot, if helpful.

You can also export a report from **Diagnostics**. Review it before sharing.

## License

Rain-Crosshair is available under the [MIT License](LICENSE).
