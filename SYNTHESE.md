# Synthèse : Cathodes Sodium-Ion — Prussian White vs Oxydes Lamellaires

*Mining de 500+ publications (2020-2026). Extraction automatisée des métriques quantitatives.*

---

## Métriques clés

| | Prussian White (PBA) | Oxydes Lamellaires Fe-Mn |
|---|---|---|
| Capacité théorique | ~170 mAh/g | ~240 mAh/g (O3), ~200 mAh/g (P2) |
| Capacité mesurée | 120-163 mAh/g | 133-181 mAh/g |
| Densité énergétique | ~100-150 Wh/kg | >180 Wh/kg |
| Cycles (max démontré) | 18 000 (high-entropy PBA) | 3 700 (P2 + compensation Na) |
| Rétention à 500 cycles | 70-88% | 68-91% |
| Voltage opérationnel | 3.0-3.8 V | 2.0-4.3 V |
| Meilleur C-rate | 30C | 5-10C |

---

## Précurseurs et synthèse

**Prussian White (PBA).** Na₄Fe(CN)₆ comme charpente, MnSO₄ ou MnCl₂ comme centre métallique, citrate de sodium comme agent chélateur. Synthèse par co-précipitation aqueuse à température ambiante. Procédé basse énergie. Dopants courants : Cu, Ni, Zn pour la stabilité structurale.

**Oxydes lamellaires.** Na₂CO₃ + MnO₂/Mn₂O₃ + Fe₂O₃/Fe₃O₄. Synthèse par calcination à 800-950°C sous air (P2) ou atmosphère contrôlée (O3). Consommation énergétique élevée. Dopants : Ti, Al, Mg, Li pour supprimer les transitions de phase.

---

## Verrous techniques

### Prussian White

**Lacunes [Fe(CN)₆].** Défaut structural majeur. Les sites vacants piègent l'eau et réduisent la capacité. Mitigation : synthèse sous N₂, ajout de citrate, recuit contrôlé.

**Eau cristalline.** L'eau résiduelle dans la structure déclenche des réactions parasites avec l'électrolyte. Mitigation : lyophilisation, dopage au césium.

**Distorsion Jahn-Teller.** Le Mn³⁺ provoque une transition cubique → tétragonal qui dégrade la structure. Mitigation : dopage Cu en gradient, high-entropy PBA, NH₄⁺.

**Dissolution du manganèse.** Perte de matière active dans l'électrolyte, catalyse la décomposition. Mitigation : coating Co₉S₈, structure core-shell CuHCF.

### Oxydes lamellaires

**Transitions de phase.** P2→O2 ou O3→P3 lors de la désodiation, avec changement de volume. Mitigation : dopage Al, Mg, Ti.

**Instabilité à l'air.** Les oxydes lamellaires sodés réagissent avec l'humidité atmosphérique, formant des carbonates de surface. Problème majeur pour le stockage et la fabrication.

**Dégagement d'oxygène.** À haut voltage (>4.2 V), l'oxygène du réseau participe à la capacité mais se dégage irréversiblement. Mitigation : dopage Li, Mg pour activer le redox anionique de façon réversible.

**Voltage decay.** Dégradation progressive de la tension de fonctionnement sur les cycles, réduisant la densité énergétique effective.

---

## Verdict

Le Prussian White domine sur le coût et la cyclabilité. Les oxydes lamellaires dominent sur la densité énergétique. Le high-entropy PBA (18 000 cycles à 30C) est l'architecture la plus prometteuse pour le stockage stationnaire. Les oxydes lamellaires restent pertinents pour la mobilité où la densité énergétique est critique.
