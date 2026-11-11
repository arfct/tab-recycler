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

A link to a Figma file opens a browser tab that launches the desktop app and then stays open. Tab Recycler is a Chrome extension that closes such tabs. It runs on three kinds of page: Figma's, Zoom pages whose address ends in "success", and Dropbox Paper's redirect to its desktop app.

On Zoom and Dropbox Paper the tab closes five seconds after the page loads. On Figma, five seconds after the page loads, the extension looks in it for the words "in Figma app", and it starts the same five-second count only when it finds them. The extension requests no browser permissions.

Version 1.3 is on the Chrome Web Store, last updated in November 2022. The repository is at 1.4, which extends the Figma match from file addresses to every Figma page.

JavaScript, Chrome Manifest V3. 2020.
