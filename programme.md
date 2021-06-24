Formation 3D PACEA
=================

## 1. Cadre général

- **Organisation** : prend place dans le cadre des Graduate Schools UB.
- **Public cible :** M2 Biogéosciences, Doctorants, Membres permanents de PACEA
- **Objectifs :**
    - Rendre autonomes les étudiants et doctorants pour leurs analyses 3D et la pratique de la morphométrie géométrique
    - Organiser un transfert de compétences entre membres de PACEA concernant ces thématiques

> *{YH} Souhaitons-nous limiter la formation à la morphométrie géométrique ou bien tenterions-nous, ne serait-ce qu'a minima, de présenter d'autres méthodes morphométriques de type EDMA, Fourrier, Difféomorphisme...?*

- **Partenaires possibles** : CRP2A, Ausonius.
> *{BD} Ausonius??? CRP2A why not, ils font de l'imagerie. Si non, il y a archeovision qui maitrise l'archivage des données 3D, acquisition surfacique (photogrammétrie et laser), et le traitement des données (topologie de mesh pour impression 3D par ex)*
 
## 2. Modalités

- Formation de 5 jours pleins, durant l'été 2022 (fin juin / début juillet).
- ~ 15 participants maximum.
- Les formateurs seront rémunérés par UB.
- Lieu : à définir (mais sur le campus bordelais).

## 3. Contenu de la formation
L'idée est d'offrir une formation concernant l'ensemble de la chaîne de traitement 3D : acquisition de données brutes (µCT, ...), segmentation, pose de landmarks (ou pas si landmark-free morphometrics), morphométrie géométrique, traitements statistiques en aval.

## 4. Formateurs ?
Les membres suivants de PACEA pourraient intervenir à différentes étapes de la formation. Si vous ne souhaitez pas intervenir, rayez simplement votre nom. Si vous souhaitez intervenir, précisez sur quelles thématiques du programme (voir plus bas).
- [x] Bruno Dutailly (J 1 et 2)
- [x] Yann Heuzé
- [ ] Adeline Le Cabec
- [x] Laura Maréchal (J 3 et 4, voire 1 et 2 si besoin)
- [X] Frédéric Santos (pour une partie des jours 3, 4 et 5)
- [X] Antoine Souron (plutôt jours 1 et 2)
- [X] Nicolas Vanderesse
- [x] Clément Zanolli

**Possibilité d'intervenants extérieurs :** faites vos suggestions ci-dessous !
- [ ] Vincent Bonhomme (http://www.vincentbonhomme.fr/) ?
- [x] Julien Claude ?
- [ ] Renaud Lebrun ? (https://isem-evolution.fr/membre/lebrun/)
- [x] Thomas Cucchi ?
- [ ] Nicolas Navarro ? (http://nnavarro.free.fr/)
- [ ] Vincent Debat ? (http://www.evomorpho.com/vincent.html)
- [ ] Neus Martinez Abadias ?(https://webgrec.ub.edu/webpages/000011/ang/neusmartinez.ub.edu.html)
- [ ] Jean Dumoncel (difféomorphisme) ? (https://www.3dmorph.org/presentation/)
- [ ] Christian Hoggard (https://cshoggard.netlify.app/) ?
- [ ] Florent Détroit
- [ ] Patricia Wils
- [ ] Dimitri Neaux (covariation ?)

## 5. Ébauche de programme

Très très préliminaire et indicatif ! N'hésitez pas à modifier / compléter.

### Jour 1 : Acquisition de données (théorie)

- Notions "théoriques" sur l'acquisition de données (µCT, etc.), l'hébergement et la sauvegarde des fichiers obtenus.
- Manipulation de meshes, segmentation, etc. 
> *{BD} on est déjà dans du traitement, pas dans l'acquisition. renommer Acquisition et traitement?*
- Présentation de différents logiciels d'imagerie (Avizo, TIVMI, Dragonfly, Fiji, etc.).
- Présentation d'un cas concret : des scans ou images (2D ou 3D)  seront remis aux stagiaires, qui devront effectuer de la saisie de données le lendemain. Présentation du contexte scientifique de l'étude.

### Jour 2 : Acquisition de données (pratique)
- Utilisation de logiciels spécifiques (TIVMI, tpsDig, viewbox ...) pour la pose de landmarks et/ou semi-landmarks.
- Chaque stagiaire (ou binôme de stagiaire) effectue la pose de landmarks pour 2 à 3 individus, puis les données sont mises en commun à la fin de la journée. La suite de la formation se base sur les données réelles acquises par les stagiaires.
- On inclura par la suite une phase "analyse de l'erreur intra-obs" si le temps le permet.
> *[]Cela me parait au contraire crucial et devrait même être un des premiers points à aborder {AS}*
>
> *{LM} D'accord avec Antoine, d'autant qu'il existe plusieurs écoles pour les tests intra-obs et ce serait bien de les passer en revue? (cf. notamment von Cramon-Taubadel et al. 2007)*
### Jour 3 : Morphométrie géométrique (les bases)
- Historique et généralités.
- Logiciels dispo (ImageJ, R, ...).
- Notions théoriques : forme, taille, allométrie, types de landmarks, superposition procustéenne.
- Cas des semilandmarks / sliding landmarks : bending energy, etc.
- Analyse pratique avec R (ou autre).
> *{LM} Pour info : l'historique, les généralités, les notions théoriques, etc sont vues dans le cours d'Introduction à la morpho géo et aux FEA en M1 puis en M2.*   

### Jour 4 : Morphométrie géométrique (un peu plus avancée)
- ACP sur données de landmarks / semilandmarks.
- Déformations TPS, principal warps, relative warps, etc.
- Analyse pratique avec R (ou autre)
> *{LM} Ici on pourrait rajouter une intro au difféomorphisme, si vous trouvez ça pertinent. Je peux participer à cette partie au besoin. En ce qui concerne les analyses pratiques, je pense que ce serait super de faire ça sur R en effet. Pour info encore : en M2, les étudiants ont un TP de morpho où je leur montre comment utiliser MorphoJ.*

### Jour 5 : Analyses statistiques en aval
- Analyse discriminante, MANOVA, régression, clustering.
- Retour sur l'allométrie.
- Conclusion de la formation.