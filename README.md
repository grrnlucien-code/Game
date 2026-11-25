# Jeux

Deux jeux pour navigateur, chacun dans un seul fichier HTML. Pour jouer, ouvre le fichier dans Chrome, Edge, Firefox ou Safari. Il n'y a rien à installer.

| Fichier | Jeu |
|---|---|
| `index.html` | **Attrape les étoiles** : un petit jeu simple où tu rattrapes les étoiles et évites les bombes. |
| `neon.html` | **Gardien du Néon** : un jeu de survie en vagues, avec boss, boutique, skins, succès et multijoueur. |

## Gardien du Néon

Tu pilotes un vaisseau qui tire tout seul sur l'ennemi le plus proche. Des vagues d'ennemis arrivent, de plus en plus fortes, avec un boss toutes les 5 vagues. Les cristaux te font monter de niveau : à chaque niveau, tu choisis une amélioration parmi 3 cartes.

### Contenu

- **8 types d'ennemis** : chasseur, rapide, tireur, tank, diviseur, kamikaze, spectre et sentinelle, plus des versions élites dorées.
- **3 boss** qui tournent : le Noyau prismatique, le Faucheur (charges annoncées par une ligne rouge) et l'Œil du vide (lasers rotatifs). Chacun devient enragé sous la moitié de ses PV.
- **21 cartes d'amélioration**, de rareté commune, rare ou épique, dont 10 cartes spéciales : orbes, drones, foudre, onde de choc, missiles, ricochet, givre, vampirisme, tirs explosifs et chance.
- **Bonus au sol** : soin, aimant, bombe et bouclier.
- **Boutique** : 7 vaisseaux, 10 couleurs (dont arc-en-ciel et galaxie), 7 traînées, 5 styles de tir et 9 améliorations permanentes, dont le Phénix qui te fait revenir une fois par partie.
- **17 succès** qui rapportent des pièces, et des statistiques.
- **4 difficultés** : plus c'est dur, plus tu gagnes de pièces.
- **Options** : volume de la musique et des effets, qualité des effets, tremblement de l'écran, chiffres de dégâts, visée automatique, mini-carte et FPS.
- Musique et sons générés par le jeu.

La progression (pièces, skins, succès) est enregistrée dans le navigateur. Elle reste tant que tu ne vides pas les données du site.

### Commandes

| Action | Clavier et souris | Manette | Mobile |
|---|---|---|---|
| Bouger | ZQSD, WASD ou flèches | Stick gauche | Glisser le doigt |
| Viser | Automatique, ou maintenir le clic | Stick droit | Automatique |
| Dash (invincible) | Espace ou Maj | A, gâchettes | Bouton DASH |
| Choisir une carte | Clic ou touches 1, 2, 3 | Gauche, droite, puis A | Toucher la carte |
| Pause / son | Échap ou P / M | Start | Bouton II |

### Multijoueur (jusqu'à 4)

**Sur le même écran** : menu Multijoueur, onglet « Sur cet écran ». Le joueur 2 appuie sur Entrée (il joue avec les flèches et dash avec Entrée). Chaque manette rejoint avec A. La caméra suit tout le groupe.

**En ligne** : menu Multijoueur, onglet « En ligne ».

1. Un joueur clique sur « Créer la partie » et reçoit un code de 5 caractères.
2. Les amis ouvrent le même jeu, entrent ce code et cliquent sur « Rejoindre ».
3. L'hôte lance la partie. On peut aussi rejoindre une partie déjà commencée.

En équipe, l'expérience est partagée : à chaque niveau, tout le monde choisit sa carte. Reste près d'un coéquipier à terre pour le relever. Sinon, il revient à la vague suivante.

Pour partager le jeu avec tes amis :

- envoie-leur le fichier `neon.html` ;
- ou mets-le en ligne avec GitHub Pages (dans le dépôt : Settings, puis Pages, puis choisis la branche). L'hôte voit alors un lien `?join=CODE` à envoyer, qui remplit le code tout seul.

Bon à savoir :

- La connexion en ligne passe par le service gratuit PeerJS, puis les navigateurs se parlent directement. Il faut donc Internet. Sur certains réseaux (4G, Wi-Fi d'école ou d'entreprise), la connexion directe peut échouer : essayez un autre réseau.
- Tout le monde doit avoir la même version du fichier.
- L'hôte doit garder l'onglet du jeu ouvert et visible, car c'est son navigateur qui fait tourner la partie.
- Quand le jeu est ouvert sur claude.ai, le mode en ligne utilise les salons de claude.ai à la place de PeerJS, et la liste des parties ouvertes s'affiche.
