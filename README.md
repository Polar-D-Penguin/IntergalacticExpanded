# Fundamental - Intergalactic Expanded
Hello! This is a mod for Fundamental! See bottom for instructions on how to play.
## Features:
* 2 new elements (working)
* New universe milestones (Not working, needs heavy balancing)
* New void reward (Works, but does not get awarded. It is always unlocked. WIP)
## Planned Features:
* New intergalactic upgrades
* New end type (requirement: U0 end)
* Another new end type (requirement: 10,000 Dark Energy)
* New darkness upgrades

#### Should be supported by:
1. Modern browsers,
2. Mobile devices,
3. Screen readers

---
### If you plan do anything with this, then you need to:
#### `npm install` - This will install everything that was used in here.
#### Keep in mind it will install latest version of dependencies, so something might break.
---

## Special NPM commands: (Configure first)
1. `npm build` - to convert all .ts files into a single .js (browsers cant use .ts).
2. `npm watch` - same as build, but will convert automatically, when detects any changes.
##### You can add `:map` if you need to see from which file and line, error has came from in a browser.
3. `npm lint` - to check if there are any obvious mistakes in .ts file, also helps to keep same style.
4. `npm fix` - will auto fix lint for you that it can by itself.

This mod could be hard to play. To play, download GitHub desktop app and open the repository. Then, Open it in vs code and, in the terminal, type: `npm install`, then `npm build` or `npm watch`. If you get any errors, use the #3 and #4 commands above. Once you've done that, and you have no problems, go to run, then either `Start Debugging` or `Run without Debugging`. Then select the browser you want to open in, and it should open the game. If it doesn't work, you can edit the `launch.json` file, removing the `url` and `webroot` arguments and replacing them with `"file": ${workspaceRoot}/index.html`
