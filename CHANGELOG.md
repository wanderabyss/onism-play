# Changelog

User-facing release notes for Onism Play. Downloads: https://play.onism.ai/download/

## 2.14.1 - November 12, 2026

Clearer Homebrew setup for Engine 2.0.

- **IMPROVED: Homebrew install steps in setup.** When Engine 2.0 needs Homebrew packages and Homebrew is missing, setup now shows the steps, the official install command, an Open Terminal button and a link to the install guide on the website. Check again continues the build.
- **IMPROVED: Smaller Play pill.** The Play pill in the app's header is smaller.

## 2.14.0 - November 12, 2026

One step to stop the macOS firewall pop-ups.

- **NEW: Allow Wine through the firewall.** macOS kept asking whether Wine's helper programs may accept incoming connections. A new Allow Wine button in Settings and setup adds them to the firewall's allowed list with one administrator prompt. The firewall stays on, and a program Wine has not run before can still ask once.

## 2.13.1 - November 12, 2026

Fixes for launching and ending Steam games.

- **FIXED: Games set to a missing engine now launch.** A game pinned to an engine that is no longer installed used to fail to start. Onism Play now uses another engine and tells you.
- **FIXED: Steam sessions end properly.** A Steam game no longer shows Playing when only Steam is open, and its session ends when the game or Steam quits.
- **IMPROVED: Open Steam goes to the game.** Open Steam on a game, and Play, now show that game's page in the Steam library. Launch errors also show their real message.

## 2.13.0 - November 12, 2026

Steam handles its own games, and setup explains engines and the Apple toolkit.

- **NEW: Steam installs and deletes in Steam.** Steam games show Open Steam instead of Install and Uninstall. Download in the Steam client and the game appears in your library. The Steam page has one Open Steam / Close Steam button.
- **IMPROVED: Clearer first-run setup.** Setup offers Epic Games and GOG, confirms when you are signed in, and explains Engine 1.0 (DirectX 9–11) and Engine 2.0 (DirectX 12) with Apple's Game Porting Toolkit, so you choose which to download first.
- **FIXED: Clear message when updates cannot install.** Run from a disk image or Downloads, Onism Play now tells you to move it to Applications instead of failing to update.

## 2.12.0 - November 11, 2026

A readability fix and clearer credit for CrossOver.

- **FIXED: Readable Continue playing card.** The Continue playing card on the Activity page stays readable on artwork that has its own logo or banner.
- **IMPROVED: CrossOver credit.** Credits now name CodeWeavers' open-source CrossOver Wine, the source Engine 2.0 is built from.

## 2.11.0 - November 11, 2026

Onism Play can now update itself.

- **NEW: Automatic updates.** The app asks the first time you open it whether to check for updates, and you can change that any time in Settings.
- **NEW: Installs that wait for your game.** Updates install when you quit the app and wait for a running game.
- **NEW: Check for Updates….** Available in the app menu and in Settings, with the time of your last check.

## 2.10.0 - November 11, 2026

A new Activity page and achievements that sync on their own.

- **NEW: Activity, rebuilt.** Hours with a trend, your streak and best day, a calendar and a when-you-play heatmap, and one row per game.
- **NEW: Achievements sync in the background.** Every Steam, GOG and Epic game updates by itself, with rarity labels and the games closest to finished.
- **IMPROVED: Save backups in the Library.** Save backups moved from Activity to a button in the Library header.

## 2.9.0 - November 11, 2026

Controller test sheet, per-game pads and a quieter Play page.

- **FIXED: Test Vibration vibrates.** The test now plays a real buzz, and you can test the left and right motors separately.
- **NEW: Smarter controller test sheet.** Button names follow your pad, sticks are checked for drift, and DualSense pads get a light bar colour picker.
- **NEW: Per-game pad choices.** Hide a pad from one game (experimental). A game's PlayStation mode is now remembered after a restart.

## 2.8.1 - November 10, 2026

The audio monitor knows which headset head tracking follows.

- **FIXED: No false headset mismatch.** A renamed or look-alike headset no longer shows a false or missed mismatch in the monitor.

## 2.8.0 - November 10, 2026

PHASE audio monitor, in-game overlay and automatic engine link.

- **NEW: Audio monitor.** A menu-bar popover shows whether PHASE is rendering, the speaker layout, per-channel levels and head direction.
- **NEW: In-game overlay.** A click-through overlay toggled with ctrl-cmd-A, placed in a corner or dragged anywhere.
- **NEW: Restore original audio.** Put an engine's audio back to how it was from Tune → Engines.

## 2.1.0 - November 6, 2026

Surround sound on headphones, with AirPods head tracking.

