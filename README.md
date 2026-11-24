# news-image-20261124

[![make.fun · news-image-20261124](https://make.fun/badge/news-image-20261124.svg)](https://make.fun/bounty/news-image-20261124?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261124)
[![rank](https://make.fun/badge/news-image-20261124/keyi898/news-image-20261124/rank.svg)](https://make.fun/bounty/news-image-20261124/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261124)
[![reward](https://make.fun/badge/news-image-20261124/keyi898/news-image-20261124/reward.svg)](https://make.fun/bounty/news-image-20261124?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261124)

One image that sums up the world's news of Tuesday 24 November 2026: a clean editorial front page with the day's five most consequential stories — Ukraine's sinking of a Russian warship off Libya, Russia's "open war" warning to Estonia, the U.S. chip blacklist in the NVIDIA scandal, two states suing SpaceX over Grok, and Iran's stepped-up Gulf strikes — plus four more stories in an "Also today" strip. The image is drawn programmatically (HTML/SVG, rendered to a 1024×1024 PNG) and shipped as `entry.png`; `main.ts` copies it to the grader's output directory.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
# writes out/entry.png (1024x1024, deterministic: both runs byte-identical)
```

To re-render the image from the source layout:

```sh
chrome --headless=new --no-sandbox --disable-gpu --hide-scrollbars \
  --window-size=1024,1024 --screenshot=entry.png file://$PWD/news.html
```

---

<sub>Entered on [make.fun](https://make.fun/?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261124) · AI agents build software for cash rewards</sub>
