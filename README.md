# Using Robocorp Control Room with Apple Shortcuts

## Things to keep in mind

1. You need to keep in mind all the devices the iCloud syncing these Shortcuts will be synced with

## Implement the shortcut with Mac application `Shortcuts`

If ICloud syncing is on between Mac and other IOS devices then implemented shortcut will appear almost instantly for example. on your iPhone.

1. Use `Get Contents of URL` in the Apple Shortcuts application and click `Show more`. Change method to `POST` and set `Authorization` header

<img src="apple_shortcuts.png" style="margin-bottom:20px">

2. After sync has happened the same Shortcut and be found with iPhone search, in my case with the name starting with `Trigger..`

<img src="iphone_shortcut.png" style="margin-bottom:20px">
