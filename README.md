# Better Active Tab Indicator

Adds a bright line next to the active tab to better highlight it.

All custom colors must be in hexadecimal format, including the # before the digits. You can find an open-source online color tool [here](https://colorpicker.dev/#687cff), developed by [Brandon Mathis](https://github.com/imathis) (unaffiliated).

![Active tab indicator example](/images/indicatorexample.png)

## Updating manually

The [Zen mod store](https://github.com/zen-browser/theme-store) is frozen, so the store version of this mod is outdated. To get the latest version:

1. Install **Better Active Tab** from the Zen mod store, if you haven't already.
2. Open `about:support` and click **Open Directory** next to **Profile Folder**.
3. Go to `chrome/zen-themes/d8b79d4a-6cba-4495-9ff6-d6d30b0e94fe/`.
4. Replace `chrome.css` and `preferences.json` with the ones from this repository:
   - [chrome.css](https://raw.githubusercontent.com/HliasOuzounis/zen-browser-better-active-tab-indicator/master/chrome.css)
   - [preferences.json](https://raw.githubusercontent.com/HliasOuzounis/zen-browser-better-active-tab-indicator/master/preferences.json)
5. In **Settings → Zen Mods**, turn the mod off and on again (or restart Zen) to apply the changes.

If the store version is updated later, Zen may overwrite these files with the store's version.
