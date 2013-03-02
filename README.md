# Node-Webkit starter
Initial starting setup for developing an app with node-webkit.
It's setup so that all files can be required node style, and basic hotkeys for page
reloading and devTools are setup.

Coffeescript can also be used for any of the modules.

## Default libraries
- underscore
- backbone
- jquery-1.9.1.min.js
- jquery.hotkeys.js

## Setting up a build system in sublime text 2.

Unzip the node-webkit.zip file and put the node-webkit app into your Applications folder

`Tools => build system => new build system`

Paste this into the window:

```json
{
  "cmd": ["node-webkit", "${project_path:${folder}}"],
  "working_dir": "${project_path:${folder}}",
  "path": "/Applications/node-webkit.app/Contents/MacOS/"
}
```

Open the index.html file and select: `Tools => Build`

The window should open up (check under your editor window)