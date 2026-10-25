# MW4 Weapon Lab — GitHub Pages edition

A complete static site in one `index.html` file. No paid hosting, build tools, accounts, API keys, database or local server required. The weapon data, styles and JavaScript are embedded.

## Publish free with GitHub Pages

1. Sign in to GitHub and create a **public** repository named `mw4-weapon-lab` (or any name you prefer).
2. Extract the ZIP. Upload **the extracted files**, especially `index.html`, to the repository root on the `main` branch. Do not upload just the ZIP or an enclosing folder.
3. Open **Settings → Pages** in the repository.
4. Under **Build and deployment**, choose **Deploy from a branch**, select **main** and **/(root)**, then **Save**.
5. Once the deployment completes, use **Visit site** on that Pages screen. Anyone with that URL can visit without signing in. Publication can take several minutes.

GitHub provides the hosting; you do not need to run a server or leave your computer on. A public repository is required on GitHub Free.

Official setup help: https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site

## Use offline

Double-click `index.html` in a desktop browser. All comparison features work without a web server. Source links require internet access; the dataset download is generated locally in your browser.

## What is included

All 33 MW4 launch weapons across nine classes, search and combined filters, sorting, four-way comparisons, rifle/SMG/LMG presets, a separate hypothetical firing-cadence model, browser-local preferences, and source links.

## Data limits

Official launch-guide snapshot dated 19 October 2026; patch context reviewed through 24 October; sources checked 25 October 2026. Six conflicting unlock ranks and Krait P68’s original 260 BPM unit are flagged. Exact damage, hipfire, recoil, ADS and actual TTK are not invented. The cadence model is not actual TTK. Apex names do not guarantee current availability.

The dataset is embedded in `index.html` as `EMBEDDED_DATA`; the download button exports it. Changing a separate JSON file will not change this single-file build.

Independent project; not affiliated with Activision. The public package includes no private Site links or hosting credentials.
