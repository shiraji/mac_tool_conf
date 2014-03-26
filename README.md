mac_tool_conf
=============
This is repository that keep the configuration for mac's tools.

#How to use
##KeyRemap4MacBook
```
bash conf.sh
```
##iTerm2
```
iTerm2 > Preferences > General > Load preferences from a custom folder or URL
```

##PCKeyboardHack
```
cp org.pqrs.PCKeyboardHack.plist ~/Library/Preferences/org.pqrs.PCKeyboardHack.plist
```

##Xcode
```
cp -prf wombat.dvtcolortheme ~/Library/Developer/Xcode/UserData/FontAndColorThemes
```

##HyperSwitch
```
cp com.bahoom.HyperSwitch.plist ~/Library/Preferences/com.bahoom.HyperSwitch.plist
```

#How to export settings
##Keyremap4macbook
```
/Applications/KeyRemap4MacBook.app/Contents/Applications/KeyRemap4MacBook_cli.app/Contents/MacOS/KeyRemap4MacBook_cli export > conf.sh
```

##iTerm2
```
iTerm2 > Preferences > General > Load preferences from a custom folder or URL
```
Choose empty folder

##PCKeyboardHack
```
cp ~/Library/Preferences/org.pqrs.PCKeyboardHack.plist org.pqrs.PCKeyboardHack.plist
```

##Xcode
```
cp -prf ~/Library/Developer/Xcode/UserData/FontAndColorThemes wombat.dvtcolortheme
```

##HyperSwitch
```
cp ~/Library/Preferences/com.bahoom.HyperSwitch.plist com.bahoom.HyperSwitch.plist
```
