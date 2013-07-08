# Crossrider Sublime Snippets

This project contains Crossrider's API snippet files to enhance coding using Crossrider's [Debug Mode](http://docs.crossrider.com/#!/guide/debug_mode) with [Sublime Text 2](http://www.sublimetext.com/).

## Installation
1. git clone (or [download](https://github.com/erez12/CrossriderSublime/archive/master.zip)).
2. Locate your Sublime user packages folder.
**Tip**: The easiest way to find location is to create a new snippet (Tools -> New Snippet), attempt to save it making note of the save folder (by default, this is the user packages folder), and then canceling the save.
3. Copy the CrossriderSnippets folder from the git clone (or download) to your user packages folder.
**Note**: You may need to restart Sublime for changes to take effect.

## Usage
Open or Create a JavaScript file (.js) and just start typing the first character of any of the supported snippets keywords and Sublime opens a drop-down menu of the matching snippets.
**Tip**: You can speed up finding snippets by typing ahead. For example, to speed up matching *browserActionOnClick*, you can type **baonclick**.
#####Supported snippets keywords:

> ####appAPI:
>
* clearInterval
* clearTimeout
* getTabId
* isBackground
* isDebugMode
* isMatchPages
* openURL
* platform
* ready
* selectedText
* setInterval
* setTimeout

> ####appAPI.appInfo:
>
* appInfoDescription
* appInfoEnvironment
* appInfoId
* appInfoName
* appInfoUserId
* appInfoVersion

> ####bookmarks
>
* bookmarksCreate
* bookmarksCreateFolder
* bookmarksGetDefaultFolder
* bookmarksGetToolbarFolder
* bookmarksGetTree
* bookmarksIsBookmark
* bookmarksRemove
* bookmarksSearchByPredicate
* bookmarksSearchByTitle
* bookmarksSearchByUrl
* bookmarksUpdateTitle
* bookmarksUpdateUrl

> ####appAPI.browser
>
* browserName
* browserRealVersion
* browserRealVersionNumber
* browserVersion
* browserVersionNumber

> ####appAPI.browserAction
>
* browserActionOnClick
* browserActionClearPopup
* browserActionClosePopup
* browserActionSetBadgeBackgroundColor
* browserActionSetBadgeText
* browserActionSetPopup
* browserActionSetResourceIcon
* browserActionSetTitle

> ####appAPI.contextMenu
>
* contextMenuAdd
* contextMenuAddSeparator
* contextMenuRemove
* contextMenuRemoveAll
* contextMenuUpdateOnClick
* contextMenuUpdateTitle

> ####appAPI.db:
>
* dbGet
* dbGetExpiration
* dbGetKeys
* dbGetList
* dbRemove
* dbRemoveAll
* dbSet
* dbSetFromRemote
* dbUpdateExpiration

> ####appAPI.db.async:
>
* dbAsyncGet
* dbAsyncGetExpiration
* dbAsyncGetKeys
* dbAsyncGetList
* dbAsyncRemove
* dbAsyncRemoveAll
* dbAsyncSet
* dbAsyncSetFromRemote
* dbAsyncUpdateExpiration

> ####appAPI.dom:
>
* domAddInlineCSS
* domAddInlineJS
* domAddRemoteCSS
* domAddRemoteJS
* domIsIframe
* domOnDocumentStartAddCSS
* domOnDocumentStartAddJS

> ####appAPI.JSON
>
* JSONParse
* JSONStringify

> ####appAPI.message
>
* messageAddListener
* messageRemoveListener
* messageToActiveTab
* messageToAllOtherTabs
* messageToAllTabs
* messageToBackground
* messageToCurrentTabIframes
* messageToCurrentTabWindow
* messageToPopup

> ####appAPI.os
>
* osName

> ####appAPI.request:
>
* requestGet
* requestPost

> ####appAPI.resources
>
* resourcesAddInlineJS
* resourcesCreateImage
* resourcesGet
* resourcesGetFolder
* resourcesGetImage
* resourcesIncludeCSS
* resourcesIncludeJS
* resourcesIncludeRemoteJS
* resourcesJquery
* resourcesJqueryUI
* resourcesParseTemplate

> ####appAPI.shortcut
>
* shortcutAdd
* shortcutRemove

> ####appAPI.tabs
>
* tabsCreate
* tabsGetActive
* tabsGetAllTabs
* tabsOnTabClosed
* tabsOnTabCreated
* tabsOnTabSelectionChanged
* tabsSetActive

> ####appAPI.time:
>
* timeDaysAgo
* timeDaysFromNow
* timeHoursAgo
* timeHoursFromNow
* timeMinutesAgo
* timeMinutesFromNow
* timeNow
* timeSecondsAgo
* timeSecondsFromNow
* timeYearsAgo
* timeYearsFromNow

> ####appAPI.utils
>
* utilsGetDomain
* utilsGetHost
* utilsIndexOf
* utilsIsArray
* utilsIsBoolean
* utilsIsDefined
* utilsIsFunction
* utilsIsNumber
* utilsIsObject
* utilsIsString

> ####appAPI.webRequest:
>
* onBeforeNavigateAddListener
* onBeforeNavigateRemoveListener
* onBeforeNavigateUpdateOpaque
* onRequestAddListener
* onRequestRemoveListener
* onRequestUpdateOpaque

> ####CrossriderAPI:
>
* bindExtensionEvent
* fireExtensionEvent
* isAppInstalled

## Author

* Erez Giladi

## License

This bundle is dual-licensed under MIT and GPL licenses (just like jQuery).

* [http://www.opensource.org/licenses/mit-license.php](http://www.opensource.org/licenses/mit-license.php)
* [http://www.gnu.org/licenses/gpl.html](http://www.gnu.org/licenses/gpl.html)

Use it, change it, fork it, sell it. Do what you will, but please leave the author attribution.

This project is provided as-is and the author takes no responsibility for any damage resulting from using this project.