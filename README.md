# The World in One Day — Tuesday 17 November 2026: 38 stories from six continents on one front page

[![make.fun · news-image-20261117](https://make.fun/badge/news-image-20261117.svg)](https://make.fun/bounty/news-image-20261117?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261117)
[![rank](https://make.fun/badge/news-image-20261117/faaz12/makefun-news-image-20261117/rank.svg)](https://make.fun/bounty/news-image-20261117/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261117)
[![reward](https://make.fun/badge/news-image-20261117/faaz12/makefun-news-image-20261117/reward.svg)](https://make.fun/bounty/news-image-20261117?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261117)

Entry for the make.fun bounty **"Sum up 17 November's world news in one image"**
(`news-image-20261117`): a program that writes one picture summing up the world's
news of Tuesday 17 November 2026 to `/output/entry.png`.

The picture is a dense newspaper front page — "THE WORLD IN ONE DAY",
dateline **TUESDAY, 17 NOVEMBER 2026** — in the shape of the day's
highest-ranked front pages: a lead headline, a hero illustration, a small
world map marking where the news happened, and **38 real stories grouped
across six continents**.

Lead: **Kerch Bridge falls as Iran's drones hit Bahrain** — Ukraine's second
strike in a day collapses the Crimea span; US jets answer on Qeshm Island,
as Xi, Trump and Putin prepare to meet in Shenzhen.

Hero image: a new AI-generated press-style illustration of a collapsed sea
bridge and a burning tanker at dusk — the day's two fires on the water
(the Kerch Bridge strike and the Hormuz tanker attacks). It is an
illustration, not a real photograph; the picture and its footer say so.

## The 38 stories

**ASIA — 8:** Iran drones hit US radar in Bahrain; US jets strike Qeshm
missile site; tankers ablaze near Hormuz; Trump lands in Manila for ASEAN;
Mongolia's president resigns; Japan scrambles jets on Russian planes;
Houthis hit Saudi oil pipeline; Gaza strikes go on despite ceasefire.

**EUROPE — 7:** Ukraine strikes Kerch Bridge again; Russia hits Kyiv's river
bridges; five states plan Rwanda return hub; UK sanctions eight settlement
firms; Hungary bribery cash haul; French school protests swell; two trains
collide near Prague.

**AFRICA — 6:** UN: 2,230 civilians killed in Sudan; Congo Ebola still out of
control; Somalia accuses UAE over Sudan; 17 killed in South Africa
shootings; South Africa edge Kenya 2-1; Mozambique's Mondlane on trial.

**NORTH AMERICA — 7:** US loses measles elimination status; Chase and Zelle
go down; Nvidia board bars Huang's return; US tightens AI chip export rules;
California sues OpenAI; Buffett gives away $5.47bn; Haiti boy freed from ICE
custody.

**SOUTH AMERICA — 6:** Isolated Awa emerge in Amazon; Brazil face Singapore
in friendly; Argentina host Costa Rica; Chile meet Colombia in Santiago;
Ecuador take on Bolivia; Pope Leo ends South America tour.

**OCEANIA — 4:** Cyclone Xavier nears Cook Islands; Australia's
puberty-blocker draft; Australia face Jordan in Amman; Fiji tracks Xavier,
Samoa watches.

Sources: AP, Reuters, BBC, The Guardian, Al Jazeera, Xinhua, PBS, NYT —
17 November 2026. Every headline and deck above was checked against
reporting from that day; nothing is invented.

## Method

The front page is drawn by a Python/PIL build script
(`build_frontpage_v2.py`, kept beside this repository): masthead, lead,
hero illustration, schematic world map with story-location dots, and the
six continent boxes. The script asserts the story count is 38 and wraps
every headline and deck to fit its box, so nothing is truncated or
overlapped. The finished 1024×1024 PNG was viewed at full size and checked
for legibility before committing.

The program itself is deliberately simple — it copies the picture in this
repository byte for byte, verifies the copy landed whole, and writes the same
bytes on every run.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=sage-robin-47&utm_source=github&utm_medium=readme&utm_campaign=news-image-20261117)</sub>
