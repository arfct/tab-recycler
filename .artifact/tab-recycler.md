---
title: Tab Recycler
date: 2020-04
status: released
category: product
tags:
  - browser-extension
url: https://chromewebstore.google.com/detail/tab-recycler/nbcnplijgopjihcgplgbhagnpopnomdi
links:
  chrome_web_store: https://chromewebstore.google.com/detail/tab-recycler/nbcnplijgopjihcgplgbhagnpopnomdi
  source: https://github.com/arfct/tab-recycler
media:
  - src: extension-page.png
    caption: Version 1.3 on its page in the browser's extension settings, loaded here in Chrome for Testing, with the three sites it may run on
    alt: A browser settings page headed Extensions, with a card for Tab Recycler showing a green recycling mark, a switch turned on, a one-line description, version 1.3 and a list of three site addresses for Figma, Zoom and Dropbox Paper
  - src: store-illustration.png
    caption: The illustration on the Chrome Web Store listing, with the icons of Figma and Zoom in a browser window under the extension's mark
    alt: A drawing of the top left corner of a browser window with one empty tab, a large green recycling mark at its right, and the Figma and Zoom app icons side by side below the toolbar
unconfirmed: [date, status]
---

Links to Figma files, Zoom meetings and Dropbox Paper documents each open a browser tab that launches the desktop app and then stays open. Tab Recycler is a Chrome extension that closes those tabs. It runs on three kinds of page: Figma file pages, Zoom pages whose address ends in "success", and Dropbox Paper's redirect to its desktop app.

On Zoom and Dropbox Paper the tab closes five seconds after the page loads. On Figma, five seconds after the page loads, the extension looks in it for the words "in Figma app", and it starts the same five-second count only when it finds them. The extension requests no browser permissions; the first image is its page in the browser's settings, which lists the sites it may run on.

Version 1.3 is on the Chrome Web Store, last updated in November 2022.

JavaScript, Chrome Manifest V3. 2020.
