# Current audio sources

The four original Meowgnificent piano themes use fixed, repeating motifs and simple triad accompaniment written for this game. No existing soundtrack or demo MIDI was copied.

## Recorded piano

- **Salamander Grand Piano v3**, recorded by **Alexander Holm**, 48kHz/24-bit, soft velocity layer4.
- Original: https://archive.org/details/SalamanderGrandPianoV3
- FLAC conversion / SFZ remap: **kinwie**, sfzinstruments: https://github.com/sfzinstruments/SalamanderGrandPiano
- Pinned revision: `3382bf9496bba2486f5ab0de55a264d1dfc38404`.
- License: **Creative Commons Attribution 3.0 Unported**, https://creativecommons.org/licenses/by/3.0/ . Full text is `docs/SALAMANDER-LICENSE.txt` and `tools/audio/Salamander-LICENSE.txt`.
- Modifications: selected soft piano recordings were decoded, retuned to the score pitches, sequenced into the project's original score, filtered gently and rendered as OGG loops. The original SFZ mapping is not bundled.
- Sample SHA256/source manifest: `tools/audio/piano_samples.json`; original score: `piano_score.json`; renderer: `render_piano_score.py`.

## Effects

The 17 short, clean effects are original deterministic synthesis, revised from the v0.40 palette with gentler pitch, attack/release and a 3kHz low-pass. No external effect recording is used. They are rendered offline by `tools/generate_sound_palette.py`.

## Earlier drafts

The earlier GeneralUser GS / FluidSynth chamber-music authoring scripts and score remain in tools/audio for provenance. They no longer generate the current runtime recordings. GeneralUser GS is by S. Christian Collins; its full license remains `GeneralUser-GS-LICENSE.txt`. No SoundFont or full piano sample library is bundled with the game. Only finished recordings and attribution are distributed.
