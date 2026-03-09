# WikiPacks 🃏

A browser card game where you collect cards based on Wikipedia articles. The rarer the article (by monthly views), the rarer the card.

## 🎮 Play

**[▶ Play WikiPacks](https://YOUR_USERNAME.github.io/wikipacks/)**

> Replace `YOUR_USERNAME` with your GitHub username after deploy.

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

## Deploy to GitHub Pages

1. Create a new repo on GitHub (e.g. `wikipacks`)
2. Push this folder:
   ```bash
   git init
   git add .
   git commit -m "initial"
   git remote add origin https://github.com/YOUR_USERNAME/wikipacks.git
   git push -u origin main
   ```
3. Go to repo **Settings → Pages → Source: main branch → Save**
4. Your game is live at `https://YOUR_USERNAME.github.io/wikipacks/`

## Local

Open `index.html` directly in any browser — no server needed.
