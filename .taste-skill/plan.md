# Robot Phoenix Team — plan

**Line 1 — kind.** Service : une équipe de lycéens qui construit et fait concourir ses robots RoboCupJunior Soccer. Site-kind `other` (pas de logiciel vendu, pas de lieu visité) ; type `service`.

**Line 2 — deal.**
- Hero : `split` (texte à gauche, la photo de l'équipe à droite), `deal.mjs --type service --has photo`.
- Nav `nav-centre` · footer `footer-dark` · close `close-photo` · rhythm `dark-band` (la section « Sous le capot ») · buttons `tonal`.
- Palette `brand` : bg `#f4efe6`, surface `#e9e1d4`, ink `#1a1a1a`, accent `#cb2d43`, muted `#5c5750`. Ce sont les couleurs du logo (cramoisi, or, orange, noir) : le cramoisi du logo passe le contraste sur le papier chaud, là où l'or et l'orange ne le passent pas. Le bleu `stone-blueprint` a été écarté : il jure avec le logo.
- Type : `schibsted` (Schibsted Grotesk), le pairing dealé pour service ; radius `soft`.
- Moments : `word-highlight` sur `#saison` (déclaration de l'équipe, une section, pas de photo). Un seul moment : la page a huit sections, pas dix.

**Voice card.** `Voice: facts only (copy-registers.md 1), un mouvement technique (2) · Pairs: exact, pas froid ; fier par le palmarès, jamais par l'adjectif · Person: « nous » pour le travail, « l'équipe » comme sujet, « vous » nulle part (pas de formulaire) · Sentences: 7 à 16 mots, un chiffre avec son unité · Humour: aucun · House words: pôles, robot, terrain, saison, finale · Never: passion, innovation, esprit, sommet, un jeu de mots sur Phoenix.`

## Sections

| # | id | idée | visuel | écrans |
|---|---|---|---|---|
| 1 | `#top` hero | l'équipe, sa catégorie, son résultat 2026 | photo A (l'équipe brandit deux robots après la finale) | 1 |
| 2 | `#poles` | quatre pôles travaillent le même robot | photo B (mise au point du robot sur la table) | 1 |
| 3 | `#palmares` | cinq résultats, trois saisons, l'objectif 2027 | liste de résultats + photo C (le quai avant la finale) | 1 |
| 4 | `#robot` | six pièces sous le capot | photo E (le robot sur le terrain, vu de près), sur le `dark-band` | 1 |
| 5 | `#equipe` | six élèves et un mentor | sept portraits 4:5 (nom et rôle dessous), puis une bande 16:3 de l'équipe sur la terrasse (desktop) | 1 |
| 6 | `#galerie` | la saison en images | quatre photos 4:5 en une rangée, sans légende, sur `ground-surface` | 1 |
| 7 | `#saison` | ce que la compétition apprend à l'équipe | type (`word-highlight`) | 1 |
| 8 | `#contact` | écrire à l'équipe | `close-photo` : photo D (l'équipe derrière la table) | 1 |

Chaque photo de compétition n'apparaît qu'une fois ; les portraits sont propres à `#equipe`. Pas de formulaire : les actions ouvrent `mailto:contact@robot-phoenix.team`. Deux sections sans photo ne se touchent pas : la déclaration (type) précède le pied de page photo. Aucune légende sous une image (règle de la maison) : la galerie nomme ses images par l'alt et la phrase d'introduction.

## Faits (brief + dépôt de l'équipe)

- RoboCupJunior, ligue Soccer ; robots 100 % conçus, imprimés et programmés en interne.
- Six jeunes et un mentor, du lycée Notre-Dame de Boulogne, en Île-de-France.
- Vice-champions de France 2026 ; vice-champions Île-de-France 2024 et 2026 ; 4e Open national 2024 (Prix de l'Enthousiasme) ; 4e Open Île-de-France 2025. Trois podiums depuis 2024.
- Objectif 2027 : titre national et qualification internationale.
- Quatre pôles : Vision & IA embarquée, mécanique/CAO, électronique/PCB/LiDAR 360°, tactique 2 vs 2/RF.
- Six pièces : caméra fisheye, base holonome (quatre roues omni), LiDAR 360° (RPLidar C1), capteurs de ligne, Raspberry Pi 4, batterie LiPo. La liste de matériel de l'équipe confirme la caméra fisheye, les roues omni, le RPLidar C1, le Raspberry Pi 4 et la carte PCB.
- Sept visages : Augustin, Auriane, Charles, Gaspard, Henri, Justine (élèves) et Stéphane (mentor).
- Galerie : match de juin 2026 (deux robots et la balle), atelier et programmation d'avril 2026, trophée de l'Île-de-France 2024. La bande de `#equipe` vient de la terrasse d'avril 2026.
- Dépôt public : github.com/Robot-Phoenix-Team.

## Assumé / à fournir

- Aucun fait inventé. Les noms et les portraits viennent de l'équipe ; les rôles se limitent à « élève » et « mentor », faute de répartition fournie.
- Portraits : fichiers de 119 à 164 px de large, affichés à 156 px au plus sur desktop (106 px en trois colonnes sur téléphone), donc jamais agrandis au-delà de la source.
- Contact réel : `contact@robot-phoenix.team`. Pas de formulaire, pas de service tiers.
- Domaine canonique `robot-phoenix.team`, hébergé sur GitHub Pages (`CNAME`).
- Aucun sponsor ni partenaire à ce jour : la page n'en mentionne aucun.
- Photos : quatre photos de galerie recadrées en 4:5 au format affiché (variantes 400/700/1200 px, 640/720 px pour les sources paysage) ; les portraits sont convertis en WebP à leur taille native.
- CAO (`robot.3mf`, `.step`, `.x_t`) : un rendu du 3MF a été testé (assemblage de 8,6 M de triangles) mais n'a pas été retenu : le maillage est trop fin pour un rendu propre, et les photos du robot sont plus lisibles.
- Dossier sponsor (`dossier sponsor robot.pdf`) : fichier corrompu (un DOCX encapsulé illisible), non exploité.
