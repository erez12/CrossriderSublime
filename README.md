# Crossrider Sublime Snipets

### Crossrider's API sublime text 2 snippets helper ###

## Installation
* git clone
* Find your user packages folder. The easiest way to find it is creating a new snippet by going to Tools -> New Snippet. Try to save the new snippet and Sublime should automatically try to save it in the user package folder. Copy that location and cancel the save file.
* Copy CrossriderSnippets folder to your user packages folder
* Sublime might need to restart for changes to have effect

## Usage
File type must be javascript in order for snippets to have effect. Just start typing one of the supported snippets keys and sublime should open a dropdown menu.
#####Supported snippets keys:
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

>####appAPI.db.async:
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

>####appAPI.message
>
* messageAddListener
* messageRemoveListener
* messageToActiveTab
* messageToAllOtherTabs
* messageToAllTabs
* messageToBackground
* messageToCurrentTabIframes
* messageToCurrentTabWindow
* messageToCurrentTabWindow

>####appAPI.request:
>
* requestGet
* requestPost

>####appAPI.webRequest:
>
* onRequestAddListener
* onRequestRemoveListener
* onRequestUpdateOpaque
* onBeforeNavigateAddListener
* onBeforeNavigateRemoveListener
* onBeforeNavigateUpdateOpaque

>####appAPI.browserAction
>
* clearPopup
* closePopup
* setPopup
* setBadgeBackgroundColor
* setBadgeText
* setResourceIcon
* browserActionOnClick
* browserActionSetTitle

>####appAPI.contextMenu
>
* contextMenuAdd
* contextMenuAddSeparator
* contextMenuRemove
* contextMenuRemoveAll
* contextMenuUpdateOnClick
* contextMenuUpdateTitle

>####appAPI.tabs
>
* tabsCreate
* tabsGetActive
* tabsSetActive
* tabsGetAllTabs
* tabsOnTabClosed
* tabsOnTabCreated
* tabsOnTabSelectionChanged

>####appAPI.dom:
>
* domAddInlineCSS
* domAddInlineJS
* domAddRemoteCSS
* domAddRemoteJS
* domIsIframe
* domOnDocumentStartAddCSS
* domOnDocumentStartAddJS

>####appAPI.time:
>
* now
* secondsAgo
* secondsFromNow
* minutesAgo
* minutesFromNow
* hoursAgo
* hoursFromNow
* daysAgo
* daysFromNow
* yearsAgo
* yearsFromNow

>####appAPI.time:
>
* now
* secondsAgo
* secondsFromNow
* minutesAgo
* minutesFromNow
* hoursAgo
* hoursFromNow
* daysAgo
* daysFromNow
* yearsAgo
* yearsFromNow

## Author

* Erez Giladi

## License

This bundle is dual-licensed under MIT and GPL licenses (just like jQuery).

* [http://www.opensource.org/licenses/mit-license.php](http://www.opensource.org/licenses/mit-license.php)
* [http://www.gnu.org/licenses/gpl.html](http://www.gnu.org/licenses/gpl.html)

Use it, change it, fork it, sell it. Do what you will, but please leave the author attribution.
