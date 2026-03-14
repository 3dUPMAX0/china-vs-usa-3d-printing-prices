# 🖨️ China → USA 3D Printing Bridge

> Helping everyday Americans access the world's most affordable 3D printing ecosystem — powered by open data and AI.

---

## 🌏 Our Mission

3D printing has the power to change how American families live, create, and fix things.

Imagine printing a replacement part for a broken kitchen appliance instead of buying a new one. Imagine your kid designing and printing their own toys. Imagine small makers and hobbyists building businesses from their garage — without needing deep pockets.

**That future is already here. But it's locked behind a price wall.**

The printers and filaments that make this possible are manufactured in China — yet most Americans pay 30–120% more than the Chinese retail price, without knowing it. This project exists to close that information gap, step by step.

---

## 🗺️ Roadmap

### ✅ Phase 1 — Price Transparency (Now)
Manually tracked, community-verified price comparison of top Chinese 3D printing brands between China (JD.com / Taobao) and the USA (Amazon / official stores).

### 🔄 Phase 2 — AI-Powered Market Intelligence (Next)
We plan to use AI to automate data collection and continuously sync Chinese market information for the English-speaking community:
- Automated price tracking across Chinese e-commerce platforms
- AI-translated product releases, reviews, and maker community insights from China
- Smart alerts when significant price drops or new models launch in China
- Integration with tools like n8n, Make, and open APIs to keep data fresh without manual effort

---

## 🏭 Brands Covered

| Brand | Known For |
|-------|-----------|
| [Bambu Lab 拓竹](data/bambu-lab.md) | High-speed FDM, multi-color |
| [Creality 创想三维](data/creality.md) | Entry-level FDM, Ender series |
| [Elegoo](data/elegoo.md) | Resin (MSLA), Neptune FDM |
| [FlashForge 闪铸](data/flashforge.md) | Enclosed FDM, education |
| [Anker Make 安克](data/anker-make.md) | AnkerMake M series |

---

## 📊 Price Snapshot (Updated: 2026-03)

### Bambu Lab — Printers

| Model | China (¥) | China (USD eq.) | USA (USD) | Markup |
|-------|-----------|-----------------|-----------|--------|
| A1 mini | ¥1,699 | ~$234 | $299 | +28% |
| A1 mini Combo | ¥2,299 | ~$317 | $449 | +42% |
| A1 | ¥2,199 | ~$303 | $399 | +32% |
| A1 Combo | ¥2,799 | ~$386 | $499 | +29% |
| P1S | ¥3,999 | ~$551 | $699 | +27% |
| X1C | ¥4,999 | ~$689 | $1,199 | +74% |

### Bambu Lab — Filament (per 1kg spool)

| Type | China (¥) | China (USD eq.) | USA (USD) | Markup |
|-------|-----------|-----------------|-----------|--------|
| PLA Basic | ¥79 | ~$11 | $24 | +118% |
| PLA Matte | ¥99 | ~$14 | $28 | +100% |
| PETG Basic | ¥99 | ~$14 | $28 | +100% |
| ABS | ¥99 | ~$14 | $28 | +100% |

---

## 💡 Key Findings

- **Filament has the biggest markup** — up to 2× the Chinese price
- **X1C has the highest machine markup** (+74%), significantly impacted by import duties and tariffs
- **Entry-level printers** (A1 mini, Ender-3) have smaller but still meaningful markups (+28–45%)
- US tariffs on Chinese goods add a further layer on top of existing price gaps

---

## 🤖 Why We Need AI Support

This project is built on a simple belief: **information asymmetry is the enemy of creativity.**

Right now, Chinese maker communities are sharing breakthroughs, tips, and affordable tools that most Americans never hear about — because of language barriers and lack of aggregated, accessible data.

AI can bridge this gap at scale. We're actively seeking AI compute support (such as OpenAI's Codex for Open Source program) to help us:
- Build automated pipelines that translate and surface Chinese maker knowledge
- Run smart price-monitoring agents across Chinese platforms
- Power a community tool that helps working-class American families make informed 3D printing decisions

**3D printing shouldn't be a luxury.** A single parent replacing a broken spatula handle, a kid printing their first invention, a maker launching a side business from home — these are the people we're building for.

---

## 🔄 How Prices Are Collected

- China prices: JD.com (京东) official brand stores, checked monthly
- USA prices: Amazon.com + official brand US stores, checked monthly
- Exchange rate: updated monthly (current: 1 USD ≈ 7.25 CNY)
- Prices exclude promotions/coupons unless noted

---

## 🤝 Contributing

Found a price error? Want to add a new model or brand?

1. Fork this repo
2. Edit the relevant file in `/data/`
3. Submit a PR with the date and source URL

All contributions welcome — especially from people with direct access to Chinese market pricing.

---

## ⚠️ Disclaimer

Prices change frequently. This is for reference only. Always verify on the official store before purchasing.

---

*Maintained by a maker with deep roots in the Chinese 3D printing market 🇨🇳 → 🇺🇸*
