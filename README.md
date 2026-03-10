# WikiPacks 🃏

A browser card game where you collect cards based on Wikipedia articles. The rarer the article (by monthly views), the rarer the card.

## 🎮 Play

**[▶ Play WikiPacks](https://usernameapetri.github.io/wikipacks/)**

> Replace `usernameapetri` with your GitHub username after deploy.

## Features

- 📦 Open Daily & Gold packs
- ✦ 5 rarity tiers — Common · Uncommon · Rare · Epic · Legendary
- 🏆 Grade system — B · A · S · SS · SSS
- ⚡ Power score based on real Wikipedia pageviews
- 🌟 Showcase your best 6 cards
- ⚔ Leaderboard — compete by Showcase Power
- 👤 Player profiles
- 🔄 Pity system — every 10 packs guarantees a Gold Pack

## How power works

```
Power = log10(views) × 22 × rarityMult × gradeMult + rarityBonus
Max = 1000
```
Open `index.html` directly in any browser — no server needed.
