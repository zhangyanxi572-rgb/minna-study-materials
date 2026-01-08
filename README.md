minna-study-materials

This repository will host StarDict-format dictionaries and related study materials converted from the eggrolls JLPT 10k Anki deck (source: https://github.com/5mdld/anki-jlpt-decks and AnkiWeb: https://ankiweb.net/shared/info/832276382).

Purpose:
- Provide GoldenDict/StarDict dictionary packages generated from the Anki deck (entries include Japanese headword, kana, Chinese definitions, and example sentences).
- Include conversion scripts, usage instructions, and sample files for review before full publishing.

Structure (initial):
- scripts/         # conversion scripts (Python)
- samples/         # sample StarDict files (small subset) and sample audio
- README.md        # this file
- LICENSE          # MIT license

Usage / Notes:
- The sample package contains the first 200 entries for review. After you confirm the sample, the full 10k conversion and audio packaging will be generated and uploaded as Release assets.
- Audio files (MP3) will be provided as Release assets to avoid committing large binaries into the git history.
- Source attribution and disclaimer: This project uses data from 5mdld/anki-jlpt-decks and AnkiWeb. Please refer to the original project for license/attribution. The maintainer of this repository does not claim ownership of the original content.
