# Ballot & Bone

A pixel-art political god sandbox in the spirit of WorldBox. Tribes grow into nations, form parties and governments, hold elections, stage coups, trade, go to war and race into space while you watch, nudge or wreck them with dozens of god powers.

It runs in any modern browser and installs on your phone or computer as an app. It works offline once installed.

## Features

- **Eras:** ten eras from the Stone Age to the Ascendant Age, with buildings, people and vehicles that change in every era.
- **People:** autonomous people with families, jobs, beliefs, ambitions and life stories.
- **Politics:** real ideologies and governments: elections, parties, coups, revolutions, laws, capitalism and inequality.
- **Diplomacy and war:** trade routes, currencies and market crashes, the United Nations, generals, fortress walls, navies, tanks and nuclear deterrence.
- **Disasters and rebuilding:** bombed buildings show damage, towns rebuild, and attacks trigger surges of patriotism.
- **Refugees:** people flee wars and disasters. Neighbors welcome them or close their borders, camps form, and families go home after the war.
- **Districts:** rich neighborhoods with mansions and slums with shacks, depending on how unequal a town is.
- **Infrastructure:** railways and trains, highways with traffic, ports with cranes, airports with flights, and power grids with blackouts.
- **The future:** climate change, a space race, and AI and robots that can lead to utopia, unemployment uprisings or a machine takeover.
- **World tools:** a premade world map, random map types and climates, world seeds you can share, six save slots, graphs and history.
- **God powers:** possess and control a person, drop missiles, summon dragons, crown kings, rig elections, trigger the Singularity and more.

## Play it online with GitHub Pages

1. Create a new repository on GitHub (for example `ballot-and-bone`).
2. Upload everything in this folder to the repository, keeping the `fonts` and `icons` folders. Include the hidden `.nojekyll` file.
3. In the repository go to **Settings → Pages**.
4. Under **Build and deployment**, set **Source** to **Deploy from a branch**, pick the `main` branch and the `/ (root)` folder, then click **Save**.
5. After a minute or two the game is live at `https://YOUR-USERNAME.github.io/ballot-and-bone/`.

## Install it as an app

Open the GitHub Pages link, then:

- **Android (Chrome):** tap the ⋮ menu → **Add to Home screen** → **Install**.
- **iPhone/iPad (Safari):** tap the **Share** button → **Add to Home Screen**.
- **Windows/Mac/Chromebook (Chrome or Edge):** click the install icon in the address bar, or open the menu → **Install Ballot & Bone**.

It opens full screen like a normal app and keeps working without internet.

## Updating the game

1. Replace `index.html` in the repository with the new version.
2. Open `sw.js` and change the version name, for example from `const VERSION = 'bb-v1';` to `const VERSION = 'bb-v2';`.
3. Commit the changes. Installed apps pick up the update the next time they're opened while online. If a player doesn't see it, they can close and reopen the app.

## Saves

Your worlds are saved in the browser or app on your own device, so they don't sync between devices. To move a world to another device, use **Export** in the save menu and import the file on the other device.

## Files

| File | Purpose |
|---|---|
| `index.html` | The whole game (one self-contained file) |
| `manifest.webmanifest` | App name, icons and colors used when installing |
| `sw.js` | Service worker that caches the game for offline play |
| `fonts/` | Pixel fonts, bundled so the game works offline |
| `icons/` | App icons |
| `.nojekyll` | Tells GitHub Pages to serve the files as they are |
