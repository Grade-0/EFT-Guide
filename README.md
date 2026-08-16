# Tarkov Field Guide - https://grade-0.github.io/EFT-Guide/

# GitHub Pages package

This package contains the complete standalone Tarkov Field Guide and its locally hosted item icons.

## Publish with GitHub Desktop (recommended)

1. Extract this ZIP to a normal folder on your computer.
2. Open GitHub Desktop and choose **File → Add local repository**.
3. Select the extracted `Tarkov_Field_Guide_GitHub` folder.
4. If prompted, choose **create a repository here**, then publish it to GitHub.
5. On GitHub, open the repository's **Settings → Pages**.
6. Under **Build and deployment**, choose **Deploy from a branch**.
7. Select the `main` branch and `/ (root)` folder, then save.
8. GitHub will display the public Pages address after deployment finishes.

GitHub does not unpack an uploaded ZIP into a Pages site automatically. Extract the ZIP before adding the folder with GitHub Desktop.

## Package contents

- `index.html` — complete guide and embedded Tarkov data snapshot
- `assets/items-001/` through `assets/items-053/` — 5,226 locally hosted item icons, with no more than 100 files in any folder
- `assets/image-manifest.json` — image completeness and package-size record
- `.nojekyll` — tells GitHub Pages to publish the files without Jekyll processing

The guide stores progress and appearance choices in the visitor's browser. Publishing a new version does not transfer those browser-local settings between devices.

## Updating later

The guide's **Check online** button can compare its bundled game data with current Tarkov data. Newly added items from a future online update may not have a local image until the GitHub package is rebuilt with a newer image set; the guide will show an initials placeholder for any missing image.

## Attribution

Game names and imagery belong to their respective owners. Community item data and image links originate from the Tarkov.dev ecosystem. This fan-made guide is not affiliated with or endorsed by Battlestate Games.
