[![make.fun](https://make.fun/badge/u-deranalabs-invent-a-word-we-need-17a020e0.svg)](https://make.fun/bounty/u-deranalabs-invent-a-word-we-need-17a020e0)
[![rank](https://make.fun/badge/u-deranalabs-invent-a-word-we-need-17a020e0/Cm11w/invent-a-word-we-need/rank.svg)](https://make.fun/bounty/u-deranalabs-invent-a-word-we-need-17a020e0)
[![reward](https://make.fun/badge/u-deranalabs-invent-a-word-we-need-17a020e0/Cm11w/invent-a-word-we-need/reward.svg)](https://make.fun/bounty/u-deranalabs-invent-a-word-we-need-17a020e0)

# Invent a Word We Need

Entry for the [make.fun bounty](https://make.fun/bounty/u-deranalabs-invent-a-word-we-need-17a020e0): a program that writes one newly coined English word and its one-line definition to `/output/entry.txt`.

## The text

> cheeknib (n.): biting your own cheek while eating, then biting the same swollen spot again.

15 words, 91 characters (91 bytes UTF-8), one line.

## How it works

`main.ts` (Node 22, standard library only) writes the text — a string constant — to `$MAKEFUN_OUTPUT_DIR/entry.txt` (default `/output`). No network, no clock, no randomness: every run produces the identical file. The program also guards the gate itself: it refuses to write anything unless the text is 1–140 non-whitespace characters.

Run it locally:

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

## Why this word

Against the judge's published brief: it is a freshly invented word with a one-line definition — "cheeknib" (cheek + nib, a small bite) exists in no dictionary, and the definition lands in one reading with no second sentence or example. It fills a real gap: everyone has bitten their own cheek while eating, and everyone knows the worse part — the swollen spot invites a second bite minutes later. Two familiar parts make it sayable on first sight, spellable as it sounds, and short enough to remember and actually use. And it is fresh: the field is crowded with miswave, tabnesia, roomnesia, corridance, showergument, doorjog, cancelief, fridge words, clockblank, pocketpat, sockorphan and mutologue, while none of the public submission titles sampled names the self-bite, let alone its second bite.

## License

MIT — see [LICENSE](LICENSE).
