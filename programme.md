Graduate school "Imagerie 3D" PACEA
===================================

## 1. Cadre général
Prend place dans le cadre du Graduate Program ARCHEO.

### Modalités

- Formation de 5 à 8 jours pleins, idéalement en 2022 (et pas forcément durant la période estivale, même si ça semble le plus adapté).
- 16 participants maximum, eu égard aux contraintes matérielles et à la capacité d'accueil.
- Les formateurs seront rémunérés par UB. Possibilité pour les EC UB de déclarer les heures faites dans leur service.
- Lieu : à définir (mais sur le campus bordelais).

### Publics cibles
- Publics prioritaires : néo-doctorants PACEA, étudiants du Master BGS durant la transition M1/M2.
- Publics éligibles s'il reste de la place (par ordre de priorité) : permanents de PACEA, anciens étudiants de M2 BGS, doctorants hors PACEA mais appartenant à la même école doctorale.
- Publics probablement pas éligibles sauf gros manque d'inscriptions : doctorants et personnels hors UB/UBM.

### Objectifs
- Rendre autonomes les étudiants et doctorants pour leurs analyses 3D et la pratique de la morphométrie géométrique
- Organiser un transfert de compétences entre membres de PACEA concernant ces thématiques

### Partenaires possibles à l'échelle locale
- CRP2A
- Ausonius (voir avec Alexis Gorgue)
- Archéovision (pour l'archivage des données 3D ou l'acquisition surfacique)

## 2. Organisation de la formation
### Philosophie générale
- Offrir une formation concernant l'ensemble de la chaîne de traitement 3D : acquisition de données brutes (µCT, ...), segmentation, pose de landmarks (ou pas, si landmark-free morphometrics), morphométrie géométrique, traitements statistiques en aval. Toutefois, l'accent doit principalement être mis sur la partie morpho géométrique.
- Idéalement : on aura un jeu de données déjà solide à proposer aux étudiants, mais on y ajoutera "en live" en cours de formation quelques specimen pour lesquels les étudiants feront l'acquisition des données.
- La formation pourrait être modulaire, avec deux inscriptions séparées à réaliser : une première inscription à un tronc commun plutôt élémentaire de 4/5 jours, une seconde pour des compléments plus avancés de 3/4 jours.
- Possibilité de séparer en deux groupes de 8 étudiants, au moins pour la partie acquisition de données.

