# Sodium-Ion Workbench

**Open-source reverse-engineering of critical battery materials. AI-assisted literature mining for cathode architectures.**

---

## Why This Exists

The sodium-ion battery race is accelerating. Three cathode architectures compete for dominance. But the public narrative — driven by fundraising announcements and gigafactory press releases — ignores the physics of the periodic table.

This workbench applies **first-principles material economics** to the sodium-ion cathode landscape. We mine 500+ academic publications (2020–2026), cross-reference precursor costs, synthesis complexity, and degradation mechanisms, and rank architectures by **industrial viability**, not press coverage.

---

## Architecture Ranking

| Rank | Architecture | Score | Cathode Cost | Production Status | Key Risk |
|:----:|-------------|:-----:|:------------:|:-----------------:|----------|
| 🥇 | **PBA / Prussian White** | **95/100** | 1–3 $/kg | Mass production (CATL Naxtra, Dec 2025) | Mn dissolution, Jahn-Teller distortion |
| 🥈 | **Layered Oxide Fe/Mn** | **88/100** | 2–5 $/kg | Mass production (HiNa, Faradion >1 GWh) | Air instability, phase transitions |
| 🥉 | **Layered Oxide Ni/Fe/Mn** | **68/100** | 10–15 $/kg | Integrated pilot lines | Nickel cost volatility |
| 4 | **NASICON Vanadium (NVPF)** | **38/100** | 15–25 $/kg | Pilot only (Tiamat Energy, Amiens FR) | **V₂O₅ at ~12,000 $/T** |

---

## The Asymmetry

**Tiamat Energy** (Amiens, France) is building a 5 GWh gigafactory for NASICON-vanadium batteries. The technology is excellent — fast charge, long cycle life, stable polyanionic structure.

But vanadium pentoxide costs **~12,000 USD per ton**.

CATL's Prussian White cathode uses soda ash (Na₂CO₃) at **159 USD per ton**.

That's a **75× cost multiplier** on the cathode precursor alone. Before synthesis. Before assembly. Before the gigafactory concrete is even poured.

| Precursor | Price (June 2026) | Used In |
|-----------|------------------:|---------|
| Na₂CO₃ (soda ash) | 159 $/T | PBA, Layered Oxides |
| Li₂CO₃ | 21,600 $/T (136×) | Li-ion (reference) |
| Fe₂O₃ (iron ore 62%) | 101 $/T | PBA, Layered Oxides |
| MnO₂ (battery grade) | ~500 $/T | PBA, Layered Oxides |
| V₂O₅ (vanadium) | ~12,000 $/T | NASICON (Tiamat) |
| Co metal | 56,290 $/T | NMC Li-ion (reference) |

The market is funding a chemistry that the periodic table has already priced out.

---

## Repository Contents

| File | Description |
|------|-------------|
| `synthesis_sample.json` | 15 structured cathode entries with PMIDs, capacity, cycles, degradation mechanisms |
| `SYNTHESE.md` | Full literature synthesis — Prussian White vs Layered Oxides comparison |
| `analyse_economique.md` | Industrial bottleneck analysis: precursor costs, synthesis complexity, scalability |

### Full Dataset

The complete dataset contains **1,088 structured entries** across all cathode architectures, with PubMed IDs, DOIs, extracted metrics (specific capacity, energy density, cycle life, capacity retention), and classified failure mechanisms.

→ [Purchase Full Dataset — 490€](https://buy.stripe.com/5kQ00cbn15kgbyubVm2sM07)

---

## Methodology

1. **Literature mining**: Semantic Scholar, PubMed, and arXiv APIs queried for sodium-ion cathode papers (2020–2026)
2. **Metric extraction**: Regex + NLP pipeline extracting specific capacity (mAh/g), energy density (Wh/kg), cycle counts, and capacity retention from abstracts
3. **Cost cross-referencing**: USGS Mineral Commodity Summaries 2026, Trading Economics spot prices, and public disclosures from CATL, Faradion, HiNa Battery, and Tiamat Energy
4. **Viability scoring**: Weighted model combining precursor cost (40%), synthesis complexity (25%), demonstrated scalability (20%), and cycle life (15%)

---

## Tone

This is a **physics-first publication**. No geopolitics. No fundraising narratives. No commercial endorsements. The goal is to provide the data that lets engineers and investors make decisions based on material reality, not press releases.

---

## License

Data: CC BY-NC-SA 4.0  
Code: MIT

*The physics of the periodic table does not negotiate.*
