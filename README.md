# Show Whitespace Obsidian Plugin
A plugin for [Obsidian](https://obsidian.md) which shows whitespace in the editor.

Utilizes code from [cm-show-invisibles](https://github.com/coderaiser/cm-show-invisibles)
by [coderaiser](https://github.com/coderaiser)

This project uses Typescript to provide type checking and documentation.  
The repo depends on the latest [plugin API](https://github.com/obsidianmd/obsidian-api) in Typescript Definition format, which contains TSDoc comments describing what it does.

**Note:** The Obsidian API is still in early alpha and is subject to change at any time!

## Compatibility

Custom plugins are only available for Obsidian v0.9.7+.

The current API of this repo targets Obsidian **v0.9.7**. 

## How to install the plugin

- Download the [Latest release](https://github.com/deathau/cm-show-whitespace-obsidian/releases/latest)
- Extract the `cm-show-whitespace-obsidian` folder from the zip to your vault's plugins folder: `<vault>/.obsidian/plugins/`  
Note: On some machines the `.obsidian` folder may be hidden. On MacOS you should be able to press `Command+Shift+Dot` to show the folder in Finder.
- Reload Obsidian
- If prompted about Safe Mode, you can disable safe mode and enable the plugin.
Otherwise head to Settings, third-party plugins, make sure safe mode is off and
enable the plugin from there.

## Notes
This is all very expermental at the moment, so parts might not work, etc.  
There are certain css classes, etc that can interfere with it and make the whitespace characters stand out more.  
Check out the styles.css in the release to see what styles are added to be customized.

## Development
If you want to contribute to development and/or just customize it with your own
tweaks, you can do the following:
- Clone this repo.
- `npm i` or `yarn` to install dependencies
- `npm run build` to compile.
- Copy `manifest.json`, `main.js` and `styles.css` to a subfolder of your plugins
folder (e.g, `<vault>/.obsidian/plugins/cm-show-whitespace-obsidian/`)
- Reload obsidian to see changes

Alternately, you can clone the repo directly into your plugins folder and once
dependencies are installed use `npm run dev` to start compilation in watch mode.  
You may have to reload obsidian (`ctrl+R`) to see changes.

## Pricing
Huh? This is an open-source plugin I made *for fun*. It's completely free.
However, if you absolutely *have* to send me money because you like it that
much, feel free to throw some coins in my hat via
[PayPal](https://paypal.me/deathau)