# FIX Log Viewer
[![Download](https://img.shields.io/badge/Download-1.0.0-blue.svg)](https://github.com/apptastic-software/fix-log-viewer/releases/latest) 

FIX Log Viewer is a cross-platform tool for viewing FIX engine logs in a much more readable format. This helps you find, analyze, and fix issues faster.

Available for Windows, Linux and MacOS.
 
![FIX Log Viewer draw selection](/assets/screenshot1.png)

## Features
### Protocols
* FIXT 1.1
* FIX 5.0 SP2
* FIX 5.0 SP1
* FIX 5.0
* FIX 4.4
* FIX 4.3
* FIX 4.2
* FIX 4.1
* FIX 4.0

### Reading FIX messages from log file
* Extracts raw FIX messages from file of any format. It is enough to have non-encoded messages stored in a file

### Searching for data
* Search for exact phrase ("35=D")
* Search with regular expression
* Case sensitive and case-insensitive search

### Filters
* Create filters to show only specific messages e.g. only messages related to trade or only session level messages, etc.
* Quick message filter
* Advanced field filter
* Time filter
* Enable/disable files

### Interoperability
* Ability to select multiple messages
* Ability to select multiple cells in a grid
* Copy & Paste

### Usability
* Rich and powerful GUI
* Sorting
* Show/Hide columns
* Go to line/message
* Coloring and conditional formatting
* Resolves currency codes, MIC codes, and LEI codes



## Installation

[![Windows](/assets/windows.png)](https://github.com/apptastic-software/fix-log-viewer/releases/latest) [![Linux](/assets/linux.png)](https://github.com/apptastic-software/fix-log-viewer/releases/latest) [![Mac](/assets/mac.png)](https://github.com/apptastic-software/fix-log-viewer/releases/latest)

Download the installer for Windows, Linux and MacOS from [Releases][1].

### Note for MacOS users
Changes to the security model used in the latest versions of **MacOS 10.14 (Mojave)** and **10.15 (Catalina)** mean that the operating system will show an error message ('"FIX Log Viewer" is damaged and can’t be opened. You should move it to the Bin.') when trying to install the application. To work around this, run the following command in a terminal before installing:

`sudo xattr -rd com.apple.quarantine /Applications/FIX\ Log\ Viewer.app`
![MacOS warning](/assets/macos-warning.png)

## Demo
![FIX Log Viewer draw selection](/assets/screenshot2.gif)

[1]: https://github.com/apptastic-software/fix-log-viewer/releases/latest