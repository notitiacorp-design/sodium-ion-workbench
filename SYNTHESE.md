# Synthèse Comparative: Cathodes Sodium-Ion
## Prussian White (Blanc de Prusse) vs Oxydes Lamellaires Fe-Mn

**Date:** 2026-06-25  
**Sources:** PubMed (40 abstracts), arXiv (3 papers), OpenAlex (11 reviews)  
**Note:** Semantic Scholar API bloquée (HTTP 429 rate limit). Compteurs de citations non disponibles.

---

## 1. RÉSUMÉ DES MÉTRIQUES CLÉS

| Métrique | Prussian White / PBA | Oxydes Lamellaires Fe-Mn |
|---|---|---|
| **Capacité théorique** | ~170 mAh/g (Na₂MnFe(CN)₆) | ~240-260 mAh/g (O3), ~170-200 (P2) |
| **Capacité mesurée** | 120–163 mAh/g | 133–180.7 mAh/g |
| **Densité énergétique cellule** | ~100-150 Wh/kg (estimé) | **>180 Wh/kg démontré** (PMID 42157640) |
| **Cycles avant dégradation** | 200–**18,000** (high-entropy PBA) | 100–3,700 (P2 + compensation Na) |
| **Rétention capacité typique** | 70–88% (500-1000 cycles) | 68–91% (100-500 cycles) |
| **Voltage opérationnel** | 3.0–3.8 V vs Na/Na⁺ | 2.0–4.3 V vs Na/Na⁺ |
| **Meilleur régime (C-rate)** | **30C** (18k cycles) | 5-10C (haute capacité réduite) |

---

## 2. MATÉRIAUX PRÉCURSEURS

### Prussian White
| Précurseur | Rôle |
|---|---|
| Na₄Fe(CN)₆ (ferrocyanure de sodium) | Charpente [Fe(CN)₆], source Fe |
| MnSO₄ / MnCl₂ / Mn(NO₃)₂ | Centre métallique Mn (site azoté) |
| Citrate de sodium (Na₃C₆H₅O₇) | Agent chélateur, contrôle cristallinité |
| PVP (polyvinylpyrrolidone) | Surfactant, contrôle morphologique |
| Dopants: Cu, Ni, Cr, Zn, Co, Cs, B | Stabilité structurale, conductivité |

**Synthèse:** Co-précipitation aqueuse à T ambiante (<100°C). Procédé basse énergie.

### Oxydes Lamellaires Fe-Mn
| Précurseur | Rôle |
|---|---|
| Na₂CO₃ | Source Na, fondant calcination |
| MnO₂ / Mn₂O₃ / MnCO₃ | Source Mn |
| Fe₂O₃ / Fe₃O₄ | Source Fe, stabilisation structurale |
| NiO / Ni(OH)₂ | Source Ni (activité redox) |
| TiO₂ / Al₂O₃ / Al(OH)₃ | Dopants: suppression transitions de phase |
| Li₂CO₃ / MgO | Dopants: activation redox anionique |

**Synthèse:** Calcination haute température (800-950°C). Consommation énergétique élevée.

---

## 3. VERROUS TECHNIQUES

### Prussian White (6 verrous majeurs)

| Verrou | Sévérité | Description | Mitigation |
|---|---|---|---|
| **Lacunes [Fe(CN)₆]** | 🔴 Critique | Défauts structuraux → eau, faible capacité | Synthèse N₂, citrate, recuit |
| **Eau cristalline** | 🔴 Critique | Réactions parasites électrolyte, gonflement | Lyophilisation, dopage Cs⁺ |
| **Distorsion Jahn-Teller** | 🟠 Élevée | Mn³⁺ → transition cubique→tétragonal | Dopage Cu-gradient, NH₄⁺, high-entropy |
| **Dissolution Mn** | 🟠 Élevée | Perte matière active, catalyse décomposition | Coating Co₉S₈, core-shell CuHCF |
| **Faible conductivité** | 🟡 Modérée | ~10⁻⁹ S/cm, nécessite beaucoup de carbone | Composite carbone, dopage Ni/Co |
| **Instabilité haute V** | 🟡 Modérée | Décomposition >4.2V | Électrolytes fluorés, high-entropy |

### Oxydes Lamellaires (7 verrous majeurs)

