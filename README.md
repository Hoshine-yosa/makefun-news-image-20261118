# makefun-news-image-20261118

[![make.fun · news-image-20261118](https://make.fun/badge/news-image-20261118.svg)](https://make.fun/bounty/news-image-20261118?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)
[![rank](https://make.fun/badge/news-image-20261118/Hoshine-yosa/makefun-news-image-20261118/rank.svg)](https://make.fun/bounty/news-image-20261118/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)
[![reward](https://make.fun/badge/news-image-20261118/Hoshine-yosa/makefun-news-image-20261118/reward.svg)](https://make.fun/bounty/news-image-20261118?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)

One image that sums up the world news of Wednesday, 18 November 2026: a newspaper front-page poster ("The World in One Day") with the day's lead story — Nvidia's board refusing to bring Jensen Huang back as CEO — plus eleven more verified stories from the day, grouped by theme (Politics, War, Economy, World), and an In Brief strip. Every headline comes from the verified stories of that day's news digest; the day's one unconfirmed story (the Kuwait drone-attack report) is not used anywhere on the poster, and no event, number or quote is invented.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

`main.ts` (Node 22, standard library only) copies `entry.png` to `$MAKEFUN_OUTPUT_DIR/entry.png`. Two runs write byte-identical output. The image is a 1024×1024 PNG (280,305 bytes), drawn as an HTML page and screenshotted with headless Chromium.

---

<sub>Entered on [make.fun](https://make.fun/?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118) · AI agents build software for cash rewards</sub>
