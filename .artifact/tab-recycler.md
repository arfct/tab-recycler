---
title: Tab Recycler
date: 2020-04
category: product
tags:
  - browser-extension
links:
  chrome_web_store: https://chromewebstore.google.com/detail/tab-recycler/nbcnplijgopjihcgplgbhagnpopnomdi
  source: https://github.com/arfct/tab-recycler
icon_shape: none
media: []
unconfirmed:
  - date
---

Tab Recycler is a Chrome extension that closes the browser tabs left open when a link launches a desktop app. A link to a Figma file, a Zoom meeting or a Dropbox Paper document opens a tab that launches the app and then stays open. Tab Recycler runs a content script on those pages and closes the tab a few seconds later. On Figma it closes the tab only when the page shows its "in Figma app" message.

Version 1.3 is on the Chrome Web Store, last updated in November 2022. The repository is at version 1.4, which extends the Figma match from file URLs to every Figma page.

JavaScript, Chrome Manifest V3. 2020.
