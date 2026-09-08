# AMV Prompt Science — Epistemology (Brent lock 2026-09-07)

## Model
A prompt is a **low-resolution translator**:
- **In:** discrete nouns / dials (text, enums, numbers)
- **Between:** model latent space (Suno / Imagine / editor) — mostly opaque
- **Out:** full audio + visual data (waveform, spectrum, pixels, motion, cut timing)

We cannot control the middle directly. We become experts by:
1. Naming every **measurable** property of the *output* that matters to quality.
2. Mapping each to an **input dial** that reliably moves that property (or noting tool-gap).
3. Preferring dials with **non-diminishing returns** — if twiddling it never changes the keepable cut, drop it.
4. Treating any existing video as a **specimen**: extract the catalog values (science), then override nouns for the next tribute (not clone).

## Extraction rule
If we cannot measure it from a finished mp4+audio (or from locked lyrics/bible text), it is not a T0 noun until we invent a measurement.

## Pitch example
`VocalPitchCenter` / `PitchRangeSemitones` — extractable from audio; Suno style/lyrics move it imperfectly; still first-class because missing it explains "why does this sound wrong vs ref."

## Human description → dial (Brent 2026-09-07)
Anything a person could use to **describe** that song or picture can become a **setting** — *only when it is helpful to do so*.

Filter:
- If a human would naturally say it ("faster", "more bass", "two dancers", "cuts on the drop") → candidate noun.
- If setting it never changes a keepable cut, or we cannot move it with Suno/Imagine/edit → leave it out (or T2 watchlist).
- Completeness means covering the *useful* description space, not every adjective in English.

## Corpus → formula (Brent 2026-09-07)
1. Collect favorites and/or best-performing cuts in a genre.
2. Extract dials from each specimen.
3. Find what they **have in common** (intersection / tight ranges).
4. Over time that intersection becomes an empirical **ideal AMV formula**.
5. New AMV = formula + tweaked inputs (lyrics, thesis, cast, world) — not a clone of any one ref.

## Speed × efficiency (Brent 2026-09-07)
1000 settings is too many to review per video. Too few settings waste gens, toss cuts, burn time and tokens. Catalog size optimizes **speed and efficiency together**, not noun count. Add a dial only if skipping it measurably wastes keepable footage or tokens.

## Chess parallel (Brent 2026-09-07)
Even if there were 1000 or a million settings, most don't change. Like chess: near-infinite legal moves, but the corpus of moves that don't suck is definable. Same with AMVs — IdealRanges / house formula = that non-sucking corpus; per-AMV work is small overrides (lyrics, thesis, cast, world).

## Common vs scrutiny (Brent 2026-09-07)
- **Commonly adjusted** settings = the default checklist / UI for most AMVs.
- Settings that need more scrutiny are *not* forced into every review — the user just **talks more about those into the prompt**.
- Full catalog still exists for extraction/corpus science; the human-facing surface stays the common set.

## Radical transparency on X (Brent 2026-09-07)
When sharing the finished AMV, **post the settings/dials with the video** — radical transparency (Elon-flavored). Show the common dials that made the cut; scrub secrets/personal paths; invite others to retarget the formula.

## Imagine control (Brent 2026-09-08)
Imagine is hard to control — but even handcuffed criminals are controllable. **Strict nouns / dials / shotlist = the handcuffs.** Unslopped constraints make the wild model finishable.
