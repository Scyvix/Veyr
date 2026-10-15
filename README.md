# Veyr

Veyr is a Windows browser with WebView2, top and side tabs, a collapsible sidebar, scenic start pages, light/dark themes, favourites, Opera import and downloads.

## Install

[Download Veyr Setup](https://github.com/Scyvix/Veyr/releases/latest/download/Scyvix.Veyr-win-x64-Setup.exe), close any older Veyr version, and run the installer once. Open Veyr from the Windows Start menu afterward. Visual Studio is not needed.

The installer is not code-signed yet, so Windows may identify its publisher as unknown.

## Automatic updates

Veyr checks for published updates when it opens and every four hours while running. Verified updates download in the background and apply when you next launch Veyr. It will not force a restart while you browse. You can also check for updates or choose Restart to update in Settings.

Updates reach the app after a new release is built and published here. Existing plain ZIP editions need a one-time switch to Setup or the self-updating portable edition.

Your browsing data remains under `%LOCALAPPDATA%\Veyr`, separate from the installation files. Close an older Veyr instance before opening a new version.

## Portable edition

The [self-updating portable ZIP](https://github.com/Scyvix/Veyr/releases/latest/download/Scyvix.Veyr-win-x64-Portable.zip) is also available. Extract the complete ZIP and run the outer `Veyr.exe` launcher. Keep its files and folders together.

This repository contains public downloads, update metadata and release notes. Application source is maintained separately. Browser profiles, bookmarks, credentials, source backups and signing/authentication secrets are not published here.
