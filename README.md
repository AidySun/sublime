# sublime

Sublime Text preference and Package Control settings for Windows. Refer to https://github.com/AidySun/sublime/tree/mac for macOS.

## Usage
0. Install Package Control in Sublime Text
1. Run in cmd

   ```
   cd "%AppData%\Sublime Text 3"
   rename Packages/User Packages/User.bak
   git init
   git remote add sublime http://github.com/AidySun/sublime.git
   git pull sublime win
   ```
2. Add "Open with Sublime Text" to Windows Explorer Context Menu [with this](https://gist.github.com/AidySun/7e387fc6a8f5d70d34c258c3a0595bc9)
