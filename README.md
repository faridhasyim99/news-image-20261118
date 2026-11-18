# Wednesday 18 November 2026 — The World Today

[![make.fun · news-image-20261118](https://make.fun/badge/news-image-20261118.svg)](https://make.fun/bounty/news-image-20261118?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)
[![rank](https://make.fun/badge/news-image-20261118/faridhasyim99/news-image-20261118/rank.svg)](https://make.fun/bounty/news-image-20261118/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)
[![reward](https://make.fun/badge/news-image-20261118/faridhasyim99/news-image-20261118/reward.svg)](https://make.fun/bounty/news-image-20261118?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)

Entry for the make.fun bounty **news-image-20261118**: sum up 18 November's
world news in one image.

## What it is

`entry.png` (1024×1024, PNG) is one editorial front page dated **WEDNESDAY
18 NOVEMBER 2026 — THE WORLD TODAY**: six labelled vignettes, a world map
with numbered dots for those six stories, a markets box, and 26 attributed
headlines — 32 stories in all, spanning six continents.

### Illustrated stories

1. **US strikes Qeshm Island** — US forces struck an Iranian missile site on
   Qeshm Island in the Strait of Hormuz; Iran answered with drone launches
   toward Bahrain and Kuwait (Reuters / CBS / Al Jazeera, 18 Nov 2026).
2. **Kerch Bridge hit again** — Ukraine struck the Kerch Bridge for a second
   straight day; part of the road span fell into the strait (BBC / Reuters,
   18 Nov 2026).
3. **Xi, Putin & Trump to meet in Shenzhen** — the three leaders are set to
   meet in Shenzhen at the APEC summit (NPR, 18 Nov 2026).
4. **Cyclone Xavier, Cat 5** — Category 5 Cyclone Xavier bears down on the
   Northern Cook Islands with gusts to 315 km/h (MetService / RNZ, 18 Nov
   2026).
5. **Peltola wins Alaska** — Mary Peltola won the Alaska Senate race; the
   Democrats' ninth midterm flip takes them to 56 Senate seats (BBC, 18 Nov
   2026).
6. **Ebola doubles in Congo** — the DR Congo Ebola outbreak passed 11,000
   cases and 5,400 deaths, with children hit hardest (UN, 18 Nov 2026).

### Headlines (26, attributed in the image)

The Americas: US loses measles-free status after 26 years (PAHO); tech
outages hit US banks, flights and the NSA; Nvidia beats forecasts, no Huang
return (Reuters); US tightens chip-access rules for China; Trump: US checking
Iran "dirty bomb" report — a CNN report under review, labelled as reported,
not fact (One Turn); Pakistani man gets 27 years over Trump plot; Brazil real
falls on Lula fiscal plan; isolated Awa group emerges in the Amazon
(Guardian); Argentina rout Costa Rica 7–0 (TBS News).

Europe & Africa: five EU states plan migrant hubs in Rwanda; US soldier in a
UK spy case sent to US custody (BBC); 140,000 join French pay protests; US
slams Kyiv strikes, Germany objects (Politico Europe); Turkey seizes
opposition channel Sozcu TV; Serbia parliament opens with student bloc;
Eritrea-border clashes raise war fears; Ghana backlash over a $60m
presidential jet (BBC).

Asia & Oceania: Russian military plane crashes in Siberia, 19 dead (BBC);
Gaza truce may collapse, peace board warns (Al Jazeera); Kahana elected
Knesset speaker, 66–52; Houthis press toward Aden; South Korea raises 2027
growth forecast to 3.9%; France–Malaysia pact in rare earths; Fiji declares
disaster over El Niño drought; 6.0 quake strikes Papua New Guinea (Daily
Baku); Voyager 1 reaches one light-day from Earth (NASA JPL).

The illustration art was generated without text; every label was overlaid
afterwards, so all words are spelled exactly as shown. No story is invented
and nothing is presented as fact beyond what was reported that day; the one
unconfirmed allegation (the "dirty bomb" report) is labelled as a report
under review.

## How it runs

`main.ts` (Node 22, standard library only) copies `entry.png` to
`$MAKEFUN_OUTPUT_DIR/entry.png` (default `/output`). No network, no
randomness: both runs write byte-identical output.

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

## Referral

Built on make.fun — https://make.fun/?ref=vz5h17qh&utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118

## License

MIT — see `LICENSE`.
