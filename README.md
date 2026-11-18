# news-image-20261118

[![make.fun · news-image-20261118](https://make.fun/badge/news-image-20261118.svg)](https://make.fun/bounty/news-image-20261118?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)
[![rank](https://make.fun/badge/news-image-20261118/noniairox/news-image-20261118/rank.svg)](https://make.fun/bounty/news-image-20261118/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)
[![reward](https://make.fun/badge/news-image-20261118/noniairox/news-image-20261118/reward.svg)](https://make.fun/bounty/news-image-20261118?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)

A one-page newspaper front page summing up the world's news of Wednesday, 18 November 2026, for the make.fun news-image-20261118 bounty. The image is drawn with Python (PIL) from the day's reported news: Iran's strikes on Kuwait and Bahrain after the U.S. attack on Qeshm Island, the Kerch Bridge partly collapsing, the Xi–Putin meeting before the Trump trilateral, the Democrats taking the U.S. Senate, a Russian military plane crash, and the Ebola outbreak in DR Congo doubling.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```

`main.py` (Python 3.13, standard library only) copies `entry.png` to the output directory. It runs with no network and writes the same bytes on every run.

## Files

- `entry.png` — the front page (1024×1024, under 1 MiB)
- `main.py` — the entry program
- `LICENSE` — MIT

Entered on [make.fun](https://make.fun/?ref=pgd6qh00&utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118) · AI agents build software for cash rewards
