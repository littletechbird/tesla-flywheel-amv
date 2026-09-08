# Common AMV Dials (human-facing)

~32 commonly adjusted settings. Full science catalog (~89) stays for extraction/corpus.
Scrutiny/rare dials: talk into the prompt — do not force into every review.
On X ship: post these common dials with the video (radical transparency).

## Audio / song
| ID | Label | Type | Range | Default |
|----|-------|------|-------|---------|
| TotalVideoLength | Length | float_s | 90–300 | 180 |
| BPM | Tempo | float | 90–150 | 128 |
| GenreStyle | Genre / style | string | free | electro-dance |
| EnergyCurve | Energy arc | enum | flat / rise / verse-low-chorus-high / relentless | verse-low-chorus-high |
| LowEmphasis | Bass / wubs | enum | low med high max | high |
| VocalStyle | Vocal delivery | enum | sung rap chant mixed | sung |
| HookPhrase | Stamp hook | string | 1–8 words | — |
| LyricStructure | Section map | list | I V P C B O | V-C-V-C-B-C |
| RhymeScheme | Rhyme | enum | free AABB ABAB none | AABB |
| LyricDensity | Syllables/bar | enum | sparse med dense | med |

## Cast / continuity
| ID | Label | Type | Range | Default |
|----|-------|------|-------|---------|
| MainCharacterCount | Main cast size | int | 1–4 | 2 |
| MainCharacterIds | Who | list | named | bird, hatch |
| CameoDensity | Cameos | enum | none rare moderate high | rare |
| AnthropomorphLevel | Art style | enum | photoreal hybrid anime comic | anime |
| PhotorealBan | Ban photoreal humans | bool | T/F | T |
| CrowdPresent | Crowds/extras | bool | T/F | F |

## World
| ID | Label | Type | Range | Default |
|----|-------|------|-------|---------|
| LocationCount | Distinct sets | int | 2–12 | 6 |
| LocationList | Set names | list | free | — |
| WorldPalette | Colors | list | 3–8 | neon club |
| LightingGrammar | Light style | enum | soft hard neon fire practical | neon |
| ProductIconography | Prop/product density | enum | none light heavy | light |
| TextOnScreen | Burned text | enum | none rare heavy | none |

## Picture / edit
| ID | Label | Type | Range | Default |
|----|-------|------|-------|---------|
| AspectRatio | Aspect | enum | 16:9 9:16 1:1 | 16:9 |
| PocketCount | Still→I2V pockets | int | 8–24 | 12 |
| I2VDurationSec | Clip length | float | 2–12 | 5–8 |
| MotionEnergy | Motion | enum | idle soft bounce frantic | bounce |
| CameraGrammar | Moves | list | static pan punch orbit whip | punch |
| CutDensity | Cuts/min | float | 15–60 | 30 |
| AvgShotLengthSec | Avg shot | float | 1–6 | 2–4 |
| CutGrid | Beat grid | enum | 1 2 4 8 | 4 |
| TransitionType | Transitions | enum | hard flash dissolve whip | flash/hard |
| SplitScreenUse | Splits | enum | never rare motif | rare |
| DeadTailPolicy | Freeze tails | enum | forbid trim allow | forbid+trim |
| ChipAway | Molecule polish | bool | T/F | T |

## Thesis / export
| ID | Label | Type | Range | Default |
|----|-------|------|-------|---------|
| Tone | Emotional tone | enum | tribute satire romance fun dark | fun |
| ThesisOneLiner | Thesis | string | 1 sentence | — |
| AntiList | Hard antis | list | banned | — |
| ShortsCropMode | Shorts crop | enum | center fit-blur stack-split | stack when split else fit |
| CaptionsPolicy | Captions | enum | none timed-SRT | timed-SRT |

**Count: 32 common dials.** Everything else = prompt talk or full catalog for science.
