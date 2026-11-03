# gameboi vision
Unedited AI playthroughs, published the [RAPP Vision](https://github.com/kody-w/rapp-vision) way: every publication is one
work with two layers, the **guided video** (the clip, MP4 + WebM) and the **live replay** (the exact button log the AI
pressed, driven on the public record of that run at the [gameboi arena](https://kody-w.github.io/gameboi-arena/)).
Separate repo, same pattern and the same validator; the player page is RAPP Vision's MIT player with this registry.

Watch: https://kody-w.github.io/gameboi-vision/ · publish one: `gameboi publish <stack> <clip.mp4> --out <this repo>`.
Validation: `python3 rapp-vision/scripts/validate_publications.py channel.json --ffprobe-local` (run from a rapp-vision checkout).
