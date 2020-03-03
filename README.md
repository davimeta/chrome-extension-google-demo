# chrome-extension-google-demo

google官网[chrome.com](https://developer.chrome.com/extensions/samples)提供的示例研究

更新同步日期:2020-03-03

## [My Bookmarks](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/My%20Bookmarks.zip)

A browser action with a popup dump of all bookmarks, including search, add, edit and delete.

CALLS:

``` list
bookmarks.create
bookmarks.getTree
bookmarks.remove
bookmarks.update
tabs.create
```

SOURCE FILES:

``` list
icon.png
manifest.json
popup.html
popup.js
```

## [Page Redder](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/Page%20Redder.zip)

Make the current page red

CALLS:

``` list
browserAction.onClicked
tabs.executeScript
```

SOURCE FILES:

``` list
background.js
manifest.json
```

## [Print this page](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/Print%20this%20page.zip)

Adds a print button to the browser.

CALLS:

``` list
browserAction.onClicked
tabs.executeScript
```

SOURCE FILES:

``` list
background.js
manifest.json
print_16x16.png
```

## [A browser action which changes its icon when clicked](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/A%20browser%20action%20which%20changes%20its%20icon%20when%20clicked.zip)

Click browser action icon to change color!

CALLS:

``` list
browserAction.onClicked
browserAction.setIcon
runtime.onInstalled
storage.StorageArea.get
storage.StorageArea.set
```

SOURCE FILES:

``` list
background.js
icon1.png
icon2.png
icon3.png
icon4.png
icon5.png
manifest.json
```

## [A browser action with a popup that changes the page color](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/A%20browser%20action%20with%20a%20popup%20that%20changes%20the%20page%20color.zip)

Change the current page color

CALLS:

``` list
tabs.executeScript
```

SOURCE FILES:

``` list
icon.png
manifest.json
popup.html
popup.js
```

## [BrowsingData API: Basics](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/BrowsingData%20API:%20Basics.zip)

A trivial usage example.

CALLS:

``` list
browsingData.remove
```

SOURCE FILES:

``` list
icon.png
manifest.json
popup.css
popup.html
popup.js
```

## [Sample Extension Commands extension](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/Sample%20Extension%20Commands%20extension.zip)

Press Ctrl+Shift+F to open the browser action popup, press Ctrl+Shift+Y to send an event.

CALLS:

``` list
commands.onCommand
```

SOURCE FILES:

``` list
background.js
browser_action.html
manifest.json
```

## [Content settings](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/Content%20settings.zip)

Shows the content settings for the current site.

CALLS:

``` list
contentSettings.ContentSetting.get
contentSettings.ContentSetting.set
tabs.query
```

SOURCE FILES:

``` list
contentSettings.png
manifest.json
popup.html
popup.js
```

## [Context Menus Sample](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/Context%20Menus%20Sample.zip)

Shows some of the features of the Context Menus API

CALLS:

``` list
contextMenus.create
extension.lastError
```

SOURCE FILES:

``` list
manifest.json
sample.js
```

## [Context Menus Sample (with Event Page)](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/Context%20Menus%20Sample%20\(with%20Event%20Page\).zip)

Shows some of the features of the Context Menus API using an event page

CALLS:

``` list
contextMenus.create
contextMenus.onClicked
extension.lastError
runtime.onInstalled
```

SOURCE FILES:

``` list
manifest.json
sample.js
```

## [Global Google Search](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/Global%20Google%20Search.zip)

Use the context menu to search a different country's Google

CALLS:

``` list
contextMenus.create
contextMenus.onClicked
contextMenus.remove
runtime.onInstalled
storage.onChanged
storage.StorageArea.get
storage.StorageArea.set
tabs.create
```

SOURCE FILES:

``` list
background.js
globalGoogle128.png
globalGoogle16.png
globalGoogle48.png
locales.js
manifest.json
options.html
options.js
```

## [Cookie API Test Extension](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/Cookie%20API%20Test%20Extension.zip)

Testing Cookie API

CALLS:

``` list
browserAction.onClicked
cookies.getAll
cookies.onChanged
cookies.remove
extension.getURL
tabs.create
tabs.update
windows.getAll
```

SOURCE FILES:

``` list
background.js
cookie.png
manager.html
manager.js
manifest.json
```

## [Live HTTP headers](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/Live%20HTTP%20headers.zip)

Displays the live log with the http requests headers

CALLS:

``` list
browserAction.onClicked
debugger.attach
debugger.detach
debugger.onEvent
debugger.sendCommand
runtime.lastError
windows.create
```

SOURCE FILES:

``` list
background.js
headers.html
headers.js
icon.png
manifest.json
```

## [JavaScript pause/resume](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/JavaScript%20pause/resume.zip)

Pauses / resumes JavaScript execution

CALLS:

``` list
browserAction.onClicked
browserAction.setIcon
browserAction.setTitle
debugger.attach
debugger.detach
debugger.onDetach
debugger.onEvent
debugger.sendCommand
runtime.lastError
```

SOURCE FILES:

``` list
background.js
debuggerContinue.png
debuggerPause.png
debuggerPausing.png
manifest.json
```

## [Tab Flipper](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/Tab%20Flipper.zip)

Press Ctrl+Shift+Right or Ctrl+Shift+Left (Command+Shift+Right or Command+Shift+Left on a Mac) to flip through window tabs

CALLS:

``` list
commands.onCommand
tabs.query
tabs.update
```

SOURCE FILES:

``` list
background.js
manifest.json
images/tabFlipper128.png
images/tabFlipper16.png
images/tabFlipper32.png
images/tabFlipper48.png
```

## [Desktop Capture Example](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/Desktop%20Capture%20Example.zip)

Show desktop media picker UI

CALLS:

``` list
desktopCapture.cancelChooseDesktopMedia
desktopCapture.chooseDesktopMedia
runtime.onMessage
runtime.sendMessage
```

SOURCE FILES:

``` list
app.js
background.js
icon.png
index.html
manifest.json
```

## [My Devices](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/My%20Devices.zip)

A browser action with a popup dump of all devices signed into the same account as the current profile.

CALLS:

``` list
signedInDevices.get
signedInDevices.onDeviceInfoChange
```

SOURCE FILES:

``` list
icon.png
manifest.json
popup.html
popup.js
```

## [FirePHP for Chrome](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/FirePHP%20for%20Chrome.zip)

Extends the Developer Tools, adding support for parsing FirePHP messages from server

CALLS:

``` list
devtools.network.getHAR
devtools.network.onRequestFinished
extension.onRequest
extension.sendRequest
tabs.executeScript
```

SOURCE FILES:

``` list
background.js
devtools.html
devtools.js
manifest.json
```

## [Chrome Query](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/Chrome%20Query.zip)

Extends the Developer Tools, adding a sidebar that displays the jQuery data associated with the selected DOM element.

CALLS:

``` list
devtools.panels.ElementsPanel.createSidebarPane
devtools.panels.ElementsPanel.onSelectionChanged
```

SOURCE FILES:

``` list
devtools.html
devtools.js
manifest.json
```

## [tabCast](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/tabCast.zip)

Creates a WiFi Display Session from the captured tab media stream using chrome.displaySource API.

CALLS:

``` list
displaySource.getAvailableSinks
displaySource.onSessionTerminated
displaySource.onSinksUpdated
displaySource.startSession
displaySource.terminateSession
extension.getBackgroundPage
runtime.lastError
runtime.onMessage
runtime.sendMessage
tabCapture.capture
tabs.getCurrent
```

SOURCE FILES:

``` list
README
background.js
main.css
main.html
main.js
manifest.json
```

## [Document Scanning API Sample](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/Document%20Scanning%20API%20Sample.zip)

CALLS:

``` list
documentScan.scan
permissions.contains
permissions.request
runtime.lastError
```

SOURCE FILES:

``` list
README.md
background.js
manifest.json
scan.css
scan.html
scan.js
```

## [Download Filename Controller](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/Download%20Filename%20Controller.zip)

Download Filename Controller

CALLS:

``` list
downloads.onDeterminingFilename
```

SOURCE FILES:

``` list
bg.js
manifest.json
options.html
options.js
```

## [Download Selected Links](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/Download%20Selected%20Links.zip)

Select links on a page and download them.

CALLS:

``` list
downloads.download
extension.onRequest
extension.sendRequest
tabs.executeScript
tabs.query
windows.getCurrent
```

SOURCE FILES:

``` list
manifest.json
popup.html
popup.js
send_links.js
```

## [Download Manager Button](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/Download%20Manager%20Button.zip)

Browser Action Download Manager User Interface for Google Chrome

CALLS:

``` list
browserAction.setIcon
downloads.acceptDanger
downloads.cancel
downloads.download
downloads.erase
downloads.getFileIcon
downloads.onChanged
downloads.onCreated
downloads.onErased
downloads.open
downloads.pause
downloads.removeFile
downloads.resume
downloads.search
downloads.setShelfEnabled
downloads.show
downloads.showDefaultFolder
i18n.getMessage
permissions.contains
permissions.request
runtime.onMessage
runtime.sendMessage
tabs.create
```

SOURCE FILES:

``` list
background.js
icon128.png
icon19.png
icon38.png
icons.html
icons.js
manifest.json
popup.css
popup.html
popup.js
_locales/en/messages.json
```

## [Download and Open Button](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/Download%20and%20Open%20Button.zip)

Download and Open Context Menu Button

CALLS:

``` list
contextMenus.create
contextMenus.onClicked
downloads.download
downloads.onChanged
downloads.open
i18n.getMessage
```

SOURCE FILES:

``` list
background.js
icon128.png
icon16.png
manifest.json
_locales/en/messages.json
```

## [Downloads Overwrite Existing Files](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/Downloads%20Overwrite%20Existing%20Files.zip)

All downloads overwrite existing files instead of adding ' (1)', ' (2)', etc.

CALLS:

``` list
downloads.onDeterminingFilename
```

SOURCE FILES:

``` list
bg.js
manifest.json
```

## [Event Page Example](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/Event%20Page%20Example.zip)

Demonstrates usage and features of the event page

CALLS:

``` list
alarms.create
alarms.onAlarm
bookmarks.onRemoved
browserAction.onClicked
browserAction.setBadgeText
commands.onCommand
declarativeWebRequest.RedirectRequest
declarativeWebRequest.RequestMatcher
runtime.onInstalled
runtime.onMessage
runtime.onSuspend
runtime.sendMessage
tabs.create
tabs.executeScript
tabs.query
tabs.sendMessage
```

SOURCE FILES:

``` list
background.js
content.js
icon.png
manifest.json
```

## [`extension.isAllowedFileSchemeAccess` and `extension.isAllowedIncognitoAccess` Example](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/`extension.isAllowedFileSchemeAccess`%20and%20`extension.isAllowedIncognitoAccess`%20Example.zip)

Demonstrates the `extension.isAllowedFileSchemeAccess` and `extesion.isAllowedIncognitoAccess` APIs

CALLS:

``` list
extension.isAllowedFileSchemeAccess
extension.isAllowedIncognitoAccess
```

SOURCE FILES:

``` list
manifest.json
popup.html
popup.js
sample-128.png
sample-16.png
sample-19.png
sample-48.png
sample.css
```

## [Fake Archive Handler App](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/Fake%20Archive%20Handler%20App.zip)

Demonstrate File System Provider API usage for apps.

CALLS:

``` list
fileSystemProvider.get
fileSystemProvider.mount
fileSystemProvider.onCloseFileRequested
fileSystemProvider.onGetMetadataRequested
fileSystemProvider.onOpenFileRequested
fileSystemProvider.onReadDirectoryRequested
fileSystemProvider.onReadFileRequested
fileSystemProvider.onUnmountRequested
fileSystemProvider.unmount
runtime.lastError
runtime.onStartup
runtime.onSuspend
storage.StorageArea.get
storage.StorageArea.set
```

SOURCE FILES:

``` list
background.js
example1.fake
example2.fake
manifest.json
```

## [File System Provider API Extension Example](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/File%20System%20Provider%20API%20Extension%20Example.zip)

Demonstrate features of the API like mounting, listing directories, etc for extensions.

CALLS:

``` list
fileSystemProvider.mount
fileSystemProvider.onCloseFileRequested
fileSystemProvider.onGetMetadataRequested
fileSystemProvider.onMountRequested
fileSystemProvider.onOpenFileRequested
fileSystemProvider.onReadDirectoryRequested
fileSystemProvider.onReadFileRequested
fileSystemProvider.onUnmountRequested
fileSystemProvider.unmount
runtime.lastError
```

SOURCE FILES:

``` list
background.js
manifest.json
```

## [Advanced Font Settings](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/Advanced%20Font%20Settings.zip)

Customize per-script font settings.

CALLS:

``` list
fontSettings.clearDefaultFixedFontSize
fontSettings.clearDefaultFontSize
fontSettings.clearFont
fontSettings.clearMinimumFontSize
fontSettings.getDefaultFixedFontSize
fontSettings.getDefaultFontSize
fontSettings.getFont
fontSettings.getFontList
fontSettings.getMinimumFontSize
fontSettings.onDefaultFixedFontSizeChanged
fontSettings.onDefaultFontSizeChanged
fontSettings.onFontChanged
fontSettings.onMinimumFontSizeChanged
fontSettings.setDefaultFixedFontSize
fontSettings.setDefaultFontSize
fontSettings.setFont
fontSettings.setMinimumFontSize
```

SOURCE FILES:

``` list
fonts128.png
fonts16.png
manifest.json
options.html
options.js
pending_changes.js
slider.css
slider.js
js/cr.js
css/chrome_shared.css
css/overlay.css
css/uber_shared.css
css/widgets.css
images/disabled_select.png
images/select.png
images/x-hover.png
images/x-pressed.png
images/x.png
images/slider/slide_bar_center.png
images/slider/slide_bar_disabled_center.png
images/slider/slide_bar_disabled_left.png
images/slider/slide_bar_disabled_right.png
images/slider/slide_bar_fill_center.png
images/slider/slide_bar_fill_left.png
images/slider/slider_bar_right.png
images/slider/slider_thumb.png
images/slider/slider_thumb_disabled.png
images/slider/slider_thumb_down.png
images/slider/slider_thumb_hover.png
js/cr/ui.js
js/cr/ui/overlay.js
```

## [History Override](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/History%20Override.zip)

Overrides the History Page

CALLS:

``` list
history.deleteAll
history.deleteUrl
history.search
```

SOURCE FILES:

``` list
history.html
history128.png
history16.png
history32.png
history48.png
logic.js
manifest.json
style.css
```

## [Typed URL History](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/Typed%20URL%20History.zip)

Reads your history, and shows the top ten pages you go to by typing the URL.

CALLS:

``` list
history.getVisits
history.search
tabs.create
```

SOURCE FILES:

``` list
clock.png
manifest.json
typedUrls.html
typedUrls.js
```

## [CLD](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/CLD.zip)

Displays the language of a tab

CALLS:

``` list
browserAction.setBadgeText
tabs.detectLanguage
tabs.onSelectionChanged
tabs.onUpdated
tabs.query
```

SOURCE FILES:

``` list
background.js
manifest.json
```

## [Detect Language](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/Detect%20Language.zip)

Detects up to 3 languages and their percentages of the provided string

CALLS:

``` list
i18n.detectLanguage
```

SOURCE FILES:

``` list
icon.png
manifest.json
popup.html
popup.js
```

## [AcceptLanguage](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/AcceptLanguage.zip)

Returns accept languages of the browser

CALLS:

``` list
i18n.getAcceptLanguages
i18n.getMessage
```

SOURCE FILES:

``` list
icon.png
manifest.json
popup.html
popup.js
_locales/en_US/messages.json
_locales/es/messages.json
_locales/sr/messages.json
```

## [Minimal Localized Hosted App](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/Minimal%20Localized%20Hosted%20App.zip)

This is the minimal set of data required to upload a localized hosted application to the web store.

CALLS:

``` list
```

SOURCE FILES:

``` list
icon128.png
manifest.json
_locales/en/messages.json
_locales/de/messages.json
```

## [Idle - Simple Example](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/Idle%20-%20Simple%20Example.zip)

Demonstrates the Idle API

CALLS:

``` list
browserAction.onClicked
extension.getBackgroundPage
idle.onStateChanged
idle.queryState
```

SOURCE FILES:

``` list
background.js
history.html
history.js
manifest.json
sample-128.png
sample-16.png
sample-19.png
sample-48.png
```

## [Test IME](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/Test%20IME.zip)

A simple IME that converts all keystrokes to upper case.

CALLS:

``` list
input.ime
input.ime.commitText
input.ime.onActivate
input.ime.onBlur
input.ime.onDeactivated
input.ime.onFocus
input.ime.onKeyEvent
```

SOURCE FILES:

``` list
icon.png
main.js
manifest.json
```

## [Message Timer](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/Message%20Timer.zip)

Times how long it takes to send a message to a content script and back.

CALLS:

``` list
runtime.onConnect
runtime.onMessage
tabs.connect
tabs.query
tabs.sendMessage
```

SOURCE FILES:

``` list
clock.png
manifest.json
page.js
popup.html
popup.js
```

## [Native Messaging Example](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/Native%20Messaging%20Example.zip)

Send a message to a native application.

CALLS:

``` list
runtime.connectNative
```

SOURCE FILES:

``` list
icon-128.png
main.html
main.js
manifest.json

# Demo by Google
```

## [Notification Demo](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/Notification%20Demo.zip)

Shows off desktop notifications, which are "toast" windows that pop up on the desktop.

CALLS:

``` list
```

SOURCE FILES:

``` list
128.png
16.png
48.png
64.png
background.js
manifest.json
options.html
options.js
style.css
```

## [Omnibox New Tab Search](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/Omnibox%20New%20Tab%20Search.zip)

Type 'nt' plus a search term into the Omnibox to open search in new tab.

CALLS:

``` list
omnibox.onInputEntered
tabs.create
```

SOURCE FILES:

``` list
background.js
manifest.json
newtab_search128.png
newtab_search16.png
newtab_search32.png
newtab_search48.png
```

## [Omnibox Example](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/Omnibox%20Example.zip)

To use, type 'omnix' plus a search term into the Omnibox.

CALLS:

``` list
omnibox.onInputChanged
omnibox.onInputEntered
```

SOURCE FILES:

``` list
background.js
manifest.json
```

## [Blank new tab page](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/Blank%20new%20tab%20page.zip)

Override the new tab page with a blank one

CALLS:

``` list
```

SOURCE FILES:

``` list
blank.html
manifest.json
```

## [iGoogle new tab page](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/iGoogle%20new%20tab%20page.zip)

Override the new tab page with iGoogle

CALLS:

``` list
```

SOURCE FILES:

``` list
manifest.json
redirect.html
```

## [Page action by content](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/Page%20action%20by%20content.zip)

Shows a page action for HTML pages containing a video

CALLS:

``` list
declarativeContent.PageStateMatcher
declarativeContent.ShowPageAction
runtime.onInstalled
```

SOURCE FILES:

``` list
background.js
manifest.json
video-128.png
video-19.png
video-48.png
```

## [Page action by URL](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/Page%20action%20by%20URL.zip)

Shows a page action for urls which have the letter 'g' in them.

CALLS:

``` list
declarativeContent.PageStateMatcher
declarativeContent.ShowPageAction
runtime.onInstalled
```

SOURCE FILES:

``` list
background.js
icon-128.png
icon-19.png
icon-48.png
manifest.json
```

## [Animated Page Action](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/Animated%20Page%20Action.zip)

This extension adds an animated browser action to the toolbar.

CALLS:

``` list
pageAction.hide
pageAction.onClicked
pageAction.setIcon
pageAction.setTitle
pageAction.show
tabs.onSelectionChanged
tabs.query
```

SOURCE FILES:

``` list
background.html
background.js
icon1.png
icon2.png
manifest.json
```

## [Top Chrome Extension Questions](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/Top%20Chrome%20Extension%20Questions.zip)

Sample demonstration of the optional permissions API.

CALLS:

``` list
permissions.contains
permissions.onAdded
permissions.onRemoved
permissions.remove
permissions.request
tabs.create
```

SOURCE FILES:

``` list
manifest.json
options.html
options.js
popup.html
popup.js
images/icon.png
```

## [Keep Awake](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/Keep%20Awake.zip)

Override system power-saving settings.

CALLS:

``` list
browserAction.onClicked
browserAction.setIcon
browserAction.setTitle
i18n.getMessage
power.releaseKeepAwake
power.requestKeepAwake
runtime.onInstalled
runtime.onStartup
storage.StorageArea.get
storage.StorageArea.set
```

SOURCE FILES:

``` list
background.js
manifest.json
images/day-19.png
images/day-38.png
images/icon-128.png
images/icon-16.png
images/icon-48.png
images/night-19.png
images/night-38.png
images/sunset-19.png
images/sunset-38.png
_locales/en/messages.json
```

## [Block/allow third-party cookies API example extension](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/Block/allow%20third-party%20cookies%20API%20example%20extension.zip)

Sample extension which demonstrates how to access a preference.

CALLS:

``` list
extension.isAllowedIncognitoAccess
```

SOURCE FILES:

``` list
advicedog.jpg
manifest.json
popup.css
popup.html
popup.js
```

## [Block/allow referrer API example extension](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/Block/allow%20referrer%20API%20example%20extension.zip)

Sample extension which demonstrates how to access a preference.

CALLS:

``` list
extension.isAllowedIncognitoAccess
```

SOURCE FILES:

``` list
advicedog.jpg
manifest.json
popup.css
popup.html
popup.js
```

## [Print Extension](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/Print%20Extension.zip)

Sends print job directly to the printers installed on the Chromebook

CALLS:

``` list
printing.getPrinterInfo
printing.getPrinters
printing.submitJob
runtime.lastError
```

SOURCE FILES:

``` list
manifest.json
printers.css
printers.html
printers.js
test.pdf
icons/icon.png
icons/icon128.png
icons/icon16.png
icons/icon48.png
```

## [Print Job History](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/Print%20Job%20History.zip)

Reads your print history and displays the recent print jobs.

CALLS:

``` list
browserAction.setBadgeText
printingMetrics.getPrintJobs
printingMetrics.onPrintJobFinished
storage.StorageArea.get
storage.StorageArea.set
```

SOURCE FILES:

``` list
background.js
manifest.json
print.png
print_jobs.css
print_jobs.html
print_jobs.js
```

## [Process Monitor](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/Process%20Monitor.zip)

Adds a browser action that monitors resource usage of all browser processes.

CALLS:

``` list
processes.onUpdatedWithMemory
processes.terminate
```

SOURCE FILES:

``` list
icon.png
manifest.json
popup.html
popup.js
```

## [Show Tabs in Process](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/Show%20Tabs%20in%20Process.zip)

Adds a browser action showing which tabs share the current tab's process.

CALLS:

``` list
processes.getProcessIdForTab
tabs.query
tabs.update
windows.getAll
windows.getCurrent
windows.update
```

SOURCE FILES:

``` list
icon.png
manifest.json
popup.css
popup.html
popup.js
```

## [Stylizr](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/Stylizr.zip)

Spruce up your pages with custom CSS.

CALLS:

``` list
extension.getURL
runtime.lastError
storage.local
storage.StorageArea.clear
storage.StorageArea.get
storage.StorageArea.remove
storage.StorageArea.set
tabs.insertCSS
```

SOURCE FILES:

``` list
icon.png
manifest.json
options.html
options.js
popup.html
popup.js
```

Tab Capture Example

## [Tab Inspector](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/Tab%20Inspector.zip)

Utility for working with the extension tabs api

CALLS:

``` list
browserAction.onClicked
extension.getURL
tabs.create
tabs.get
tabs.getAllInWindow
tabs.move
tabs.onAttached
tabs.onCreated
tabs.onDetached
tabs.onMoved
tabs.onRemoved
tabs.onSelectionChanged
tabs.onUpdated
tabs.query
tabs.remove
tabs.update
windows.create
windows.get
windows.getAll
windows.getCurrent
windows.getLastFocused
windows.onCreated
windows.onFocusChanged
windows.onRemoved
windows.remove
windows.update
```

SOURCE FILES:

``` list
background.js
jstemplate_compiled.js
manifest.json
tabs_api.html
tabs_api.js
```

## [Keyboard Pin](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/Keyboard%20Pin.zip)

Creates a keyboard shortcut (Alt + Shift + P) to toggle the pinned state of the currently selected tab

CALLS:

``` list
commands.onCommand
tabs.query
tabs.update
```

SOURCE FILES:

``` list
README
background.js
manifest.json
```

## [Test Screenshot Extension](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/Test%20Screenshot%20Extension.zip)

Demonstrate screenshot functionality in the chrome.tabs api.

CALLS:

``` list
browserAction.onClicked
extension.getURL
extension.getViews
tabs.captureVisibleTab
tabs.create
tabs.onUpdated
```

SOURCE FILES:

``` list
background.js
camera.png
manifest.json
screenshot.html
screenshot.js
white.png
```

## [Tabs Zoom API Demo](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/Tabs%20Zoom%20API%20Demo.zip)

This extension allows the user to explore features of the new tabs zoom api.

CALLS:

``` list
runtime.lastError
tabs.getZoom
tabs.getZoomSettings
tabs.onZoomChange
tabs.query
tabs.setZoom
tabs.setZoomSettings
```

SOURCE FILES:

``` list
README
background.js
manifest.json
popup.html
popup.js
zoom16.png
zoom19.png
zoom48.png
```

## [Top Sites](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/Top%20Sites.zip)

Shows the top sites in a browser action

CALLS:

``` list
tabs.create
topSites.get
```

SOURCE FILES:

``` list
icon.png
manifest.json
popup.html
popup.js
```

## [NTP prototyping extension](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/NTP%20prototyping%20extension.zip)

extension to prototype new NTP designs

CALLS:

``` list
topSites.get
```

SOURCE FILES:

``` list
manifest.json
newTab.css
newTab.html
newTab.js
```

## [Console TTS Engine](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/Console%20TTS%20Engine.zip)

A "silent" TTS engine that prints text to a small window rather than synthesizing speech.

CALLS:

``` list
extension.getViews
ttsEngine.onSpeak
ttsEngine.onStop
windows.create
windows.getCurrent
windows.onRemoved
```

SOURCE FILES:

``` list
console_tts_engine.html
console_tts_engine.js
manifest.json
```

## [Drink Water Event Popup](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/Drink%20Water%20Event%20Popup.zip)

Demonstrates usage and features of the event page by reminding user to drink water

CALLS:

``` list
alarms.clearAll
alarms.create
alarms.onAlarm
browserAction.setBadgeText
notifications.create
notifications.onButtonClicked
storage.StorageArea.get
storage.StorageArea.set
```

SOURCE FILES:

``` list
background.js
drink_water128.png
drink_water16.png
drink_water32.png
drink_water48.png
manifest.json
popup.html
popup.js
stay_hydrated.png
```

## [WebNavigation Tech Demo](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/WebNavigation%20Tech%20Demo.zip)

Demonstration of the WebNavigation extension API.

CALLS:

``` list
i18n.getMessage
runtime.onMessage
runtime.onStartup
runtime.sendMessage
storage.StorageArea.get
storage.StorageArea.set
webNavigation.onBeforeNavigate
webNavigation.onCommitted
webNavigation.onCompleted
webNavigation.onCreatedNavigationTarget
webNavigation.onErrorOccurred
webNavigation.onHistoryStateUpdated
webNavigation.onReferenceFragmentUpdated
```

SOURCE FILES:

``` list
background.js
icon.png
manifest.json
navigation_collector.js
popup.css
popup.html
popup.js
_locales/en/messages.json
```

## [Webview transparency](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/Webview%20transparency.zip)

Sample of the webview.captureVisibleRegion api

CALLS:

``` list
```

SOURCE FILES:

``` list
display.html
main.js
manifest.json
test.html
test.js
test2.html
```

## [WebView Extension Communications Demo: App](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/WebView%20Extension%20Communications%20Demo:%20App.zip)

CALLS:

``` list
runtime.connect
```

SOURCE FILES:

``` list
app.js
main.js
manifest.json
test.html
```

## [WebView Extension Communications Demo: Extension](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/WebView%20Extension%20Communications%20Demo:%20Extension.zip)

Provides content scripts to an app hosting a WebView.

CALLS:

``` list
runtime.id
runtime.onConnectExternal
```

SOURCE FILES:

``` list
background.js
manifest.json
```

## [Merge Windows](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/Merge%20Windows.zip)

Merges all of the browser's windows into the current window

CALLS:

``` list
browserAction.onClicked
tabs.getAllInWindow
tabs.move
windows.getAll
windows.getCurrent
```

SOURCE FILES:

``` list
NOTICE
arrow_in.png
background.js
manifest.json
merge_windows_128.png
merge_windows_48.png
```

## [Simple Background App](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/Simple%20Background%20App.zip)

CALLS:

``` list
```

SOURCE FILES:

``` list
README
background.html
index.html
index.js
manifest.json
```

## [Calculator](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/Calculator.zip)

A simple calculator.

CALLS:

``` list
```

SOURCE FILES:

``` list
LICENSE
calculator.html
controller.js
manifest.json
model.js
style.css
view.js
images/buttons_1x.png
images/buttons_2x.png
images/icon-128x128.png
images/icon-16x16.png
```

## [App Launcher](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/App%20Launcher.zip)

Get access to your apps in a browser action

CALLS:

``` list
extension.getURL
management.getAll
management.launchApp
tabs.create
```

SOURCE FILES:

``` list
browser_action_icon.png
icon.png
manifest.json
popup.css
popup.html
popup.js
```

## [Chromium Buildbot Monitor](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/Chromium%20Buildbot%20Monitor.zip)

Displays the status of the Chromium buildbot in the toolbar. Click to see more detailed status in a popup.

CALLS:

``` list
browserAction.setBadgeBackgroundColor
browserAction.setBadgeText
browserAction.setTitle
extension.getBackgroundPage
extension.getURL
extension.getViews
storage.StorageArea.get
storage.StorageArea.set
```

SOURCE FILES:

``` list
active_issues.js
bg.js
chromium.png
icon.png
manifest.json
options.html
options.js
popup.css
popup.html
popup.js
prefs.js
try_status.js
utils.js
```

## [Google Calendar Checker (by Google)](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/Google%20Calendar%20Checker%20\(by%20Google\).zip)

Quickly see the time until your next meeting from any of your calendars. Click on the button to be taken to your calendar.

CALLS:

``` list
browserAction.onClicked
browserAction.setBadgeBackgroundColor
browserAction.setBadgeText
i18n.getMessage
management.uninstallSelf
notifications.clear
notifications.create
notifications.onButtonClicked
notifications.onClicked
runtime.getURL
runtime.id
runtime.onInstalled
tabs.create
```

SOURCE FILES:

``` list
manifest.json
views/options.html
javascript/background.js
javascript/options.js
images/icon-128.png
images/icon-16.png
images/icon-19.png
images/icon-38.png
images/icon-48.png
_locales/sr/messages.json
_locales/sk/messages.json
_locales/vi/messages.json
_locales/pt_BR/messages.json
_locales/hu/messages.json
_locales/fi/messages.json
_locales/el/messages.json
_locales/es/messages.json
_locales/de/messages.json
_locales/lv/messages.json
_locales/nl/messages.json
_locales/th/messages.json
_locales/ja/messages.json
_locales/ca/messages.json
_locales/cs/messages.json
_locales/id/messages.json
_locales/nb/messages.json
_locales/fr/messages.json
_locales/pl/messages.json
_locales/en/messages.json
_locales/zh_TW/messages.json
_locales/he/messages.json
_locales/es_419/messages.json
_locales/it/messages.json
_locales/pt_PT/messages.json
_locales/lt/messages.json
_locales/et/messages.json
_locales/en_GB/messages.json
_locales/fil/messages.json
_locales/sv/messages.json
_locales/hr/messages.json
_locales/ko/messages.json
_locales/da/messages.json
_locales/ro/messages.json
_locales/bg/messages.json
_locales/ar/messages.json
_locales/ru/messages.json
_locales/hi/messages.json
_locales/sl/messages.json
_locales/uk/messages.json
_locales/tr/messages.json
_locales/zh_CN/messages.json
```

## [CatBlock](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/CatBlock.zip)

I can't has cheezburger!

CALLS:

``` list
webRequest.onBeforeRequest
```

SOURCE FILES:

``` list
background.js
loldogs.js
manifest.json
```

## [Catifier](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/Catifier.zip)

Moar cats!

CALLS:

``` list
declarativeWebRequest.IgnoreRules
declarativeWebRequest.RedirectRequest
declarativeWebRequest.RequestMatcher
runtime.lastError
runtime.onInstalled
```

SOURCE FILES:

``` list
event_page.js
manifest.json
```

## [Chromium Search](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/Chromium%20Search.zip)

Add support to the omnibox to search the Chromium source code.

CALLS:

``` list
omnibox.onInputCancelled
omnibox.onInputChanged
omnibox.onInputEntered
omnibox.onInputStarted
omnibox.setDefaultSuggestion
tabs.query
tabs.update
```

SOURCE FILES:

``` list
background.js
manifest.json
```

## [Constant Context](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/Constant%20Context.zip)

Highlights elements with keywords on developer.chrome

CALLS:

``` list
declarativeContent.PageStateMatcher
declarativeContent.ShowPageAction
runtime.onInstalled
storage.StorageArea.clear
storage.StorageArea.get
storage.StorageArea.set
tabs.executeScript
```

SOURCE FILES:

``` list
background.js
content_script.js
manifest.json
popup.html
popup.js
images/cc128.png
images/cc16.png
images/cc32.png
images/cc48.png
```

## [Download Images](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/Download%20Images.zip)

Displays all webpage images and allows user to download

CALLS:

``` list
declarativeContent.PageStateMatcher
declarativeContent.ShowPageAction
downloads.download
runtime.lastError
runtime.onInstalled
storage.StorageArea.get
storage.StorageArea.set
tabs.create
tabs.executeScript
```

SOURCE FILES:

``` list
background.js
manifest.json
options.html
options.js
popup.html
popup.js
images/download_image128.png
images/download_image16.png
images/download_image32.png
images/download_image48.png
```

## [Email this page (by Google)](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/Email%20this%20page%20\(by%20Google\).zip)

This extension adds an email button to the toolbar which allows you to email the page link using your default mail client or Gmail.

CALLS:

``` list
browserAction.onClicked
runtime.connect
runtime.onConnect
tabs.create
tabs.executeScript
tabs.update
```

SOURCE FILES:

``` list
background.js
content_script.js
email_16x16.png
mail_128x128.png
manifest.json
options.html
options.js
```

## [Chrome Sounds](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/Chrome%20Sounds.zip)

Enjoy a more magical and immersive experience when browsing the web using the power of sound.

CALLS:

``` list
bookmarks.onCreated
bookmarks.onMoved
bookmarks.onRemoved
extension.getBackgroundPage
extension.onRequest
extension.sendRequest
tabs.get
tabs.onAttached
tabs.onCreated
tabs.onDetached
tabs.onMoved
tabs.onRemoved
tabs.onSelectionChanged
tabs.onUpdated
windows.onCreated
windows.onFocusChanged
windows.onRemoved
```

SOURCE FILES:

``` list
bg.js
content.js
icon.png
manifest.json
options.html
options.js
```

## [Google Document List Viewer](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/Google%20Document%20List%20Viewer.zip)

Demonstrates how to use OAuth to connect the Google Documents List Data API.

CALLS:

``` list
extension.getBackgroundPage
extension.getURL
tabs.create
tabs.onUpdated
tabs.query
tabs.remove
```

SOURCE FILES:

``` list
README
background.html
chrome_ex_oauth.html
chrome_ex_oauth.js
chrome_ex_oauthsimple.js
manifest.json
options.html
popup.html
img/docs_spreadsheets-128.gif
img/docs_spreadsheets-32.gif
img/docs_spreadsheets-48.gif
js/jquery-1.4.1.min.js
img/icons/audio.gif
img/icons/document.gif
img/icons/file.gif
img/icons/folder.gif
img/icons/form.gif
img/icons/pdf.gif
img/icons/presentation.gif
img/icons/spreadsheet.gif
```

## [Google Mail Checker](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/Google%20Mail%20Checker.zip)

Displays the number of unread messages in your Google Mail inbox. You can also click the button to open your inbox.

CALLS:

``` list
alarms.create
alarms.get
alarms.onAlarm
browserAction.onClicked
browserAction.setBadgeBackgroundColor
browserAction.setBadgeText
browserAction.setIcon
i18n.getMessage
runtime.onInstalled
runtime.onStartup
runtime.onStartup
tabs.create
tabs.getAllInWindow
tabs.onUpdated
tabs.update
webNavigation.onDOMContentLoaded
webNavigation.onDOMContentLoaded
webNavigation.onReferenceFragmentUpdated
webNavigation.onReferenceFragmentUpdated
windows.onCreated
```

SOURCE FILES:

``` list
background.html
background.js
gmail_logged_in.png
gmail_not_logged_in.png
icon_128.png
manifest.json
_locales/es/messages.json
_locales/nl/messages.json
_locales/pt_BR/messages.json
_locales/ar/messages.json
_locales/sk/messages.json
_locales/pt_PT/messages.json
_locales/he/messages.json
_locales/lv/messages.json
_locales/hr/messages.json
_locales/nb/messages.json
_locales/fil/messages.json
_locales/hi/messages.json
_locales/sv/messages.json
_locales/ko/messages.json
_locales/cs/messages.json
_locales/da/messages.json
_locales/sl/messages.json
_locales/pl/messages.json
_locales/es_419/messages.json
_locales/en_GB/messages.json
_locales/fi/messages.json
_locales/zh_CN/messages.json
_locales/en/messages.json
_locales/vi/messages.json
_locales/hu/messages.json
_locales/el/messages.json
_locales/th/messages.json
_locales/id/messages.json
_locales/bg/messages.json
_locales/ca/messages.json
_locales/sr/messages.json
_locales/zh_TW/messages.json
_locales/ro/messages.json
_locales/ja/messages.json
_locales/tr/messages.json
_locales/uk/messages.json
_locales/it/messages.json
_locales/fr/messages.json
_locales/et/messages.json
_locales/ru/messages.json
_locales/lt/messages.json
_locales/de/messages.json
```

## [Imageinfo](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/Imageinfo.zip)

Get image info for images, including EXIF data

CALLS:

``` list
contextMenus.create
tabs.getCurrent
windows.create
windows.update
```

SOURCE FILES:

``` list
NOTICE
background.js
imageinfo-128.png
imageinfo-16.png
imageinfo-48.png
info.css
info.html
info.js
loader.gif
manifest.json
imageinfo/binaryajax.js
imageinfo/exif.js
imageinfo/imageinfo.js
imageinfo/readme.txt

Chromium IRC App

CALLS:

``` list
```

SOURCE FILES:

``` list
manifest.json
```

## [Managed Bookmarks](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/Managed%20Bookmarks.zip)

Adds bookmarks configured by your system administrator to Chrome.

CALLS:

``` list
bookmarks.create
bookmarks.getChildren
bookmarks.move
bookmarks.onChanged
bookmarks.onMoved
bookmarks.onRemoved
bookmarks.remove
bookmarks.removeTree
bookmarks.update
runtime.onInstalled
storage.StorageArea.get
storage.StorageArea.set
storage.StorageArea.get
storage.onChanged
```

SOURCE FILES:

``` list
background.js
manifest.json
schema.json
_locales/en/messages.json
```

## [Mappy](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/Mappy.zip)

Finds addresses in the web page you're on and pops up a map window.

CALLS:

``` list
pageAction.setTitle
pageAction.show
runtime.onMessage
runtime.sendMessage
storage.StorageArea.get
storage.StorageArea.set
```

SOURCE FILES:

``` list
background.js
icon.png
manifest.json
mappy_content_script.js
marker.png
popup.css
popup.html
popup.js

Google Maps

CALLS:

``` list
```

SOURCE FILES:

``` list
128.png
24.png
manifest.json
```

## [News Reader (by Google)](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/News%20Reader%20\(by%20Google\).zip)

Displays the latest stories from Google News in a popup.

CALLS:

``` list
extension.getURL
i18n.getMessage
tabs.create
```

SOURCE FILES:

``` list
manifest.json
images/buzz.png
images/delete-icon.png
images/fb.png
images/news.gif
images/news_action.png
images/news_icon.png
images/sprite_arrows.gif
images/twitter.png
css/feed.css
css/options.css
javascript/feed.js
javascript/options.js
javascript/util.js
views/background.html
views/feed.html
views/options.html
_locales/en/messages.json
```

## [News Reader](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/News%20Reader.zip)

Displays the first 5 items from the 'Google News - top news' RSS feed in a popup.

CALLS:

``` list
tabs.create
```

SOURCE FILES:

``` list
feed.css
feed.html
feed.js
feed_iframe.css
feed_iframe.js
manifest.json
news_action.png
news_icon.png
sprite_arrows.gif
```

## [News Reader(1)](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/News%20Reader\(1\).zip)

Displays the first 5 items from the '$Google$ News - top news' RSS feed in a popup.

CALLS:

``` list
```

SOURCE FILES:

``` list
feed.html
manifest.json
news_action.png
news_icon.png
sprite_arrows.gif
_locales/sr/messages.json
_locales/es/messages.json
_locales/en/messages.json
```

## [No Cookies](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/No%20Cookies.zip)

Removes 'Cookie' and 'Set-Cookie' headers.

CALLS:

``` list
webRequest.onBeforeSendHeaders
webRequest.onHeadersReceived
```

SOURCE FILES:

``` list
background.js
manifest.json
```

## [Sample - OAuth Contacts](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/Sample%20-%20OAuth%20Contacts.zip)

Uses OAuth to connect to Google's contacts service and display a list of your contacts.

CALLS:

``` list
browserAction.onClicked
browserAction.setIcon
extension.getBackgroundPage
extension.getURL
tabs.create
tabs.onUpdated
tabs.query
tabs.remove
```

SOURCE FILES:

``` list
NOTICE
README
background.js
chrome_ex_oauth.html
chrome_ex_oauth.js
chrome_ex_oauthsimple.js
contacts.html
contacts.js
manifest.json
onload.js
img/icon-128.png
img/icon-19-off.png
img/icon-19-on.png
img/icon-48.png
```

## [Optional Permissions New Tab](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/Optional%20Permissions%20New%20Tab.zip)

Demonstrates optional permissions in extensions

CALLS:

``` list
permissions.contains
permissions.request
storage.StorageArea.get
storage.StorageArea.set
topSites.get
```

SOURCE FILES:

``` list
logic.js
manifest.json
newtab.html
style.css
images/optional_permissions128.png
images/optional_permissions16.png
images/optional_permissions32.png
images/optional_permissions48.png
```

## [Per-plugin content settings](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/Per-plugin%20content%20settings.zip)

Customize your content setting for different plugins.

CALLS:

``` list
contentSettings.plugins
contentSettings.ContentSetting.clear
contentSettings.ContentSetting.getResourceIdentifiers
contentSettings.ContentSetting.set
i18n.getMessage
runtime.lastError
```

SOURCE FILES:

``` list
bunny128.png
bunny48.png
manifest.json
options.html
js/chrome_stubs.js
js/main.js
js/plugin_list.js
js/plugin_list_test.html
js/plugin_settings.js
js/plugin_settings_test.html
js/rule_list.js
js/rule_list_test.html
css/plugin_list.css
css/rule_list.css
domui/css/button.css
domui/css/chrome_shared.css
domui/css/list.css
domui/css/select.css
options/images/close_bar.png
options/images/close_bar_h.png
options/images/close_bar_p.png
options/js/deletable_item_list.js
options/js/inline_editable_list.js
domui/images/select.png
domui/js/cr.js
domui/js/util.js
_locales/en/messages.json
options/css/list.css
domui/js/cr/event_target.js
domui/js/cr/ui.js
domui/js/cr/ui/array_data_model.js
domui/js/cr/ui/list.js
domui/js/cr/ui/list_item.js
domui/js/cr/ui/list_selection_controller.js
domui/js/cr/ui/list_selection_model.js
domui/js/cr/ui/list_single_selection_model.js
```

## [Proxy Extension API Sample](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/Proxy%20Extension%20API%20Sample.zip)

Set Chrome-specific proxies; a demonstration of Chrome's Proxy API

CALLS:

``` list
browserAction.setBadgeBackgroundColor
browserAction.setBadgeText
browserAction.setTitle
extension.isAllowedIncognitoAccess
extension.onRequest
extension.sendRequest
i18n.getMessage
proxy.onProxyError
runtime.lastError
```

SOURCE FILES:

``` list
background.js
icon128.png
icon16.png
icon32.png
icon48.png
manifest.json
popup.css
popup.html
popup.js
proxy_error_handler.js
proxy_form_controller.js
test/jsunittest.js
test/proxy_form_controller_test.html
test/proxy_form_controller_test.js
test/unittest.css
_locales/en/messages.json
```

## [Speak Selection](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/Speak%20Selection.zip)

Speaks the current selection out loud.

CALLS:

``` list
browserAction.onClicked
browserAction.setIcon
extension.getURL
extension.onRequest
extension.sendRequest
tabs.create
tabs.executeScript
tabs.sendRequest
tts.getVoices
tts.speak
tts.stop
windows.getAll
```

SOURCE FILES:

``` list
SpeakSel128.png
SpeakSel16.png
SpeakSel19-active.png
SpeakSel19.png
SpeakSel256.png
SpeakSel48.png
background.js
content_script.js
keycodes.js
manifest.json
options.html
options.js
tabs.js
```

## [Talking Alarm Clock](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/Talking%20Alarm%20Clock.zip)

A clock with two configurable alarms that will play a sound and speak a phrase of your choice.

CALLS:

``` list
browserAction.setIcon
runtime.connect
runtime.onConnect
tts.getVoices
tts.speak
tts.stop
```

SOURCE FILES:

``` list
background.js
blank-clock-150.png
blank-clock-ring1-150.png
blank-clock-ring2-150.png
clock-128.png
clock-16.png
clock-19.png
clock-256.png
clock-48.png
clock-disabled-19.png
clock-highlighted-19.png
common.js
credits.html
manifest.json
play.png
popup.html
popup.js
audio/cuckoo.ogg
audio/digital.ogg
audio/metal.ogg
audio/ringing.ogg
audio/rooster.ogg
```

## [TTS Debug](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/TTS%20Debug.zip)

Tool for developers of Chrome TTS engine extensions to help them test their engines are implementing the API correctly.

CALLS:

``` list
tts.getVoices
tts.speak
tts.stop
```

SOURCE FILES:

``` list
128.png
16.png
256.png
manifest.json
pacman.gif
ttsdebug.css
ttsdebug.html
ttsdebug.js
```

## [TTS Demo](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/TTS%20Demo.zip)

Demo Chrome's synthesized text-to-speech capabilities.

CALLS:

``` list
runtime.lastError
tts.getVoices
tts.isSpeaking
tts.speak
tts.stop
```

SOURCE FILES:

``` list
128.png
16.png
256.png
manifest.json
ttsdemo.html
ttsdemo.js
```

## [Sandboxed Frame](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/Sandboxed%20Frame.zip)

Demonstrate use of handlebars inside a sandboxed frame

CALLS:

``` list
browserAction.onClicked
```

SOURCE FILES:

``` list
LICENSE.handlebars
eventpage.html
eventpage.js
handlebars-1.0.0.beta.6.js
icon.png
manifest.json
sandbox.html
```

## [Tab Shortcuts](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/Tab%20Shortcuts.zip)

Allows pinning and duplication of tabs via keyboard shortcuts.

CALLS:

``` list
commands.onCommand
tabs.duplicate
tabs.update
```

SOURCE FILES:

``` list
manifest.json
tab_shortcuts.js
```

## [Event Tracking with Google Analytics](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/Event%20Tracking%20with%20Google%20Analytics.zip)

A sample extension which uses Google Analytics to track usage.

CALLS:

``` list
```

SOURCE FILES:

``` list
analytics-extension-icon-128.png
analytics-extension-icon-19.png
analytics-extension-icon-48.png
manifest.json
popup.html
popup.js
```

## [Broken Background Color](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/Broken%20Background%20Color.zip)

Fix an Extension!

CALLS:

``` list
declarativeContent.PageStateMatcher
declarativeContent.ShowPageAction
storage.StorageArea.get
storage.StorageArea.set
tabs.executeScript
```

SOURCE FILES:

``` list
background.js
manifest.json
options.html
options.js
popup.html
popup.js
images/get_started128.png
images/get_started16.png
images/get_started32.png
images/get_started48.png
```

## [Getting Started Example](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/Getting%20Started%20Example.zip)

Build an Extension!

CALLS:

``` list
runtime.onInstalled
storage.StorageArea.get
storage.StorageArea.set
```

SOURCE FILES:

``` list
background.js
images.zip
manifest.json
options.html
options.js
popup.html
popup.js
images/get_started128.png
images/get_started16.png
images/get_started32.png
images/get_started48.png
```

## [Getting Started Example(1)](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/Getting%20Started%20Example\(1\).zip)

Build an Extension!

CALLS:

``` list
declarativeContent.PageStateMatcher
declarativeContent.ShowPageAction
runtime.onInstalled
storage.StorageArea.get
storage.StorageArea.set
tabs.executeScript
tabs.query
```

SOURCE FILES:

``` list
background.js
manifest.json
options.html
options.js
popup.html
popup.js
images/get_started128.png
images/get_started16.png
images/get_started32.png
images/get_started48.png
```

## [Getting started example(2)](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/Getting%20started%20example\(2\).zip)

This extension allows the user to change the background color of the current page.

CALLS:

``` list
runtime.lastError
storage.local
storage.sync
storage.StorageArea.get
storage.StorageArea.set
tabs.executeScript
tabs.query
```

SOURCE FILES:

``` list
icon.png
manifest.json
popup.html
popup.js
```

## [Hello Extensions](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/Hello%20Extensions.zip)

Base Level Extension

CALLS:

``` list
```

SOURCE FILES:

``` list
hello.html
hello_extensions.png
manifest.json
```

## [OAuth Tutorial FriendBlock(1)](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/OAuth%20Tutorial%20FriendBlock\(1\).zip)

Uses OAuth to connect to Google's People API and display contacts photos.

``` list

CALLS:

``` list
browserAction.onClicked
identity.getAuthToken
tabs.create
```

SOURCE FILES:

``` list
background.js
index.html
manifest.json
oauth.js
```

## [OAuth Tutorial FriendBlock(2)](https://github.com/emanruoy/chrome-extension-google-demo/raw/master/OAuth%20Tutorial%20FriendBlock\(2\).zip)

Uses OAuth to connect to Google's People API and display contacts photos.

``` list

CALLS:

``` list
browserAction.onClicked
identity.getAuthToken
tabs.create
```

SOURCE FILES:

``` list
background.js
index.html
manifest.json
oauth.js
```
