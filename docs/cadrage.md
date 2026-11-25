# Note de cadrage : refonte du site du CISEI

Version de travail, novembre 2026. Document à discuter avec les responsables de l'association.

## 1. Pourquoi refaire le site

Le site actuel ([ciseionline.it](https://www.ciseionline.it)) a été conçu vers 2012 et n'est plus mis à jour depuis plusieurs années. Une analyse complète a été réalisée (voir [l'audit](audit-site-existant.md)). Les points essentiels :

| Constat | Conséquence |
|---|---|
| Le site ne s'adapte pas aux téléphones | Sur mobile, le texte s'affiche à environ 5 px : illisible pour une grande partie des visiteurs |
| Le contenu est figé (dernière actualité en 2018, dernier événement en 2011) | Le site donne l'image d'une association inactive |
| Le menu et les titres sont des images | Le site est inutilisable avec un lecteur d'écran, mal référencé par Google, et impossible à modifier sans logiciel de retouche |
| Le bandeau cookies ne fonctionne pas, alors que Google Analytics mesure les visites | Non-conformité au RGPD |
| La technologie est obsolète (ASP classique, bibliothèques de 2009) | Risques de sécurité, maintenance de plus en plus difficile |
| Les 4 langues ne sont pas à jour de la même façon | Les visiteurs anglophones, germanophones et lusophones voient un site incomplet |
| L'adhésion passe par un virement et un bulletin papier | Peu de visiteurs vont jusqu'au bout |

Le CISEI a pourtant un atout rare : **une archive de plus de 3 millions de noms d'émigrés italiens**. Le nouveau site doit la mettre au premier plan.

## 2. Objectifs proposés

1. **Mettre la recherche dans l'archive au cœur du site**, dès la page d'accueil, simple à utiliser sur ordinateur comme sur téléphone.
2. **Faciliter l'adhésion aux « Amici del CISEI »**, au moment où le visiteur en a envie (par exemple quand il trouve une fiche qui l'intéresse).
3. **Donner l'image d'un centre d'études vivant et crédible** : actualités, publications, récits, partenaires.
4. **Offrir un vrai site multilingue**, rédigé et non traduit automatiquement.
5. **Être conforme** : accessibilité, RGPD, mentions légales, transparence.
6. **Être facile à mettre à jour** par l'équipe, sans compétences techniques.

## 3. Publics visés

| Public | Ce qu'il vient chercher |
|---|---|
| Descendants d'émigrés, généalogistes (public principal) | Retrouver un ancêtre, comprendre son parcours |
| Chercheurs et étudiants | Sources, publications, bibliothèque, contacts scientifiques |
| Musées, institutions, partenaires | Présentation du centre, projets, réseau |
| Communautés italiennes à l'étranger | L'annuaire CiseiNet, les échanges |
| Donateurs et mécènes | Comprendre l'utilité du centre, soutenir |

## 4. Périmètre

### Inclus dans la refonte

- Le site principal : accueil, présentation du centre, archive, publications, actualités et événements, newsletter, adhésion, contact, mentions légales et transparence.
- Une nouvelle identité visuelle pour le web, qui respecte les éléments existants (pictogramme, couleurs).
- La reprise des contenus utiles : mission, sources de l'archive, publications, newsletters, documents de transparence.
- Les redirections depuis les anciennes adresses, pour ne pas perdre les visiteurs ni le référencement.

### À décider avec l'association

- **La base de données de recherche** (`/portomondo/`) : la garder telle quelle et la relier au nouveau site, l'habiller aux nouvelles couleurs, ou la reconstruire plus tard.
- **CiseiNet** (annuaire des communautés) : il a déjà un design plus récent. L'intégrer ou le garder à part.
- **Les récits et mini-bases** (`/raccontimigranti/`, `/storiemigranti/`) : à intégrer au site principal ou non.
- **Les langues** : italien et anglais au minimum ; allemand et portugais seulement si quelqu'un peut les tenir à jour.

### Hors périmètre (pour l'instant)

- Paiement en ligne de l'adhésion (possible dans un second temps).
- Espace membre avec compte personnel.

## 5. Principes de la nouvelle version

- **Simple** : un menu court, une page d'accueil claire, peu de clics pour trouver.
- **Mobile d'abord** : pensé pour le téléphone, puis élargi à l'ordinateur.
- **Accessible** : textes lisibles, contrastes suffisants, navigation au clavier et au lecteur d'écran.
- **Sobre et durable** : peu de technologies, un hébergement peu coûteux, une maintenance légère.
- **Respectueux de la vie privée** : pas de suivi sans consentement.

## 6. Démarche proposée

| Étape | Contenu | Validation par l'association |
|---|---|---|
| 1. Cadrage | Cette note, réponses aux questions ci-dessous | Objectifs, périmètre, langues |
| 2. Directions artistiques | 3 planches d'ambiance (couleurs, typographies, images, croquis de l'accueil), voir le [benchmark](benchmark.md) | Choix d'une direction |
| 3. Maquettes | Maquettes Figma de la direction retenue : accueil, recherche, adhésion, une page de contenu, version mobile | Validation des maquettes |
| 4. Contenus | Mise à jour des textes, de l'équipe, des chiffres, traductions | Validation des textes |
| 5. Réalisation | Développement, reprise des contenus, redirections | Recette avant mise en ligne |
| 6. Mise en ligne | Bascule, suivi des premières semaines | — |

