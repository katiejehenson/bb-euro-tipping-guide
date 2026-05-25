# European Tipping Guide — Booked & Beyond

> **Live site:** https://katiejehenson.github.io/bb-euro-tipping-guide/

A branded travel reference guide covering tipping customs across 48 European, transcontinental, and sovereign nations — built for Booked & Beyond clients.

---

## Deploy to GitHub Pages

### First time setup

```bash
# 1. Clone the repo
git clone https://github.com/katiejehenson/bb-euro-tipping-guide.git
cd bb-euro-tipping-guide

# 2. Copy index-bb.html → index.html (GitHub Pages serves index.html from root)
cp index-bb.html index.html

# 3. Commit and push
git add index.html README.md
git commit -m "Launch: Booked & Beyond European Tipping Guide"
git push origin main
```

### Enable GitHub Pages

1. Go to **Settings → Pages** in the repo
2. Source: `Deploy from a branch`
3. Branch: `main` / folder: `/ (root)`
4. Click **Save**

Site will be live at `https://katiejehenson.github.io/bb-euro-tipping-guide/` within ~60 seconds.

---

### Updating the guide

Whenever you get a new `index-bb.html` file:

```bash
cp index-bb.html index.html
git add index.html
git commit -m "Update: [describe changes]"
git push origin main
```

GitHub Pages auto-redeploys on every push to `main`.

---

## What's in the guide

- **48 countries** across 3 groups: EU Members (27), Other European Nations (16), Transcontinental (6)
- **8 tipping categories** per country with expandable detail
- **Grouped dropdown** selector with flag emoji
- **3-flag recent history** bar in the hero
- **Universal transfers & guide** reference card (8 tiers)
- **Universal etiquette tips** card
- Fully branded to **Booked & Beyond** brand standards (Warm Slate, Cherry, Dusty Rose, Blush White / Raleway + Outfit)
- Single HTML file — zero dependencies, no build step

---

*Booked & Beyond LLC · Tools · Workflows · Training*
