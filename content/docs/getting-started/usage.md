---
title: Usage
type: docs
prev: installation
---
## Installing a version of a tool
The only pre-installed plugin is go because go is needed to compile plugins you download. You might not have go installed but you can install it using MTVM of course! 
You can download go using this command:
```
mtvm install go latest
```
Then set it as the current go version using this command:
```
mtvm use go latest
```
But you can also install versions directly from the use command using the \--install flag, like this:
```
mtvm use go latest --install
```
If you want to install a specific version, just replace latest with the version number. Latest is special because it retrieves the version number of the latest version of the tool, so you don't have to look for the newest version yourself!