Les trois pistes artistiques envisagées :

- **Registro** : l'archive savante, inspirée des registres d'embarquement. Sobre, crédible, scientifique.
- **Partenze** : le voyage et la mer, Gênes et le port. Plus émotionnel, tourné vers les descendants.
- **Rete** : un réseau moderne et participatif, tourné vers la diaspora d'aujourd'hui.

## 7. Questions pour l'association

### Identité et ressources

1. Disposez-vous du logo en haute définition ou en vectoriel (fichiers AI, EPS, SVG, PDF) ?
2. Avez-vous des photos en bonne résolution : siège de la Commenda di Prè, documents d'archive, événements, équipe ?
3. Pouvons-nous obtenir les couvertures des publications et les logos des partenaires en bonne qualité ?
4. Avez-vous une charte graphique, même ancienne ?

### Contenus

5. Qui compose aujourd'hui l'équipe, le conseil et le comité scientifique ?
6. Les contacts, horaires et adresses e-mail sont-ils toujours valables ?
7. Quels sont les tarifs et les avantages actuels de l'adhésion ?
8. Les chiffres de l'archive (3 millions de noms) sont-ils à jour ?
9. La newsletter continue-t-elle ? Quelles activités récentes (depuis 2018) peut-on mettre en avant ?

### Organisation

10. Quelles langues garder ? Qui pourra rédiger ou relire les traductions ?
11. Qui mettra le site à jour après la mise en ligne, et à quelle fréquence ?
12. Y a-t-il un budget (hébergement, nom de domaine, éventuels services) ?
13. Y a-t-il une échéance (événement, anniversaire, demande d'un financeur) ?
14. Qui valide les décisions (une personne référente, le conseil) ?

### Technique

15. Qui gère aujourd'hui l'hébergement chez Aruba et le nom de domaine ?
16. Qui a développé la base de données de recherche, et peut-on obtenir son code ou un export ?
17. Que souhaitez-vous faire de la base de données, de CiseiNet, des récits et mini-bases ?

## 8. Ce dont nous avons besoin pour avancer

- **Un accord écrit pour analyser la base de données** et l'annuaire CiseiNet. Idéalement, un accès direct (code, export de la base ou compte chez l'hébergeur) : ce serait plus fiable et plus respectueux que des recherches répétées depuis l'extérieur.
- **Une personne référente** pour répondre aux questions et valider chaque étape.
- **Les réponses aux questions ci-dessus**, même partielles.

## 9. Décisions attendues à l'issue de cette note

- [ ] Objectifs validés
- [ ] Périmètre validé (base de données, CiseiNet, récits)
- [ ] Langues retenues
- [ ] Personne référente désignée
- [ ] Accord pour l'analyse de la base de données
- [ ] Rendez-vous fixé pour la présentation des directions artistiques
