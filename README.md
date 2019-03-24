# example-docsify-config
This is an example configuration for docsify

Note that the docsify.min.js and some plugin files, aswell as theme files are **not** the original but modified. That is why these files are being loaded from a cdn server that has these modified files (https://cdn.jannik.ml (I own this))

Since this file is also used for docsify itself:

# Overview

* [subject](subject/subject)

The following files under a (not committed) directory called `static` should be created:
- android-chrome-192x192.png
- android-chrome-256x256.png
- favicon-16x16.png
- favicon-32x32.png
- favicon.ico
- apple-touch-icon.png
- safari-pinned-tab.svg
- manifest.json

In addition to that in the root directory these files should be created:
- browserconfig.xml
- mstile-150x150.png

Also an assets folder for any assets is recommended. Since the included dark mode inverts every image to make it work in the dark mode simple transparent and black svgs work best. When color is needed try to keep in mind how the dark mode functions.
