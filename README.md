mac_tool_conf
=============
This is repository that keep the configuration for mac's tools.

#How to use
##Karabinder
```
cd ~/mac_tool_conf/Karabinder
bash conf.sh
cp private.xml /Users/isogai_yoshinori/Library/Application\ Support/Karabiner/private.xml
```
Change Key tab > Reload XML

##iTerm2
```
iTerm2 > Preferences > General > Load preferences from a custom folder or URL
```

##Seil
```
cp org.pqrs.Seil.plist ~/Library/Preferences/org.pqrs.Seil.plist
```

##Xcode
```
cp -prf wombat.dvtcolortheme ~/Library/Developer/Xcode/UserData/FontAndColorThemes
```

##HyperSwitch
```
cp com.bahoom.HyperSwitch.plist ~/Library/Preferences/com.bahoom.HyperSwitch.plist
```

##AndroidStudio
```
File > Import Settings, then choose file to import
```

#How to export settings
##Karabinder
```
cd ~/mac_tool_conf/Karabinder
/Applications/Karabiner.app/Contents/Library/bin/karabiner export > conf.sh
cp /Users/isogai_yoshinori/Library/Application\ Support/Karabiner/private.xml .
```

##iTerm2
```
iTerm2 > Preferences > General > Load preferences from a custom folder or URL
```
Choose empty folder

##Seil
```
cp ~/Library/Preferences/org.pqrs.Seil.plist org.pqrs.Seil.plist
```

##Xcode
```
cp -prf ~/Library/Developer/Xcode/UserData/FontAndColorThemes wombat.dvtcolortheme
```

##HyperSwitch
```
cp ~/Library/Preferences/com.bahoom.HyperSwitch.plist com.bahoom.HyperSwitch.plist
```

##AndroidStudio
```
File > Export Settings, then choose file to export
```
