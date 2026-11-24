# Robot Phoenix Team — plan

**Line 1 — kind.** Service: une équipe de collégiens qui construit et fait concourir ses robots RoboCupJunior Soccer. Site-kind `other` (pas de logiciel vendu, pas de lieu visité) ; type `service`.

**Line 2 — deal.**
- Hero : `split` (texte à gauche, la photo de l'équipe à droite), `deal.mjs --type service --has photo`.
- Nav `nav-centre` · footer `footer-dark` · close `close-photo` · rhythm `dark-band` (la section « Sous le capot ») · buttons `tonal`.
- Palette `brand` : bg `#f4efe6`, surface `#e9e1d4`, ink `#1a1a1a`, accent `#cb2d43`, muted `#5c5750`. Ce sont les couleurs du logo (cramoisi, or, orange, noir) : le cramoisi du logo passe le contraste sur le papier chaud, là où l'or et l'orange ne le passent pas. Le bleu `stone-blueprint` a été écarté : il jure avec le logo.
- Type : `schibsted` (Schibsted Grotesk), le pairing dealé pour service ; radius `soft`.
- Moments : `word-highlight` sur `#saison` (déclaration de l'équipe, une section, pas de photo). Un seul moment : la page a six sections, pas huit.

**Voice card.** `Voice: facts only (copy-registers.md 1), un mouvement technique (2) · Pairs: exact, pas froid ; fier par le palmarès, jamais par l'adjectif · Person: « nous » pour le travail, « l'équipe » comme sujet, « vous » seulement dans le formulaire · Sentences: 7 à 16 mots, un chiffre avec son unité · Humour: aucun · House words: pôles, robot, terrain, saison, finale · Never: passion, innovation, esprit, sommet, un jeu de mots sur Phoenix.`

## Sections

| # | id | idée | visuel | écrans |
|---|---|---|---|---|
| 1 | `#top` hero | l'équipe, sa catégorie, son résultat 2026 | photo A (l'équipe brandit deux robots après la finale) | 1 |
| 2 | `#poles` | quatre pôles travaillent le même robot | photo B (mise au point du robot sur la table) | 1 |
| 3 | `#palmares` | cinq résultats, trois saisons, l'objectif 2027 | liste de résultats, sans photo (tableau) | 1 |
| 4 | `#robot` | cinq pièces sous le capot | diagramme `hub` tenu immobile, sur le `dark-band` | 1 |
| 5 | `#saison` | ce que la compétition apprend à l'équipe | type (`word-highlight`) | 1 |
| 6 | `#ecrire` | écrire à l'équipe | formulaire + photo C (le quai avant la finale) | 1 |
| 7 | `#contact` | contacter l'équipe | `close-photo` : photo D (l'équipe derrière la table) | 1 |

Chaque photo n'apparaît qu'une fois. Deux sections sans photo ne se touchent pas : le palmarès (tableau) est suivi du robot (diagramme), la déclaration (type) précède le formulaire (photo).

## Faits (brief + dépôt de l'équipe)

- RoboCupJunior, ligue Soccer ; robots 100 % conçus, imprimés et programmés en interne.
- Vice-champions de France 2026 ; vice-champions Île-de-France 2024 et 2026 ; 4e Open national 2024 (Prix de l'Enthousiasme) ; 4e Open Île-de-France 2025.
- Objectif 2027 : titre national et qualification internationale.
- Quatre pôles : Vision & IA embarquée, mécanique/CAO, électronique/PCB/LiDAR 360°, tactique 2 vs 2/RF.
- Cinq pièces : caméra grand angle, base holonome, LiDAR 360°, capteurs de ligne, batterie LiPo.
- Dépôt public : github.com/Robot-Phoenix-Team.

## Assumé / à fournir

- Aucun fait inventé. Pas de nom de personne ni de portrait (le brief n'en donne pas pour la page).
- Le formulaire utilise un `mailto:` sur `.example` ; l'adresse réelle est `contact@robot-phoenix.team`, à rebrancher.
- Domaine canonique `robot-phoenix.team` : la ligne reste en commentaire.
- Photos : les quatre photos de compétition du client, optimisées en WebP. Le client peut fournir des vues de près du robot (caméra, LiDAR, PCB) pour remplacer le diagramme.
