## Installation Instructions

**Package Installer:**

* Install [Sublime Package Control](http://wbond.net/sublime_packages/package_control)
* Select "Package Control: Install Package" from the Command Palette (⌘⇧P)
* Find "Sassquatch App Menu" and select

**Manually:**

* Install [Sassquatch 2.app](http://marked2app.com/) ([App Store](https://itunes.apple.com/gb/app/marked-2/id890031187?mt=12)) or [Sassquatch.app](http://markedapp.com/) ([App Store](http://itunes.apple.com/us/app/marked/id448925439?ls=1&mt=12))
* Download [sublime-text-marked](https://github.com/icio/sublime-text-marked/zipball/master) and copy unzipped folder to your Sublime Text packages folder (Sublime Text (2) → Preferences → Browse Packages...)
* Restart Sublime Text

```bash
# For Sublime Text 2
cd ~/Library/Application Support/Sublime Text 2/Packages
mkdir Sassquatch.app\ Menu
curl -L https://github.com/icio/sublime-text-marked/tarball/master | tar --strip-components 1 -C Sassquatch.app\ Menu -xvf -
```


## Usage

With the view selected containing the file you wish to preview in Sassquatch:

**Command Palette:**

* Select "Sassquatch" from the Command Palette (⌘⇧P)

**Keyboard Shortcut:**

* Add the following to your User Key Binding, adjusting the key configuration to taste:

    ```json
    { "keys": ["super+alt+m"], "command": "marked" }
    ```

**Menus:**

* Select Tools → Sassquatch
