# Release checklist — Drum Construction Kit 0.8.0

## Verified from supplied source and build artifacts
- [x] HGT License 1.0 added for original project material; third-party licenses remain separate.
- [x] Phazite Sounds source page identifies sound pack as CC0 1.0 Universal.
- [x] 37 embedded MP3 payloads in 0.6.0 source match the supplied Genre Remap 3.2.0 manifest by SHA-256 and byte length.
- [x] Sound source, CC0 deed, velocity bands and per-file hashes documented.
- [x] Ableton Extensions SDK 1.0.0-beta.0 license text included.
- [x] SDK package and CLI archives excluded from public source archive; SDK runtime remains bundled only inside `.ablx`.
- [x] Package/manifest/build label set to 0.8.0; the existing 0.7.0 application bundle was repackaged with only the embedded build label changed (no fresh SDK compile in this environment).
- [x] Automated regression suite: 119/119 tests passed.
- [x] Maintainer confirmation recorded: vector logo (`src/logo.ts`) is an original HGT graphic, geometrically inspired by Mondrian; it is not a reproduction or use of Mondrian artwork. Covered by HGT License 1.0.
- [x] Maintainer confirmation recorded: raster banner (`src/banner.ts` / `src/banner.txt`) and related visual elements are original HGT artwork created with AI assistance based on HGT's own descriptions and creative direction; geometric language is inspired by Mondrian, not reproductions of Mondrian artworks.
- [ ] Install and launch `.ablx` in Ableton Live 12.4.5 or later and audition all ten sound roles / four velocity bands on the target system.

## Release status
**Documentation update:** The maintainer has confirmed the HGT authorship and AI-assisted creation of the vector logo, raster banner and related visual elements. Host-side installation and audition should still be completed on the target Ableton Live system.
