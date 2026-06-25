# Viabilité industrielle des cathodes Sodium-Ion

*Analyse croisée : coûts des précurseurs, complexité de synthèse, scalabilité. Juin 2026.*

---

## Prix des précurseurs (spot, juin 2026)

| Précurseur | Prix | Source |
|---|---|---|
| Na₂CO₃ (soda ash) | 159 $/tonne | TradingEconomics |
| Li₂CO₃ (lithium) | 21 600 $/tonne | TradingEconomics |
| Fe₂O₃ (iron ore 62%) | 101 $/tonne | TradingEconomics |
| MnO₂ (battery grade) | ~2 000 $/tonne | Estimé marché |
| V₂O₅ (vanadium) | ~12 000 $/tonne | Marché ferro-vanadium |
| Co métal | 56 290 $/tonne | TradingEconomics |
| Hard carbon | ~6 000 $/tonne | Estimation pilote→masse |
| Graphite (battery) | ~4 000 $/tonne | Marché spot |

**Ratio clé :** Na₂CO₃ est 136× moins cher que Li₂CO₃. Fe₂O₃ est ~300× moins cher que le cobalt. Le vanadium, même sans cobalt, coûte 75× le soda ash.

---

## Classement par viabilité économique

### 1. Bleu de Prusse (PBA) — Score 95/100

**Acteur de référence :** CATL (Naxtra, production de masse depuis décembre 2025).

**Coût cathode :** 1-3 $/kg. Les précurseurs (fer, manganèse, sodium, carbone) sont tous abondants et bon marché.

**Synthèse :** Co-précipitation aqueuse à 80°C. Pas d'atmosphère contrôlée. Une seule étape. Consommation énergétique négligeable.

**Scalabilité :** Production de masse. CATL a certifié ses cellules Naxtra selon GB 38031-2025. L'architecture PBA est intégrée dans les chaînes de production existantes.

**Risque résiduel :** Dissolution du manganèse sur les longs cycles. Compensé par les formulations high-entropy (18 000 cycles démontrés).

---

### 2. Oxyde lamellaire Fe/Mn — Score 88/100

**Acteurs de référence :** HiNa Battery (CAS, Chine), Faradion (Reliance Industries, UK/Inde).

**Coût cathode :** 2-5 $/kg. Fer et manganèse abondants. Pas de nickel, pas de cobalt.

**Synthèse :** Calcination à 850°C sous air. Une étape. Pas de gaz inerte requis pour les phases P2. Consommation énergétique modérée.

**Scalabilité :** Production de masse (>1 GWh). Faradion a licencié sa technologie à Reliance. HiNa a déployé des batteries dans des véhicules électriques et du stockage stationnaire en Chine.

**Risque résiduel :** Instabilité à l'air des oxydes lamellaires sodés. Nécessite une manipulation sous atmosphère sèche pendant la fabrication des électrodes.

---

### 3. Oxyde lamellaire Ni/Fe/Mn — Score 68/100

**Coût cathode :** 10-15 $/kg. Le nickel, même à des teneurs réduites (10-30%), pèse sur le coût.

**Synthèse :** Calcination à 850-950°C. Atmosphère contrôlée (O₂ ou air sec) pour stabiliser le nickel.

**Scalabilité :** Lignes pilotes intégrées. Les formulations O3-NaNi₁/₃Fe₁/₃Mn₁/₃O₂ sont produites à l'échelle pilote. Compatible avec les équipements de production NMC Li-ion existants.

**Risque résiduel :** Volatilité du prix du nickel. La capacité plus élevée (150-180 mAh/g) ne justifie pas le surcoût pour le stockage stationnaire. Reste pertinent pour la mobilité.

---

### 4. NASICON Vanadium (NVPF) — Score 38/100

**Acteur de référence :** Tiamat Energy (Amiens, France). Gigafactory de 5 GWh planifiée.

**Coût cathode :** 15-25 $/kg. Le pentoxyde de vanadium à ~12 000 $/tonne est le facteur limitant. Même à des teneurs réduites, le vanadium domine le coût matière.

**Synthèse :** Multi-étapes sous Ar/N₂. Calcination à 700-800°C. Contrôle strict de l'atmosphère. Consommation énergétique élevée.

**Scalabilité :** Pilote uniquement. Tiamat produit des cellules 18650 en petite série. Le passage à 5 GWh implique une multiplication par 1 000 de la capacité de production. Aucune référence de production de masse pour le NASICON-vanadium.

**Avantage réel :** Charge rapide (6 minutes), durée de vie exceptionnelle, sécurité intrinsèque (structure polyanionique stable). Ces qualités sont réelles mais s'adressent à un marché de niche (flottes captive, véhicules utilitaires légers) — pas au stockage stationnaire de masse.

---

## Conclusion

Le marché est en train de converger vers deux architectures gagnantes : PBA pour le coût, oxydes lamellaires Fe/Mn pour la densité. Le NASICON-vanadium, malgré ses qualités techniques, se heurte à une réalité physique que le marché n'a pas encore intégrée dans ses valorisations : le vanadium est 75 fois plus cher que le sodium, et aucun gain d'échelle ne changera ce rapport.
