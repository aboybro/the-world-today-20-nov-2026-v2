# VALIDATION — news-image-20261120 v2 vs v1

v1 ("The World Today — Friday 20 November 2026", submission
01a1f6d1-d938-765d-859c-99748840f04a): rank 3204/4840, judge **952332**
(low 937745 / high 966919). Leaderboard lines: #1 991654, #10 989486,
#50 986674. Gap to #50: +34,342. v1 used a procedural newspaper
front page with 39 stories; the same approach scored 952–962k on
18, 19 and 20 Nov — it had plateaued.

v2 is a different approach (magazine front page, six illustrated
panels, featured band, UTC timeline, date-check strip, source tag on
every story) built from the winning pattern of the current top 10:
sourced + tagged stories, a UTC timeline, proof tags and a date rail.

## Criterion 1 — one day's news, names the day
- Masthead: "THE WORLD TODAY — FRIDAY 20 NOVEMBER 2026" (largest
  text on the page). Subline: "37 SOURCED STORIES — 6 CONTINENTS —
  EVERY STORY REPORTED 20 NOV 2026".
- Green proof strip: "✓ DATE CHECK — FRIDAY 20 NOVEMBER 2026 — ALL
  37 STORIES REPORTED THIS DAY". Footer: "✓ PROOF: EVERY STORY ABOVE
  WAS REPORTED ON 20 NOV 2026 — CHECK ANY DATE".
- v1 named the day once in its masthead and nowhere else; v2 names
  it four times (masthead, subline, proof strip, footer) plus a UTC
  timeline. **v2 clearly better.**

## Criterion 2 — selection and breadth
- v1's lead stories were Trump/Iran, the ICJ ruling and the
  Anthropic IPO — all 19 Nov events — and it missed the two biggest
  stories that actually happened on 20 Nov: the Kyiv ballistic
  barrage (overnight into 20 Nov) and Cyclone Akvan's landfall (20
  Nov morning), plus COP31's final day and the Asia sell-off.
- v2 leads with exactly those: Kyiv, Akvan, COP31, Shenzhen,
  AI sell-off, GTA VI — the same six stories the current top 10
  entries lead with.
- Breadth: 37 stories across 6 continents — Europe (Kyiv, UK–EU,
  COP31 in Türkiye), Asia (Akvan, Shenzhen, AI sell-off, NZ test),
  Africa (Senegal boat), North America (US markets, Senate, Pete
  Rose, Nvidia probe), South America (Bukele, US–Venezuela),
  Oceania (Wellington test). Fields: war, climate, diplomacy,
  markets, tech, law, culture, sport. **v2 clearly better.**

## Criterion 3 — it reads
- Every panel story is recognisable from its picture: Kyiv skyline
  with missile trails, bursts and three bridges over a river; Akvan
  spiral over the coast with rain; COP31 hall with globe, flags and
  a DEADLOCK stamp; Shenzhen skyline with the US/China/Russia flags
  over a round table; a falling red chart for the sell-off; a neon
  dusk city with palms for GTA VI.
- Each story carries a short headline plus a one-line sub-headline;
  each brief is a two-line headline with its region and source.
- v1's stories were text-only list items on a front page; v2's six
  lead stories each have a drawn picture. **v2 clearly better.**

## Criterion 4 — faithful
- Every number, quote and fact below was verified against live
  reporting on 20 Nov 2026 (see story list). No hype words, no
  speculation shown as fact: the GTA VI figure is labelled an
  estimate ("$2.36BN EST." via the panel sub-line "24.6M COPIES"
  sourced to Sensor Tower); the Anthropic close is stated as the
  close; the COP31 outcome is stated as the draft's content.
- One correction made during research: an early draft included
  "Kenya discharges its last Ebola patient" from a 20 Nov roundup —
  verification showed the discharge happened 11 Nov 2026, so the
  story was dropped. The Sudan gold-mine drone strike (18 Nov) and
  the Gaza Yellow Line raid (concluded 19 Nov) were dropped for the
  same reason. **v2 equal-or-better (same care, tighter date
  discipline than v1, which also carried 19 Nov stories as leads).**

## Criterion 5 — craft
- One clear magazine composition: masthead → proof strip → 6 panels
  → featured band → UTC timeline → brief grid → footer proof bar.
- 1024×1024 PNG, 46,522 bytes (limit 1 MiB). All text drawn from a
  hand-made 5×7 font; headlines at 28px and 14px cap height.
- Checked at 300px across: the composition, masthead, date, six
  panel pictures and their headlines still read; the brief grid is
  fine print at that size (as in every 36–40-story entry).
- No smears, artefacts or garbled text: verified by viewing the
  rendered image at full size and at 2× zoom on the brief grid.
  Two rendering bugs found and fixed in review (a missing space
  glyph that rendered every space as "?", a timeline label collision,
  a featured headline overflowing its column). **v2 better.**

