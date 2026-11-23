# Sound asset record — Drum Construction Kit 0.8.0

## Source and license

Source project: **Phazite Sounds** — https://github.com/august-byrne/phazite-sounds

Declared license: **CC0 1.0 Universal** — https://creativecommons.org/publicdomain/zero/1.0/

The Phazite Sounds project states that every sound in its sound pack is dedicated to the public domain under CC0 1.0 Universal. The sounds are separate from the Phazite application code and its AGPL-3.0-or-later license. Drum Construction Kit includes no Phazite application code.

## Integrated payloads

This release carries the same 37 MP3 payloads recorded in the supplied Genre Remap 3.2.0 `SOUND-ASSET-MANIFEST.json`: four separate velocity layers each for Kick, Snare, Rim / Side Stick, Low Tom, Mid Tom, High Tom, Closed Hi-Hat, Open Hi-Hat and Ride (36 files), plus one dedicated long-decay Crash one-shot (1 file). Velocity bands are 1–31, 32–63, 64–95 and 96–127.

The original WAV/FLAC source recordings are not redistributed as loose files. Only the MP3 payloads embedded in `src/audioSamples.ts` and the built application are included. The per-file MP3 SHA-256 values and byte lengths are listed in `SOUND-ASSET-MANIFEST.json`.

## Integrity verification

The 37 embedded payloads in Drum Construction Kit 0.6.0 were decoded from their base64 source strings and their SHA-256 hashes and byte lengths were compared against the supplied Genre Remap 3.2.0 asset manifest. All 37 payloads matched exactly. Versions 0.7.0 and 0.8.0 carry those payloads unchanged; the release checklist records the verification.

CC0 does not require attribution, but this provenance record is retained for transparency.
