## 1.7.0
### Features
* New users can now try the full version of ScreenTray with a free 14-day trial
* Completely redesigned tray menu. It now displays an upload history with a few available actions:
     * open upload
     * copy link to clipboard
     * delete from cloud

<img src="/images/trayMenu.png?raw=true" width="512" height="556">

* Added integration with Firebase Dynamic Links. You can now customize links to screenshots by using your domain (e.g., cloud.yourdomain.com/XXXXXXXXXXXXXXXXX)
* Added the new "Export / Import" section to preferences to make it easy to transfer ScreenTray settings to another computer or share them with your team

<img src="/images/exportImportSection.png?raw=true" width="702" height="578">

### Improvements
* Full macOS Catalina support
* ScreenTray is notarized now, meaning that it was scanned by Apple and checked for malware and other security issues
* Improved error handling. Now you will see dialog boxes with the appropriate explanation if anything goes wrong (e.g., you don't have an internet connection, cloud tokens expired, you don't have sufficient cloud permissions, etc.)
* Added ability to toggle logo visibility right from image editor
* Added ability to select folders from the Google Drive "Shared with me" section
* Improved performance when screenshots are copied to clipboard

### Fixes
* Fixed Google Drive authentication
* Fixed issue when the crop tool worked incorrectly with the "Downscale retina screenshots" option set to true
* Fixed issue when it was possible to draw shapes using mouse buttons other than the left one
* Fixed issue when the Command+X shortcut didn't work

## 1.6.0
### Features
* Tray icon now turns into a progress bar when screenshots are uploaded to the cloud

### Improvements
* Optimized image editor load time (2-3x faster)
* Optimized image editor RAM usage (3-4x less)
* Eliminated noticeable lags when selecting an area of the screen to capture
* Added ability to create public folders in Google shared drives

### Fixes
* Fixed issue when contents of Google shared drives were not displayed
* Fixed issue when notifications were not shown sometimes
* Fixed error when pressing shortcuts before image editor is loaded

## 1.5.0
### Features
* macOS Mojave’s dark mode support
* Introduced additional toolbar in image editor where you can:
     * see screenshot resolution
     * rename screenshots before uploading/saving
     * save screenshots by dragging & dropping them into the destination folder
* Added more options to preferences:
     * control when app plays a sound
     * control when app shows notifications 

### Improvements
* Aligned icons in image editor

### Fixes
* Fixed issue when some buttons in image editor were unclickable
* Fixed issue when saved retina screenshots opened twice as big as their actual size in Preview
* Fixed error when trying to copy/paste text in the save dialog
