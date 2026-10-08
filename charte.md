# Charte — Budget 2027 (direction « Encre + ambre »)

Choisie par Sébastien le 2026-10-08, après proposition de 5 directions.
Direction retenue : **n° 4 — Encre + ambre**.

## 1. Registre

**Sombre profond.** Fond bleu nuit dégradé, halo froid en haut à droite. Grave, haut de gamme,
lisible en projection comme en écran.

## 2. Palette (par rôle)

| Rôle | Valeur | Emploi |
|---|---|---|
| fond | `#0D1B2E` → `#081326` | dégradé principal |
| halo | `#1C4067` | tache radiale, haut droite (58 % d'atténuation) |
| accent | `#F2B450` | valeur chiffrée, kicker, filet, barres |
| accent foncé | `#C98B2C` | départ du dégradé de barre |
| clair | `#EEF3F9` | titres, corps fort |
| secondaire | `#A8BDD4` | texte courant, libellés |
| pied | `#617991` | pied de page, numérotation |
| bordure | `rgba(255,255,255,.12)` | contours de carte |
| filet de pied | `rgba(255,255,255,.16)` | séparateur bas |
| risque | `#E5484D` | bord supérieur du panneau « risque » |
| parade | `#3DD68C` | bord supérieur du panneau « parade » |

Contraste mesuré : `#F2B450` sur `#0D1B2E` = **9,41:1** ; `#A8BDD4` sur fond = **8,98:1**.
Ambre retenu le 2026-10-08 : **doré `#F2B450`** (préféré au cuivré `#E9A13B`, 7,93:1).

## 3. Polices

- **Source Sans 3** (300/400/600/700) — titres, corps, valeurs. Chiffres en `tabular-nums`.
- Rapatriée en local (`fonts/`) : aucun appel réseau au rendu.

## 4. Échelle typographique

| Niveau | Taille / graisse | Emploi |
|---|---|---|
| display | 150 / 700, interligne 1.14 | ouverture |
| titre | 84 / 700, interligne 1.12 | titre de slide |
| sous-titre | 38 / 400 | accroche |
| corps | 30 / 400 | texte (plancher imposé) |
| légende | 22 / 400 | pied, note |

## 5. Motif porteur

**Grande diagonale** claire en haut à droite (`clip-path`, rotation 6°, ambre doré à 20 %
d'opacité). C'est l'élément qui donne son caractère au jeu — la revue du 08/10 a montré que c'est
ce type de parti pris, et non une illustration, qui fait paraître une slide professionnelle.

**Placement (décidé le 2026-10-08)** : présente et forte **sur la couverture et la slide de
clôture** (« la demande »), **absente sur les slides de contenu** — celles-ci portent déjà leur
propre structure (cartes, barres, panneaux) et une diagonale partout entrerait en concurrence
avec elles.

**Filet ambre** court (260 × 6 px) sous le titre de la couverture.

## 6. Gabarits

1. **Couverture** — display + deux cartes de chiffres.
2. **Cartes** — 3 cartes translucides, valeur en ambre en tête.
3. **Barres** — 5 lignes : libellé / jauge / pourcentage.
4. **Comparaison** — deux barres + une barre d'écart.
5. **Avant / après** — deux panneaux, bord ambre / bord froid.
6. **Flux** — étapes numérotées reliées.
7. **Demande** — deux plans : demande à gauche, conséquence à droite.

## 7. Signalétique de couleur

- **ambre** = valeur chiffrée et accent (jamais pour du texte courant) ;
- **clair** = titres ; **secondaire** = texte courant ;
- rouge/vert réservés aux registres « risque / parade » (aucun usage décoratif).

## Interdits

- Pas d'illustration dessinée à la main (règle mesurée : rejetée).
- Pas d'icône hors bibliothèque (Lucide si besoin).
- Pas de couleur porteuse d'information seule (daltonisme).
- Chiffres illustratifs : la mention « maquette » reste tant que les vrais montants ne sont pas fournis.