### (TODO) Données
Quelles données fournir aux étudiants pour servir de support et de cas d'étude ? Il faudrait idéalement que ces données restent librement accessibles aux stagiaires après la formation, et qu'elles soient des scans complets afin de permettre la partie segmentation / pose de landmarks par les stagiaires. Sources possibles : 
- Bases en ligne (e.g., https://www.morphosource.org/)
- Données jointes à des articles de recherche publiés (lesquels ?).

On peut aussi utiliser plusieurs jeux de données différents, un par grand thème (contours 2D, landmarks 3D, etc.).

### Logiciels
Privilégier l'utilisation de R. Démo rapide de MorphoJ également possible.

### Pédagogie et supports de cours
- Au moins pour les parties sur R, possibilité de préparer des tutoriels interactifs, sous forme de Jupyter Notebooks ou de tutoriels `learnr`. Voir un exemple ici : https://learnr-examples.shinyapps.io/ex-data-filter/
- Comment harmoniser / coordonner le travail et les supports des différents formateurs ?
- Possible source d'inspiration : cf. les PDF et les vidéo sur https://github.com/CSHoggard/-gmm_liverpool_2020

### Références
- Prévoir une mise en commun des PDF de bonnes références (manuels généraux d'introduction à la GM, articles théoriques, articles d'étude de cas, ...) dont nous disposons.

## 4. (TODO) Programme

À modifier / compléter à foison ! On part sur le principe de journées de 6h (?).

### Intro / Présentation d'un cas concret (resp. : ? ;  durée : 1h)
- Accueil et intro générale
- Motivation : présentation d'un article de recherche intéressant, avec l'ensemble de la démarche en imagerie 3D.

### Acquisition de données : théorie (resp. : ? ; durée : 2h)
- Notions "théoriques" sur les outils d'acquisition de données (acquisition tomographique, etc.), l'hébergement et la sauvegarde des fichiers obtenus.
- Manipulation de meshes, segmentation, etc. 
> *{BD} on est déjà dans du traitement, pas dans l'acquisition. renommer Acquisition et traitement?*
- Présentation des différents logiciels qui seront utilisés (privilégier [3DSlicer](https://www.slicer.org/) et/ou TIVMI, qui sont gratuits).

### Acquisition de données : pratique (resp. : ? ; durée : 9h)
- Segmentation
- Acquisition de landmarks 2D/3D :
  - Utilisation de logiciels spécifiques (TIVMI, tpsDig, viewbox ...) pour la pose de landmarks et/ou semi-landmarks.
  - Chaque stagiaire (ou binôme de stagiaire) effectue la pose de landmarks pour 2 à 3 individus, puis les données acquises par les étudiants sont mises en commun.

### Généralités et rappels en morpho géométrique (resp. : ? ; durée : 3h ?)
- Historique et généralités.
- Logiciels dispo (ImageJ, R, ...).
- Notions théoriques : forme, taille, allométrie, types de landmarks, superposition procustéenne, morphospace, espace tangent, etc.

### Demi-journée R ?
À voir comment la caser en termes de timing.

### Morpho géométrique sur landmarks 2D/3D (resp. : ? ; durée : 9h ?)
Utilisation de R pour :
- Étude de l'erreur intra/inter-obs
- Visualisation de formes 3D
- ACP sur données de landmarks
- Analyse discriminante / clustering / autres stat amusantes de votre choix.

### Morpho géométrique : compléments (resp. : ?  ; durée : ~ 9h ?)
- Théorie des semilandmarks / sliding landmarks : bending energy, etc.
- Déformations TPS, principal warps, relative warps, etc.
- Analyse pratique avec R (ou autre)

### Morpho géométrique "avancée" (resp. : ?  ; durée : ~ 12 ou 15h ?)
Proposer une inscription *séparée* à ce module, pour les plus motivés. :-) Attention : prévoir là aussi des données pour cette partie de la formation (et pas nécessairement les mêmes que pour le tronc commun).
- Analyse des contours 2D (Fourier, etc.), exemple avec R.
- Analyse par EDMA, exemple avec R.
- Analyse par difféomorphisme, exemple avec R.
- Estimation de landmarks ou de parties manquantes, exemple avec R.

## 5. Formateurs
Les membres suivants de PACEA pourraient intervenir à différentes étapes de la formation.
- [x] Priscilla Bayle (un peu de tout plutôt de J1 à J3)
- [x] Hélène Coqueugniot
- [x] Isabelle Crevecoeur (J 1 et 2)
- [x] Bruno Dutailly (J 1 et 2)
- [x] Yann Heuzé
- [x] Adeline Le Cabec (J1 et 2)
- [x] Laura Maréchal (J 3 et 4, voire 1 et 2 si besoin)
- [X] Frédéric Santos (pour une partie des jours 3, 4 et 5)
- [X] Antoine Souron (plutôt jours 1 et 2)
- [X] Nicolas Vanderesse
- [x] Clément Zanolli

**Possibilité d'intervenants extérieurs :** faites vos suggestions ci-dessous !
- [ ] Vincent Bonhomme (http://www.vincentbonhomme.fr/) ?
- [x] Julien Claude ?
- [x] Renaud Lebrun ? (https://isem-evolution.fr/membre/lebrun/)
- [x] Thomas Cucchi ?
- [ ] Nicolas Navarro ? (http://nnavarro.free.fr/)
- [ ] Vincent Debat ? (http://www.evomorpho.com/vincent.html)
- [ ] Neus Martinez Abadias ?(https://webgrec.ub.edu/webpages/000011/ang/neusmartinez.ub.edu.html)
- [ ] Jean Dumoncel (difféomorphisme) ? (https://www.3dmorph.org/presentation/)
- [ ] Christian Hoggard (https://cshoggard.netlify.app/) ?
- [ ] Florent Détroit
- [x] Patricia Wils
- [ ] Dimitri Neaux (covariation ?)
- [ ] Philipp Gunz (ALC: On peut aussi demander à Simon Neubauer?)
- [ ] Sélim Natahi (ALC: idem pour Alexandra Schuh qui sera sur Bordeaux)
- [ ] Mona Le Luyer
- [ ] Markus Bastir
- [ ] Michaël Coquerelle
- [ ] Mikel Arlegui
- [ ] Paul O'Higgins
- [ ] Laura Martin-Frances
- [ ] Zewdi Tsegai (https://www.eva.mpg.de/evolution/staff/zewdi-tsegai/) 
