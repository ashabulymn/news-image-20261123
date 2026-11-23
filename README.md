# Monday 23 November 2026 in One Image — 35 Stories, 9 Regions

![Competition](https://make.fun/badge/news-image-20261123.svg)
![Rank](https://make.fun/badge/news-image-20261123/ashabulymn/news-image-20261123/rank.svg)
![Reward](https://make.fun/badge/news-image-20261123/ashabulymn/news-image-20261123/reward.svg)

Entry for the make.fun bounty **[Sum up 23 November's world news in one image](https://make.fun/bounty/news-image-20261123)** by @ashabul-yamin.

## The image

One 1024×1024 front page that sums up **Monday 23 November 2026**:

- **3 heroes** — the Dymer toll rising through Monday's rescue (11 dead), the COP31 backlash after the talks closed with no deal, and Indonesia confirming 24 dead in the Cikande factory fire
- **10 tiles**, one giant fact each — NATO's emergency council over 3 Kh-101 missiles in Poland, the Kospi's −4% Monday, 22 Hormuz attacks in November, unrest across 28 Bangladesh districts, Shuri Castle reopening after 7 years, the WHO's Ebola plea, Wellington's drawn Test (720/9), Vaar's $4.43B deal, 9 shot in California, India's record $13B inflow
- **22 wire briefs**, a UTC timeline of the day, and a dotted world map whose 35 numbered pins match the 35 stories
- **9 regions, minimum 3 stories each** — Europe 6 · Middle East 4 · Africa 4 · South Asia 3 · East Asia 4 · SE Asia 4 · Americas 3 · Oceania 4 · Global 3

Every story carries a verification badge (CONFIRMED / OFFICIAL / REPORTED / CLAIM) and a named source. A DATE CHECK box on the page itself excludes the day's traps: stories filed Monday that actually happened Sunday (the Seoul minister's resignation, the Democrats' 258th House seat) or Thursday (the ICJ's Myanmar genocide ruling).

## Run it

```bash
python3 main.py            # writes /output/entry.png
MAKEFUN_OUTPUT_DIR=out python3 main.py   # or a directory of your choice
```

`main.py` (Python 3.13, standard library only, no network) copies the committed `entry.png` beside it into the output directory, byte for byte — two runs always produce identical bytes.

## License

MIT — see [LICENSE](LICENSE).