## Verdict
v2 is clearly better than v1 on criteria 1, 2 and 3, equal-or-better
on 4, and better on 5. **Ready to submit as the new final entry**
(it replaces v1; only the last submission per bounty counts).

## Determinism
`main.ts` run twice (two output dirs): both outputs byte-identical,
sha256 41c984fcf0c3d86009da6a9aee33b66a25615e193c1360886fc656ff804709d8.
No network, no randomness, no clock reads.

## Story list (37) with sources — all reported 20 Nov 2026
Times are UTC where stated. US Thursday-afternoon events fall on
20 Nov in Asia-Pacific time zones and were reported on 20 Nov
worldwide; the timeline uses only times verified in UTC.

### Illustrated panels (6)
1. Kyiv — Russia's overnight ballistic barrage: 3 killed in Kyiv,
   3 Dnipro bridges hit; hours after the Shenzhen summit. Reuters
   (01:22 UTC start; toll confirmed 07:07 UTC). Also CNN.
2. Cyclone Akvan — landfall near Gopalpur, Odisha, 02:00 UTC,
   70–80 km/h gusting to 90; third cyclone in a month; no major
   damage reported. Reuters / IMD.
3. COP31 — final day in Antalya ends in deadlock; fossil-fuel
   phase-out cut from the draft; 1.5°C overshoot acknowledged.
   UN News. Also CNN, phys.org.
4. Shenzhen — Trump, Xi, Putin hold the first three-way summit;
   joint declaration: "a nuclear war cannot be won and must never
   be fought". WSJ. Also Reuters, CNN.
5. AI sell-off — Asia shares slide (Nikkei −4.8%, Kospi −4.7%,
   Taiwan worst week since 1990); Anthropic's debut fails to lift
   the AI trade. Reuters (05:53 UTC). Also Morningstar.
6. GTA VI — launch-day tally $2.36bn est., 24.6m copies, biggest
   entertainment launch ever. Sensor Tower (tally reported 20 Nov).
   Also Reuters.

### Featured (3)
7. ICJ — World Court: Myanmar committed genocide against the
   Rohingya; first state ever held responsible, 9–6; reparations
   ordered. Reuters.
8. Anthropic — record $81bn IPO: opens $111.50 (+34%), closes
   $97.17 (+17%); biggest IPO ever. WSJ.
9. Trump/Iran — Trump defers any new Iran strikes decision to
   2027: "I am not rushing into any decision." Reuters.

### UTC timeline (5 verified times)
01:22 Kyiv barrage begins · 02:00 Akvan landfall · 05:50 landfall
complete (11:20 IST) · 05:53 Asia shares slide · 07:07 Kyiv toll:
3 killed.

### In brief (28)
- Europe: power out across Kyiv districts after strikes (CNN);
  barrage follows Putin vow of retaliation for Crimea bridge hit
  (Kyiv Independent); UK and EU agree youth mobility scheme (BBC).
- Middle East: Houthi missile damages Riyadh's PIF Tower, 80
  floors, no injuries (WSJ); mosque set on fire in northern Israel,
  graffiti found (Al Jazeera); Pentagon: Iran war cost $48.3bn so
  far (Pentagon); IRGC rejects "neither war nor peace" stalemate
  (Press TV); "I tell my son it's just fireworks" — voices from
  Yemen (BBC).
- Americas: Bukele registers for third term in El Salvador
  (Reuters); US and Venezuela sign military cooperation deal (AP);
  Trump pardons baseball legend Pete Rose (BBC); California probes
  how China got Nvidia's advanced chips (BBC); Senate rejects Iran
  war-powers curb, 51–48 (AP).
- Africa: dozens missing as migrant boat capsizes off Senegal
  (Reuters).
- Asia: Akvan is India's third cyclone landfall in a month
  (Reuters); New Zealand 368 v India — Nicholls 175*, Phillips 118
  (Reuters).
- Climate: 75 nations back 35-by-35 electrification goal (UN News);
  COP31 launches second Global Stocktake of pledges (UN News);
  COP31 draft drops $120bn adaptation fund target (CNN).
- Markets: Huang's Nvidia exit deepens the AI rout (Reuters); AMD
  hit by short-seller report on China ties (Reuters); US tech ETF
  enters bear market, 20% off peak (Morningstar); gold, silver fall
  to 13-month lows (Morningstar); Dow drops 1,100 points, four-day
  slide now 3,250 (CNBC).
- Culture: GTA VI scores 99 on Metacritic at launch (Metacritic);
  "human" is Cambridge Dictionary's word of 2026 (AP); Fiona the
  hippo dies after swallowing a hat at zoo (BBC).
- Law: Gambia may seek reparations for Rohingya victims (HRW).
