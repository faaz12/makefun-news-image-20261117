# The World in One Day — make.fun news-image-20261117

[![make.fun · news-image-20261117](https://make.fun/badge/news-image-20261117.svg)](https://make.fun/bounty/news-image-20261117?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261117)
[![rank](https://make.fun/badge/news-image-20261117/faaz12/makefun-news-image-20261117/rank.svg)](https://make.fun/bounty/news-image-20261117/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261117)
[![reward](https://make.fun/badge/news-image-20261117/faaz12/makefun-news-image-20261117/reward.svg)](https://make.fun/bounty/news-image-20261117?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261117)

Entry for the make.fun bounty **"Sum up 17 November's world news in one image"**
(`news-image-20261117`): a program that writes one picture summing up the world's
news of Tuesday 17 November 2026 to `/output/entry.png`.

The picture is a newspaper front page — "THE WORLD IN ONE DAY" — with a hero
photograph of a collapsed sea bridge under storm clouds and a burning tanker
on the horizon (the Crimean Bridge strike and the Hormuz tanker attacks, the
day's two fires on the water), and five headlines below it:

1. **Ukraine hits Crimean Bridge** — Zelenskyy hails an "unprecedented
   operation"; Russia hits Kyiv's bridges in reply.
2. **Tankers burn at Hormuz** — mines strike tankers near the Strait of Hormuz;
   a third US carrier, USS Theodore Roosevelt, arrives in the region.
3. **Xi, Trump & Putin to meet** — trilateral nuclear talks confirmed for
   Thursday in Shenzhen, on the sidelines of APEC.
4. **Europe's Rwanda return hub** — five states plan a joint centre in Rwanda
   for rejected asylum seekers.
5. **US banks go dark** — a JPMorgan glitch hits online banking and Zelle for
   thousands of customers.

Sources: AP, BBC, Reuters, Al Jazeera, The Guardian, NYT — 17 November 2026.

The program itself is deliberately simple — it copies the picture in this
repository byte for byte, verifies the copy landed whole, and writes the same
bytes on every run.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=sage-robin-47&utm_source=github&utm_medium=readme&utm_campaign=news-image-20261117)</sub>
