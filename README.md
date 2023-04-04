# FIX Log Viewer
[![Download](https://img.shields.io/badge/Download-1.2.0-blue.svg)](https://github.com/apptastic-software/fix-log-viewer/releases/latest) 

FIX Log Viewer is a tool for viewing FIX engine logs in a much more readable format. It helps you find, analyze, and fix issues faster.

Available for Windows, Linux and MacOS.

[View demo](#demo)
 
![FIX Log Viewer draw selection](/assets/screenshot1.png)

## Features
### Protocol
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
* Read compressed log files (zip, gz, 7z, bz2, lz4, xz, and lzma)
* Support for tailing FIX log file and displays FIX messages in realtime
* Support for reading FIX log file on a remote machine and displays new FIX messages in real-time

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
Changes to the security model used in the latest versions of **MacOS 11 (Big Sur)**, **MacOS 12 (Monterey)**, and **MacOS 13 (Ventura)** mean that the operating system will show an error message ('"FIX Log Viewer" is damaged and can’t be opened. You should move it to the Bin.') when trying to start the application. To work around this, run the following command on the downloaded dmg file in a terminal **before** installing:

`sudo xattr -d com.apple.quarantine FIX.Log.Viewer-<version>_<arch>.dmg`

Alternatively download the app from command line with `wget` or `curl` instead of from a web browser. The web browser will flag `.dmg` file as suspicious if it does not have the correct signature. This flag is removed with the above `xattr` command.

I you still see the error message manually remove the app and install it again.

![MacOS warning](/assets/macos-warning2.png)

## Demo
![FIX Log Viewer draw selection](/assets/screenshot2.gif)

Keywords: 
FIX Parser
FIX Analyser
FIX Protocol Analyzer
FIX Protocol Log Reader

[1]: https://github.com/apptastic-software/fix-log-viewer/releases/latest
