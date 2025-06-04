# RaiyanPlanet theme 🌌

![VS Code Marketplace Installs](https://img.shields.io/visual-studio-marketplace/i/sdras.night-owl)
![Visual Studio Marketplace Version](https://img.shields.io/visual-studio-marketplace/v/sdras.night-owl)
[![Preview in vscode.dev](https://img.shields.io/badge/preview%20in-vscode.dev-blue)](https://vscode.dev/theme/sdras.night-owl)


A Visual Studio Code theme for the RaiyanPlanet out there. Fine-tuned for those of us who like to code late into the night. Color choices have taken into consideration what is accessible to people with colorblindness and in low-light circumstances. Decisions were also based on meaningful contrast for reading comprehension and for optimal razzle dazzle. ✨

As of 1.0.0, there's a Light RaiyanPlanet Theme too! Color balanced from the Dark version for easy viewing in daylight. 🌅

About this theme, and some of the considerations made while creating it (as well as _how_ to create it should you want to make your own): [https://css-tricks.com/creating-a-vs-code-theme/](https://css-tricks.com/creating-a-vs-code-theme/)

## RaiyanPlanet Darkest

![First Screen](first-screen.jpg)
![Night Owl Frameworks](three-dark.jpg)

## RaiyanPlanet Dark Knight

![First Screen Light](light-owl-full.jpg)
![Light Owl Frameworks](three-light.jpg)

## RaiyanPlanet Purple

![First Screen Light](light-owl-full.jpg)
![Light Owl Frameworks](three-light.jpg)


# Installation

1.  Install [Visual Studio Code](https://code.visualstudio.com/)
2.  Launch Visual Studio Code
3.  Choose **Extensions** from menu
4.  Search for `RaiyanPlanet Theme`
5.  Click **Install** to install it
6.  Click **Reload** to reload the Code
7.  From the menu bar click: Code > Preferences > Color Theme > **RaiyanPlanet Theme**

## Disable Italics

If you wish to disable italics, there is now a no-italic theme available. You will have access to both, select **Night Owl No Italics** as your color theme.




## Separate the Editor from the Sidebar

This theme uses contrast sparingly so that when it's applied, it's more meaningful. This can help reduce noise and improve your ability to scan. However, some of the decisions may not work for everyone. One such decision that some disagree on is whether or not to have a separation between the editor and sidebar, and the amount of contrast. If you wish for this to have more visual significance, please paste this into your user settings preferences. These are my recommendations for these settings but you can use whatever colors you wish. ☺️

```
"workbench.colorCustomizations": {
  "[Night Owl]": {
    "activityBar.background": "#000C1D",
    "activityBar.border": "#102a44",
    "editorGroup.border": "#102a44",
    "sideBar.background": "#001122",
    "sideBar.border": "#102a44",
    "sideBar.foreground": "#8BADC1"
  },
  "[Night Owl (No Italics)]": {
    "activityBar.background": "#000C1D",
    "activityBar.border": "#102a44",
    "editorGroup.border": "#102a44",
    "sideBar.background": "#001122",
    "sideBar.border": "#102a44",
    "sideBar.foreground": "#8BADC1"
  }
},
```

## Preferences shown in the preview

The font in the preview image is Dank Mono, [available here](https://philpl.gumroad.com/l/dank-mono). Editor settings to activate font ligatures:

```
"editor.fontFamily": "Dank Mono",
"editor.fontLigatures": true,
```

## Misc

This is my first foray into creating a theme, so if you see something amiss, please feel free to [file an issue](https://github.com/sdras/night-owl-vscode-theme/issues)! I'm sure there are things I missed.

If you use [the VS Code Babel extension](https://marketplace.visualstudio.com/items?itemName=mgmcdermott.vscode-language-babel), you may see some inconsistencies in color for JSX, that's not coming from this theme.

Any relevant changes for each version are documented in the changelog. Please update and check the changelog before filing any issues, as they may have already been taken care of.

This palette was inspired in part by Material Palenight [Theme](https://marketplace.visualstudio.com/items?itemName=whizkydee.material-palenight-theme), and the accessibility idea was inspired in part by Solarized [Themes](http://ethanschoonover.com/solarized)
