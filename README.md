# Crossrider Sublime Snipets

### Crossrider's API sublime text 2 snippets helper ###

## Installation
* git clone
* FInd your user packages folder. The easiest way to find it is creating a new snippet by going to Tools -> New Snippet. Try to save the new snippet and Sublime should automatically try to save it in the user package folder. Copy that location and cancel the save file.
* Copy CrossriderSnippets folder to your user packages folder
* Sublime might need to restart for changes to have effect

## Usage
File type must be javascript in order for snippets to have effect. Just start typing one of the supported snippets keys and sublime should open a dropdown menu.
#####Supported snippets keys:
> ####DB:
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

>####DB Async:
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

>#### Message
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

>#### Request:
>
* requestGet
* requestPost

>#### BrowserAction
>
* clearPopup
* closePopup
* setPopup
* setBadgeBackgroundColor
* setBadgeText
* setResourceIcon
* browserActionOnClick
* browserActionSetTitle

>#### ContextMenu
>
* contextMenuAdd
* contextMenuAddSeparator
* contextMenuRemove
* contextMenuRemoveAll
* contextMenuUpdateOnClick
* contextMenuUpdateTitle

>#### Tabs
>
* tabsCreate
* tabsGetActive
* tabsSetActive
* tabsGetAllTabs
* tabsOnTabClosed
* tabsOnTabCreated
* tabsOnTabSelectionChanged

>#### DOM:
>
* domAddInlineCSS
* domAddInlineJS
* domAddRemoteCSS
* domAddRemoteJS
* domIsIframe
* domOnDocumentStartAddCSS
* domOnDocumentStartAddJS

>#### Time:
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
