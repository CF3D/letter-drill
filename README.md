# Letter Drill

A quick, one-shot drill for the 29 Arabic letters (from *Towards Reading the Qur'an, Part One*).
Open it and you get a random set of 10 letters to work through. Refresh, reopen or tap **New set** for a fresh one.
Nothing is tracked or saved. Works offline and installs to your phone's home screen.

## Put it on GitHub Pages

1. On github.com, click **+ › New repository**. Name it `letter-drill`, make it **Public**, then **Create repository**.
2. On the new repo page, click **uploading an existing file**.
   Drag in **everything inside this folder**: `index.html`, `sw.js`, `manifest.webmanifest`,
   `.nojekyll`, and the `fonts` and `icons` folders. Then click **Commit changes**.
   (If `.nojekyll` is hidden in Finder, press Cmd+Shift+. to show hidden files. The app works without it.)
3. Go to **Settings › Pages**. Under *Branch*, choose **main** and **/ (root)**, then **Save**.
4. After a minute or two, your app is live at
   `https://YOUR-USERNAME.github.io/letter-drill/`

## Add it to your iPhone

Open the link in **Safari**, tap **Share › Add to Home Screen › Add**.
It opens full-screen from its own icon and works without internet.

## Updating later

If you change any file, also change `VERSION` at the top of `sw.js` (e.g. `v1` → `v2`)
so phones pick up the new version. Close and reopen the app twice to see it.

Fonts: Amiri, Amiri Quran, EB Garamond, Nunito Sans — SIL Open Font Licence (see `fonts/`).
