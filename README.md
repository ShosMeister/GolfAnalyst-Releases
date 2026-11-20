# Golf Analyst

Free golf scores, handicap and statistics for one golfer, on Windows, Mac and Linux.

**[⬇ Download the latest version](https://github.com/ShosMeister/GolfAnalyst-Releases/releases/latest)**

## What it is

Golf Analyst keeps your golf scores and works out your Handicap Index the way the World Handicap System does. It shows
your statistics course by course, your best rounds, how you play every hole, and it prints a handicap report, a log of
your rounds and a scorecard to take with you. Angelo Mileto first wrote it in 1991 on the Mac; this is the new Java
version.

## Which file to get

Open the [latest release](https://github.com/ShosMeister/GolfAnalyst-Releases/releases/latest) and look under
**Assets**:

- **Windows:** `GolfAnalyst_vX.Y.Z.exe`, the installer. It brings its own Java, so there is nothing else to install.
- **Mac with an Apple chip** (M1 or newer: Apple menu, About This Mac, "Chip"): `GolfAnalyst_vX.Y.Z-mac-arm64.dmg`,
  the Mac installer. It brings its own Java too.
- **Mac with an Intel processor, and Linux:** `GolfAnalyst_vX.Y.Z.zip`, the "runs anywhere" copy. It needs Java 17 or
  newer. (It also runs on Windows and on any Mac with the computer's own Java.)
- `README.txt` says how to install it, where your data lives, and what to do if something goes wrong.

### Installing it on Windows

1. Double-click `GolfAnalyst_vX.Y.Z.exe`. If you have an earlier copy installed, this one replaces it; your data is
   kept.
2. Windows may say **"Windows protected your PC"**, because the program is not signed yet. Click **More info**, then
   **Run anyway**.
3. Read the credits, click Next, and choose whether you would like a shortcut on your desktop. No administrator
   password is needed: it installs just for you.
4. Start it from the Start menu: **Golf Analyst**.

### Installing it on a Mac with an Apple chip

1. Double-click `GolfAnalyst_vX.Y.Z-mac-arm64.dmg`. In the window that opens, drag **Golf Analyst** onto
   **Applications**. If you have an earlier copy, choose Replace; your data is kept.
2. Double-click Golf Analyst in Applications. The first time, because the program is not yet signed by Apple, macOS
   stops it: **"Golf Analyst.app" Not Opened** — *Apple could not verify "Golf Analyst.app" is free of malware that
   may harm your Mac or compromise your privacy.* Click **Done**, the lower button (not the blue **Move to Trash**,
   which is what Return presses).
3. Open **System Settings**, click **Privacy & Security** and scroll down to **Security**. It says *"Golf
   Analyst.app" was blocked to protect your Mac.* Click **Open Anyway** beside it.
4. macOS asks **Open "Golf Analyst.app"?** — *Apple is not able to verify that it is free from malware that could harm
   your Mac or compromise your privacy. Don't open this unless you are certain it is from a trustworthy source.* Click
   **Open Anyway**, the middle button (again, not the blue Move to Trash).
5. A **Privacy & Security** window asks for *an administrator's username and password to allow this*. Type them and
   click **OK**. (On a standard account, someone with an administrator account types theirs.) Golf Analyst opens, and
   from then on it opens with a double-click.

Control-clicking the program and choosing Open no longer gets past this on recent versions of macOS; use Open Anyway
as above. To uninstall, drag Golf Analyst from Applications to the Trash: your data is kept.

### Mac with an Intel processor, and Linux

1. Check your Java: open a terminal and type `java -version`. If it is missing or older than 17, install it free from
   [adoptium.net](https://adoptium.net) (the latest LTS version).
2. Unzip the whole folder somewhere you like, such as your home folder. Keep the files together.
3. Open a terminal in that folder and type `sh run.sh`. (On Windows, double-click `run.bat` instead.)
4. To update later, replace the folder with the new one. Your data is never inside it.

## Your data

The program starts with made-up sample data, so there is something to look at straight away. When you press New Round
or New Course it first offers to make your own data folder, Documents\Golf Analyst (Documents/Golf Analyst on a Mac or
Linux). Your rounds, courses and settings all live there, with the backups the program makes for you. Uninstalling
Golf Analyst, or deleting the unzipped folder, never removes it.

To use the same data on two computers, keep the data folder in a cloud folder and point both copies at it (Settings,
Change...). Close the program when you finish, wait for the cloud to say it is up to date before opening it on the
other computer, and save nothing if the cloud reports a conflict. Help, on the Home screen, says more under "Sharing
your data between computers".

To hear about new versions, tick **Tell me when a new version is available** in Settings: it only tells you, and never
downloads or installs anything.

## About the Handicap Index

Golf Analyst calculates your Handicap Index using the World Handicap System formulas published by the USGA. It is an
independent program, not affiliated with or endorsed by the USGA, and it is not an authorized handicap service, so
clubs and tournaments that require an official index will want one issued through a golf association or club.

## If something goes wrong

- Write down what you were doing just before it happened.
- Take a screenshot (on Windows press Windows + Shift + S; on a Mac, Shift + Command + 4).
- Look at the bar along the bottom of the window: it says what the program is doing, and it says so when a data file
  could not be read.
- Tell Angelo about it under [Issues](https://github.com/ShosMeister/GolfAnalyst-Releases/issues) on this page: press
  **New issue**, say what you were doing, and attach the screenshot. Issues are public, so please leave out anything
  private. Every bit helps.

## The source code

Golf Analyst is free to download and use. Its source code is not published: this page holds only the downloads, the
release notes and this README. Golf Analyst is provided as is, without any warranty.

## Credits

Background photographs courtesy of On The Green Magazine
([www.onthegreenmagazine.com](https://www.onthegreenmagazine.com)), used with permission.

ZIP code data from GeoNames ([www.geonames.org](https://www.geonames.org)), used under a Creative Commons Attribution
license. The data is provided as is.

Have fun, and good golfing!