| Verrou | Sévérité | Description | Mitigation |
|---|---|---|---|
| **Transitions de phase** | 🔴 Critique | P2→O2, O3→P3, ΔV jusqu'à 20% | Dopage Al/Ti/Li/Mg, high-entropy |
| **Perte d'oxygène (O₂)** | 🟠 Élevée | Redox O²⁻→O₂ⁿ⁻→O₂↑, sécurité | Dual-site co-doping, coating Nb-Ti |
| **Distorsion Jahn-Teller** | 🟠 Élevée | Mn³⁺ → fissuration particules | Al/Ti co-dopage, dilution Mn |
| **Instabilité à l'air** | 🟠 Élevée | Échange Na⁺/H⁺, NaOH/Na₂CO₃ surface | Traitement acide, high-entropy |
| **Dissolution TM** | 🟡 Modérée | Mn, Fe dans électrolyte | Coating, électrolytes sans fluor |
| **Voltage decay** | 🟠 Élevée | Migration TM → baisse voltage moyen | Superstructure LiTiMn₅, dopage Mg |
| **Cinétique Na⁺ lente** | 🟡 Modérée | Canaux 2D étroits (O3) | High-entropy, dopage Li |

---

## 4. INNOVATIONS MAJEURES 2026

### Prussian White
1. **High-entropy PBA (Cr-Mn-Fe-Ni-Zn):** 18,000 cycles à 30C, structure quasi-zéro-déformation (PMID 41870985)
2. **Cu-gradient@MnPBA:** Dopage graduel Cu en surface, 500 cycles, rétention 78% (PMID 42159928)
3. **Ancrage NH₄⁺ par liaisons H:** Stabilise Mn-PBA contre transition cubique→tétragonal (PMID 42153505)
4. **Ingénierie Cs⁺:** Stabilise liaisons Fe-N, 1000 cycles, rétention 81.5% (PMID 42103733)
5. **Marquage D₂O:** Révèle mécanisme couplé eau-défauts dans dégradation (PMID 42160118)
6. **MnHCF monoclinique (synthèse N₂):** 200 cycles à 5C, 75% rétention (PMID 41587389)

### Oxydes Lamellaires
1. **Compensation NaBPh₄:** >180 Wh/kg cellule, 3700 cycles (PMID 42157640)
2. **Al/Ti co-dopé Fe-Mn O3:** 200 cycles, rétention 85.5% (PMID 42171082)
3. **High-entropy O3 (Ni-Mn-Fe-Ti-Cu-Mg + F):** 500 cycles, 85% rétention, air-stable (PMID 42240021)
4. **Dual-site co-doping O3:** 500 cycles, rétention 72.7%, supprime perte O₂ (PMID 42326355)
5. **Superstructure LiTiMn₅ P2:** Supprime voltage decay (PMID 42329130)
6. **Mg/Li co-dopage P2:** Active redox anionique, 400 cycles (PMID 42195646)
7. **Li/Ti dual-doping O3:** 180.7 mAh/g, haute tension (PMID 42149052)
8. **Traitement acide O3:** Résout instabilité air ambiant (PMID 42159581)

---

## 5. COMPARAISON CROISÉE

| Critère | Vainqueur | Écart |
|---|---|---|
| **Densité énergétique** | 🏆 Oxydes lamellaires | >180 Wh/kg vs ~100-150 Wh/kg |
| **Durée de vie** | 🏆 Prussian White | 18,000 vs 3,700 cycles (meilleur cas) |
| **Puissance (C-rate)** | 🏆 Prussian White | 30C vs 5-10C |
| **Coût / Durabilité** | 🏆 Prussian White | Synthèse <100°C, sans Ni/Co |
| **Scalabilité industrielle** | ⚖️ Égalité | PW: procédé simple mais contrôle qualité; LO: mature mais énergivore |

---

## 6. FORMULATIONS LES PLUS PROMETTEUSES

### Pour le stockage stationnaire (longue durée, puissance)
→ **High-entropy PBA** (Cr-Mn-Fe-Ni-Zn): 18,000 cycles, 30C, bas coût

### Pour la densité énergétique (mobilité légère)
→ **O3 high-entropy** (Ni-Mn-Fe-Ti-Cu-Mg + F) avec compensation Na: >180 Wh/kg, air-stable

### Pour compromis performance/coût
→ **P2-Na₀.₆₇Fe₀.₄Mn₀.₄Al₀.₁Ti₀.₁O₂**: 200 cycles, 85.5% rétention, sans Ni

---

## 7. RECOMMANDATION

Les deux architectures sont viables pour remplacer le lithium:
- **Oxydes lamellaires Fe-Mn** pour applications nécessitant une densité énergétique élevée (>150 Wh/kg)
- **Prussian White** pour applications nécessitant longue durée de vie, puissance élevée, et coût minimal

La tendance 2026 est clairement vers les approches **high-entropy** dans les deux familles, qui résolvent simultanément plusieurs verrous techniques (transitions de phase, stabilité structurale, dissolution).

---

*Fichier JSON complet: `/home/openclaw/sodium_ion_data/synthesis_final.json`*
*Données brutes: `/home/openclaw/sodium_ion_data/`*
