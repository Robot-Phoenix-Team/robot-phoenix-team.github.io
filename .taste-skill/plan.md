# Robot Phoenix Team — plan

**Line 1 — kind.** Service : une équipe de lycéens qui conçoit, fabrique et fait concourir ses robots RoboCupJunior Soccer. Site-kind `other` (pas de logiciel vendu, pas de lieu visité) ; type `service`.

**Line 2 — deal.**
- Hero : `split` (texte à gauche, la photo de l'équipe célébrant avec les deux robots à droite), `deal.mjs --type service --has photo`.
- Nav `nav-centre` · footer `footer-dark` · close `close-photo` · rhythm `dark-band` (la section « Sous le capot » avec rendu 3D) · buttons `tonal`.
- Palette `brand` : bg `#ffffff`, surface `#f4f4f5`, ink `#18181b`, accent `#cb2d43`, muted `#52525b`. Alignée sur les couleurs exactes du logo (blanc pur, noir profond, gris mécanique de la couronne dentée, dégradé de flamme or `#f9b745`, orange `#e27244`, cramoisi `#cb2d43`). Logo transparent sur fond clair (`logo-phoenix.svg`) et fond sombre (`logo-phoenix-inv.svg`).
- Rendu 3D : Modèle CAO officiel de l'équipe issu de `photo/robot.3mf` (châssis imprimé sarcelle `#005B54`, 4 roues omnidirectionnelles avec joints toriques, roulements, LiDAR RPLidar C1 et Raspberry Pi 4), rendu en studio sous éclairage 3 points et intégré dans `#robot`.
- Type : `schibsted` (Schibsted Grotesk), le pairing dealé pour service ; radius `soft`.
- Moments : `word-highlight` sur `#saison` (déclaration de l'équipe, une section, pas de photo).

**Voice card.** `Voice: facts only (copy-registers.md 1), un mouvement technique (2) · Pairs: exact, pas froid ; fier par le palmarès, jamais par l'adjectif · Person: « nous » pour le travail, « l'équipe » comme sujet, « vous » nulle part (pas de formulaire) · Sentences: 7 à 16 mots, un chiffre avec son unité · Humour: aucun · House words: pôles, robot, terrain, saison, finale · Never: passion, innovation, esprit, sommet, un jeu de mots sur Phoenix.`

## Sections

| # | id | idée | visuel | écrans |
|---|---|---|---|---|
| 1 | `#top` hero | l'équipe, sa catégorie, son résultat 2026 | photo A (célébration complète, robots brandis bien visibles) | 1 |
| 2 | `#poles` | 4 pôles d'ingénierie travaillent le robot | photo B (mise au point du robot sur le terrain vert) | 1 |
| 3 | `#palmares` | cinq résultats, trois saisons, l'objectif 2027 | liste de résultats + photo C (l'équipe sur le quai avec sacs, cadrage complet) | 1 |
| 4 | `#robot` | six pièces sous le capot | rendu 3D CAO officiel de l'équipe (`robot-cad-1200.webp`), sur le `dark-band` | 1 |
| 5 | `#equipe` | six élèves et un mentor | sept portraits complets en `contain` (sans rognage de visages) + bandeau terrasse desktop et mobile | 1 |
| 6 | `#galerie` | la saison en images | quatre photos en ratio 4:3 naturel (match deux robots, programmation, atelier, trophée) | 1 |
| 7 | `#saison` | ce que la compétition apprend à l'équipe | type (`word-highlight`) | 1 |
| 8 | `#contact` | écrire à l'équipe | `close-photo` : l'équipe derrière la table de match avec ses deux robots | 1 |

Toutes les photos sont affichées dans leur intégralité sans coupures inopportunes. Pas de formulaire : l'action unique est `mailto:contact@robot-phoenix.team` libellée « Contacter l'équipe » dans toute la page.
