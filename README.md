
# macOS Modern Theme


## Big Sur

Added light Big Sur Versions + Icons. Dark coming soon ...

---

macOS Modern is a set of Visual Studio Code themes styled to match native macOS as closely as possible.  Updated to include dark + light versions and a few minimal icon themes. Reapply both (icon and color) themes if you have problems. I HIGHLY recommend using the settings below for best results. Screenshots need to be updated; there is a lot more options now. The dark theme has just got an overhaul!

**macOS Modern - Xcode Low Key** + **macOS Modern Minimal Icons**
![Minimal](https://github.com/davidbwaters/macOS-modern-vscode-theme/raw/master/images/screenshot1.png)

**Dark**
![dark](https://github.com/davidbwaters/macOS-modern-vscode-theme/raw/master/images/screenshot1b.png)

**macOS Modern - Xcode Default** + **macOS Modern - Color Icons**
![Xcode](https://github.com/davidbwaters/macOS-modern-vscode-theme/raw/master/images/screenshot2.png)

**macOS Modern - Xcode Low Key** + **macOS Modern - Color Icons**
![Low Key](https://github.com/davidbwaters/macOS-modern-vscode-theme/raw/master/images/screenshot3.png)

---

## Setup & Tweaks

There are a few settings that should be added to your User Settings to really transform the look to better match OS X.  The zoom level and native title bar make a huge difference in the overall look of VSCode.  I also prefer to hide the Activity Bar, which can be done from the View menu.

### Highly Recommended

```json
 // macOS Modern Tweaks
"editor.fontSize": 12,
"editor.fontFamily": "SF Mono, Monaco",
"editor.tabSize": 2,
"editor.fontWeight": "normal",
"window.titleBarStyle": "native",
"window.nativeTabs": true,
"window.zoomLevel": -0.5,
"workbench.iconTheme": "macOS-modern-color-icon-theme",

// Disable Tab File Icons
"workbench.editor.showIcons": false,
// Disable Red Sidebar Errors
"problems.decorations.enabled": false,

```

### Extension Tweaks

If you choose to hide the activity bar, you can install the "Activitus Bar" extension to add the activity bar buttons to your status bar.  Add these settings to theme the "Activitus Bar" and "Project Manager" extensions to match Modern macOS.

```json
 // Activitus Bar
"activitusbar.activeColour": "#615F61",
"workbench.activityBar.visible": true,

// Project Manager
"projectManager.treeview.visible": false,
```

### Optional Additions

You can optionally hide the minimap.

```    json
// Disable Minimap
"editor.minimap.enabled": false,

```

### Activity Bar Badge Background

You can change the activity bar badge background with these settings. Add the line for the color you want to `workbench.colorCustomizations`

```json
// Workbench Color Tweaks
"workbench.colorCustomizations": {
  "activityBarBadge.background": "#1a8bfb", // blue
  "activityBarBadge.background": "#f84339", // red
},
```

---

## Extras

Light and dark VSCode icons are also included in full quality (don't use the small preview below) on the GitHub repo or in the extension folder in:
`~/.vscode/extensions/davidbwaters.macOS-modern-theme/extras/app-icons`
You could also download the files from the repo [folder](https://github.com/davidbwaters/macOS-modern-vscode-theme/tree/master/extras) by clicking the name of the `icns` or `png` and clicking the "Download" button. You can use the free app [LiteIcon](https://freemacsoft.net/liteicon/) to change the icon.

![VSCode](https://github.com/davidbwaters/macOS-modern-vscode-theme/raw/master/images/icon-big-sur-insiders.png) ![VSCode Insiders](https://github.com/davidbwaters/macOS-modern-vscode-theme/raw/master/images/icon-big-sur-insiders.png)

![Old Dark](https://github.com/davidbwaters/macOS-modern-vscode-theme/raw/master/images/icon-dark.png) ![Old Light](https://github.com/davidbwaters/macOS-modern-vscode-theme/raw/master/images/icon-big-sur-insiders.png)

There are also Sketch design files with all the icons. Feel free to use, tweak, add, etc. If you find them useful, a shoutout would be appreciated.

---

David B. Waters

:) :) :)
