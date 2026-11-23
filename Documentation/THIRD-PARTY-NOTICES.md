# Third-party notices — Drum Construction Kit 0.8.0

This release contains original HGT project material, CC0 audio assets from Phazite Sounds, and a bundled runtime portion of the Ableton Extensions SDK. The terms below are separate; the HGT License 1.0 does not override them.

## Phazite Sounds — audio assets

The 37 embedded MP3 payloads are derived from the Phazite Sounds project, which dedicates its sound pack to the public domain under CC0 1.0 Universal. The CC0 dedication permits use, modification, commercial use and redistribution without attribution. The sounds are separate from Phazite application code; no Phazite application code or AGPL-licensed application component is included. See `SOUND-ASSETS.md`, `SOUND-ASSET-MANIFEST.json` and https://github.com/august-byrne/phazite-sounds. CC0 deed: https://creativecommons.org/publicdomain/zero/1.0/.

## Ableton Extensions SDK

The extension uses `@ableton-extensions/sdk` version `1.0.0-beta.0`. The `.ablx` bundles the SDK runtime code required by the application. Ableton's SDK license expressly grants rights to develop applications and publish, sell or otherwise distribute those applications under the developer's own brand, while prohibiting distribution of the SDK itself or parts of it outside the application. The bundled runtime is included only as part of this application package; the SDK package, SDK archive and CLI archive are not included in the public source ZIP. The complete SDK license text is provided in `ABLETON-EXTENSIONS-SDK-LICENSE.md`. Obtain the SDK separately from Ableton for development/building.

## Ableton and Ableton Live trademarks

Ableton and Ableton Live are names and/or trademarks of Ableton AG, used only to identify compatibility. This project is independent and is not endorsed by Ableton AG. Observe Ableton's branding and UI guidelines.

## Build-time tools

Node.js, the TypeScript compiler, and the system `zip` utility are build-time tools and are not bundled as application runtime components by this project. Install and use them under their respective licenses. No other third-party runtime library is intentionally bundled in the `.ablx` beyond the Ableton SDK runtime noted above.

## Original HGT artwork — logo, banner and visual elements

The HGT vector logo, raster banner and related visual elements are original artwork created by Hans-Georg Tröster (HGT), with AI assistance based on HGT's own descriptions and creative direction. Their geometric visual language is inspired by the visual principles associated with Piet Mondrian; they are not reproductions, tracings or uses of original Mondrian artworks. These graphics are original HGT project material and are covered by the HGT License 1.0, subject to its terms. No Mondrian artwork or third-party logo asset is embedded in these HGT graphics.
