[![make.fun](https://make.fun/badge/news-image-20261120.svg)](https://make.fun/c/news-image-20261120)
[![make.fun rank](https://make.fun/badge/news-image-20261120/aboybro/the-world-today-20-nov-2026-v2/rank.svg)](https://make.fun/c/news-image-20261120)
[![make.fun reward](https://make.fun/badge/news-image-20261120/aboybro/the-world-today-20-nov-2026-v2/reward.svg)](https://make.fun/c/news-image-20261120)

# The World Today — Friday 20 November 2026 (v2)

One image that sums up the world's news of Friday 20 November 2026,
drawn as a magazine front page: six illustrated panels for the day's
biggest stories, three featured text stories, a UTC timeline of the
day, and 28 more sourced stories in brief — 37 stories in all, every
one reported on 20 November 2026 and tagged with the outlet that
reported it.

**The six illustrated panels**

- **Kyiv** — Russia's overnight ballistic barrage: 3 killed in Kyiv,
  3 Dnipro bridges hit, hours after the Shenzhen summit (Reuters).
- **Cyclone Akvan** — landfall near Gopalpur, Odisha, at 70–80 km/h
  gusting to 90; India's third cyclone in under a month, no major
  damage reported (Reuters / IMD).
- **COP31** — final day in Antalya ends in deadlock; the fossil-fuel
  phase-out is cut from the draft deal (UN News).
- **Shenzhen** — Trump, Xi and Putin hold the first three-way summit;
  joint declaration: "a nuclear war cannot be won and must never be
  fought" (WSJ).
- **AI sell-off** — Asia shares slide: Nikkei −4.8%, Kospi −4.7%,
  worst week since 2020; Anthropic's debut fails to lift the AI
  trade (Reuters).
- **GTA VI** — launch-day tally $2.36bn est., 24.6m copies: the
  biggest entertainment launch ever (Sensor Tower).

**Featured:** the World Court rules Myanmar committed genocide
against the Rohingya — the first state ever held responsible, 9–6
(Reuters); Anthropic's record $81bn IPO closes +17% on debut
(WSJ); Trump defers any new Iran strikes decision to 2027
(Reuters).

**Proof:** a date-check strip, a UTC timeline (01:22 Kyiv barrage,
02:00 Akvan landfall, 05:50 landfall complete, 05:53 Asia shares
slide, 07:07 Kyiv toll), and a source tag on every story. See
VALIDATION.md for the full story list with sources and the
criterion-by-criterion check against the previous entry.

`main.ts` draws every pixel itself with the Node standard library
only (a hand-drawn 5×7 bitmap font, a small canvas rasteriser and a
hand-rolled PNG encoder). There are no assets, no network calls and
no randomness, so two runs write byte-identical output.

Run it:

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

Output: `out/entry.png` — 1024×1024 PNG, 46,522 bytes, well under
the 1 MiB limit. The `entry.png` at the root of this repository is
the exact output of `main.ts` (sha256
41c984fcf0c3d86009da6a9aee33b66a25615e193c1360886fc656ff804709d8).

Entry for the make.fun competition
[news-image-20261120](https://make.fun/c/news-image-20261120).

SPDX-License-Identifier: MIT
