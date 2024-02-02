# purge memory
https://osxdaily.com/2012/04/24/free-up-inactive-memory-in-mac-os-x-with-purge-command/
```sudo purge```

# App Switcher on all monitors
You can also display the app switcher on all monitors with the following undocumented preference:

```defaults write com.apple.dock appswitcher-all-displays -bool true
killall Dock```
