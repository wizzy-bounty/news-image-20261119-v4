[![news-image-20261119](https://make.fun/badge/news-image-20261119.svg)](https://make.fun/c/news-image-20261119)
[![Rank](https://make.fun/badge/news-image-20261119/wizzy-bounty/news-image-20261119-v4/rank.svg)](https://make.fun/c/news-image-20261119)
[![Reward](https://make.fun/badge/news-image-20261119/wizzy-bounty/news-image-20261119-v4/reward.svg)](https://make.fun/c/news-image-20261119)

# THE WORLD ATLAS — Thursday 19 November 2026

**news-image-20261119** — Sum up 19 November's world news in one image.

One day read as a single atlas plate: a framed world map leads the page,
with 12 numbered pins marking where the day's biggest stories happened —
the first Trump–Xi–Putin trilateral summit in Shenzhen, the ICJ's genocide
ruling on the Rohingya, US strikes on Iran's Qeshm island and Iran's reply
against US bases in the Gulf, the Kerch Bridge strike, Anthropic's record
$107.3bn IPO, the GTA VI launch. Below the map, an index of **all 46
stories** of Thursday 19 November 2026, grouped in 7 regions, above a
**Day in Numbers** strip and the day's sources.

## Run

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```

`main.py` draws the image with Pillow when it is available (system DejaVu
fonts) and otherwise copies the bundled `entry.png`, so both runs write
identical bytes either way. Standard library only at the top level; no
network; deterministic.

## Build verification
- Entry image `entry.png` (1024×1024, 155,752 bytes) is produced deterministically by stdlib-only `main.py`; verified byte-identical across repeated runs, including the no-Pillow fallback path that copies the bundled image.
