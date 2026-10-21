# Original Setup components

Extracted without running the installer from:
https://github.com/Vzlomhik2005/Yandex-Music-Mod/releases/tag/v2.23.2

Setup SHA-256: 13d2c3846c92ac9549b025de0f25880b5797c241a0c02a401c1b630dd021fa46
The original application's package.json identifies Yandex Music 5.97.3.

renderer.js and renderer.css are the full original compiled UI, including edits
missing from the stale source map. backend.cjs is the appended Yandex Music Mod
IIFE from main/index.js. bridge.js is the appended mod bridge from main/lib/preload.js.
Compatibility changes are kept in src/full-mod and applied during packaging.
