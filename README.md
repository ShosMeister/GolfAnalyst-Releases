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

- **Windows:** `GolfAnalyst_vX.XX.exe`, the installer. It brings its own Java, so there is nothing else to install.
- **Mac and Linux:** `GolfAnalyst_vX.XX.zip`, the "runs anywhere" copy. It needs Java 17 or newer. (It also runs on
  Windows with the computer's own Java.)
- `README.txt` says how to install it, where your data lives, and what to do if something goes wrong.

### Installing it on Windows

1. Double-click `GolfAnalyst_vX.XX.exe`. If you have an earlier copy installed, this one replaces it; your data is
   kept.
2. Windows may say **"Windows protected your PC"**, because the program is not signed yet. Click **More info**, then
   **Run anyway**.
3. Read the credits, click Next, and choose whether you would like a shortcut on your desktop. No administrator
   password is needed: it installs just for you.
4. Start it from the Start menu: **Golf Analyst**.

### Mac and Linux

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
