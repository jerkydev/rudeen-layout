# rudeen_layout
Russian, English, German keyboard layout

wip

## Install

`make install`

Reboot

`open -a Xcode ~/Library/Preferences/com.apple.HIToolbox.plist`

Remove the input source or input sources you want to disable from the `AppleEnabledInputSources` dictionary. If there is an `AppleDefaultAsciiInputSource` key, remove it.