- **NEW: PHASE surround.** Choose Off, PHASE Surround or Head-tracked Surround per game, in Tune and in TV Mode. It needs a PHASE-enabled engine.
- **NEW: AirPods head tracking.** Live status, plus recenter controls that stay available during play. Motion data never leaves your Mac.
- **FIXED: No freeze when switching games.** Cloud-save details now load in the background, and a running game is recovered if you reopen the app.

## 2.0.0 - November 5, 2026

A redesign: new Play page, floating sidebar and TV Mode.

- **NEW: TV Mode.** A full-screen mode for keyboard or controller, with its own library, game details and per-game Tune.
- **NEW: New Play page and sidebar.** A full-width hero, landscape shelves and a floating sidebar. Game Tune, Engines and Controllers each get their own page.
- **IMPROVED: Needs attention.** The library lists installed games with a known problem and says why.

## 1.29.0 - November 4, 2026

Hide a store you don't use.

- **NEW: Hide store.** Every store page has a Hide store button. Hidden stores come back from the bottom of the Stores page, and their games stay in your library.

## 1.28.0 - November 4, 2026

The whole hero image, and a shortcut to minimize your game.

- **NEW: Minimize game shortcut.** Press ctrl-cmd-M to hide the running game and return to Onism Play, and again to bring it back. You can change it in Settings.
- **FIXED: Hero image no longer cropped.** The Play banner follows the art's own shape, so the top and bottom of the picture show.

## 1.27.6 - November 4, 2026

The EA app runs on the Apple graphics engine.

- **IMPROVED: EA app on D3DMetal or DXMT.** Like Ubisoft Connect, the EA app now uses an engine with D3DMetal or DXMT, so DirectX 12 games started from it can run.

## 1.27.5 - November 4, 2026

Clearer EA and Ubisoft pages.

- **IMPROVED: Account first.** Launcher store pages show the account state and main action first, with a neutral note instead of a warning about how these stores work.
- **IMPROVED: Set up engine.** On an install with no Wine engine yet, the main button says Set up engine instead of an Install button that fails.

## 1.27.2 - November 4, 2026

Your EA games, not just installed ones.

- **NEW: Owned EA games.** Sync library on the EA app page now lists the games your EA account owns. Install opens the EA app.
- **IMPROVED: Ubisoft install uses the right engine.** Ubisoft's Install now starts the launcher on the same engine as its games.

## 1.27.0 - November 4, 2026

Your Ubisoft Connect library, and Install from Onism Play.

- **NEW: Owned Ubisoft games.** Sync library now lists every Ubisoft Connect game you own, not just installed ones.
- **NEW: Install from Onism Play.** Install opens the game's install in the launcher. Finish there, then sync again.

## 1.26.1 - November 4, 2026

Open launcher no longer looks dead.

- **FIXED: Stuck launcher restarts.** Open launcher on Ubisoft Connect or the EA app now restarts a launcher that is already running.
- **FIXED: No blank Ubisoft window.** Ubisoft Connect now starts with the same rendering switches as the EA app, so its login page draws.

## 1.26.0 - November 4, 2026

Ubisoft Connect and the EA app.

- **NEW: Two new stores.** Ubisoft Connect and the EA app appear on the Stores page, in the library filter and in the environment list, each with its own bottle.
- **NEW: Install and sync.** Each store page installs the launcher, opens it to sign in and syncs the games you install through it.

## 1.25.0 - November 4, 2026

A calmer Play screen.

- **IMPROVED: Full-width shelves.** Recently played and Installed stack at full width, with evenly sized posters and quieter section headers.
- **FIXED: Readable in dark mode.** The glow behind bright artwork is fainter, so text over it meets the 4.5:1 contrast target.

## 1.23.0 - November 4, 2026

Themes, engine builds from the app, and a more tactile Play screen.

- **NEW: Color themes.** Pick Cream, Midnight, Graphite or Theater in Settings, plus a Light, Dark or System toggle in the toolbar.
- **NEW: Build engines from the app.** Build Engine now works from the installed app, and the Engines page has an Apple Game Porting Toolkit card.

## 1.22.0 - November 4, 2026

The onismplay command ships inside the app.

- **NEW: Command line tool.** Install the onismplay command from Settings. If the app moves, Settings says so and Reinstall repairs the link.

## 1.21.0 - November 4, 2026

About credits every third-party component.

- **NEW: Credits and licenses.** The About window lists the software Onism Play is built on, with licenses and links. View licenses opens the full notices.

## 1.20.0 - November 4, 2026

Fully renamed.

- **IMPROVED: One name everywhere.** The app, command-line tool, data folder and packaging all use the Onism Play name. Your library, saves, bottles and engines move over on first launch.

