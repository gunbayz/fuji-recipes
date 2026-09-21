# My Fuji

A small phone app for Fujifilm X-T5 film simulation recipes: browse 118 X-T5 recipes from Fuji X Weekly, favorite them, and set up the camera's C1–C7 custom slots with settings listed in the exact order and wording of the camera menu.

**Live:** https://gunbayz.github.io/fuji-recipes/

## Get it on your phone

1. Open the link above in **Safari** on your iPhone.
2. Tap **Share** → **Add to Home Screen** → **Add**.
3. Open it once while online. After that it works offline.

On a Mac, open the link in Safari and choose **File → Add to Dock**.

## How it works

- **My camera**: your seven slots, named by situation (C1 Bright sun, C2 Overcast, C3 Golden hour, C4 Indoor/tungsten, C5 Night, C6 Black & white, C7 Wildcard). Tap a filled slot to see its recipe, or an empty one to browse recipes for that situation.
- **Library**: search, filter by situation, favorites or what's in the camera. Tap the star to favorite.
- **Recipe**: photo, look, when to use it, and every setting in camera-menu order. ISO and exposure compensation are listed separately because they live on the dials, not in the slot.
- **Put in a camera slot → Setup**: a checklist for the camera's `MENU › IMAGE QUALITY SETTING › EDIT/SAVE CUSTOM SETTING` screen. When replacing a recipe, **Only changes** shows just the settings that differ. The screen stays awake while you work.
- **Backup (⋯ on My camera)**: favorites and slots are saved on each device. Export a backup file and import it on another device to copy them over.

## Files

- `index.html`: the whole app
- `data/recipes.json`: the recipe library (settings in X-T5 menu order, situations, photos)
- `sw.js`: offline support. **Bump `CACHE` (e.g. `my-fuji-v2`) whenever anything changes.**
- `manifest.webmanifest`, icons: home-screen app setup

Recipes and photos © Fuji X Weekly (fujixweekly.com); each recipe links to its original post.
