IDE-Preferences
===============

Keymappings and macros for RubyMine and IntelliJ IDEA

Ideally clone this repo.
Then symlink the files in your IDE preferences folder.
For example, using RubyMine ~> 6
```
cd ~/Library/Preferences/RubyMine60/keymaps
ln -sf ~/workspace/IDE-Preferences/IntelliJKeymap.xml
```
To add the custom macros, do the same for the macros.xml
```
cd ~/Library/Preferences/RubyMine60/options
ln -sf ~/workspace/IDE-Preferences/macros.xml
```


For IntelliJ 13
```
cd ~/Library/Preferences/IntelliJIdea13/keymaps
ln -sf ~/workspace/IDE-Preferences/IntelliJKeymap.xml
```
And again, do the same for the macros if you want them
```
cd ~/Library/Preferences/IntelliJIdea13/options
ln -sf ~/workspace/IDE-Preferences/macros.xml
```

They are using the same format, so you can change configuration in one IDE and see it applied to the other one.
The Keymap is called "Mac OSX 10.5 + Improved" in your keymaps sett
