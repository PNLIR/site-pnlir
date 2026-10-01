# Site institutionnel du PNLIR

**Programme National de Lutte contre l’Insuffisance Rénale**
Ministère de la Santé et de la Population — République du Congo

Site officiel du programme : informer sur la maladie rénale, orienter vers
le dépistage, et rendre publiques les données et les projets du programme.

## Contenu du dépôt

| Fichier | Rôle |
|---|---|
| `index.html` | Le site entier : pages, styles, scripts, polices, images et documents |
| `apercu-pnlir.png` | Image affichée lors d’un partage sur WhatsApp, Facebook, LinkedIn |

Le site tient dans un seul fichier. Il ne nécessite ni base de données,
ni PHP, ni serveur applicatif : un hébergement statique suffit.

## Mise en ligne

Le dépôt est relié à Hodi. Toute modification déposée ici est publiée
automatiquement sur le site.

## Modifier le site

Le fichier est volumineux (environ 2,7 Mo) : **téléversez une nouvelle version**
plutôt que d’utiliser l’éditeur en ligne, qui peine sur cette taille.

1. `Add file` → `Upload files`
2. Glisser le nouveau `index.html` (le nom doit être exactement celui-ci)
3. Décrire la modification en bas de page, puis `Commit changes`

Chaque version est conservée : en cas d’erreur, l’onglet `Commits` permet
de revenir en arrière.

## Ce que contient le site

**Dix rubriques** — Accueil, Le Programme, Partenaires, Santé Rénale,
Statistiques, Projets, Actualités, Faire un don, Nous contacter, Ressources.
Plus deux pages accessibles depuis le pied de page : mentions légales et
politique de confidentialité.

**Cinq langues** — français, anglais, espagnol, chinois, arabe (avec
inversion complète de la mise en page pour l’arabe).

**Contenus** — 6 examens de dépistage détaillés, 8 hôpitaux référencés,
2 projets réalisés et 4 en cours, le Plan de Travail Annuel Budgétisé 2026
en téléchargement, une vidéo de sensibilisation (« Protégez vos reins :
dites non au tabac »), mentions légales et politique de confidentialité.

**Données** — chaque chiffre publié provient d’une étude évaluée par les
pairs ou d’un document officiel du programme, avec sa source.

## Politique de confidentialité

Mise à jour le 25 septembre 2026, dans les cinq langues. Elle décrit :

- le responsable du traitement (le PNLIR, son adresse et ses contacts) ;
- la lettre d’information : données collectées (adresse, date, langue,
  origine de l’inscription), finalité, conservation, désabonnement ;
- le rôle de Google (feuille de calcul et envoi des lettres) ;
- l’hébergement et les journaux techniques du serveur ;
- les liens vers les réseaux sociaux et les vidéos YouTube ;
- les droits prévus par la loi n°29-2019 du 10 octobre 2019.

Un lien vers la politique figure sous la case de consentement de la
newsletter. **Si le site change** (nouvel outil, nouveau formulaire,
mesure d’audience), la politique doit être mise à jour en même temps.

## La vidéo

La vidéo est placée dans le bloc « Sensibilisation sur les réseaux sociaux »,
qui apparaît dans Actualités et, recopié automatiquement, sur l’Accueil.

- Avant le clic, le visiteur voit une vignette aux couleurs du programme :
  rien n’est chargé depuis YouTube.
- Au clic, la vidéo se lit dans la page, en mode « confidentialité avancée »
  (youtube-nocookie.com).
- Si le fichier est ouvert directement sur un ordinateur (double-clic),
  YouTube refuse son lecteur : la vidéo s’ouvre alors sur YouTube.
  **Testez toujours la vidéo sur le site en ligne.**

Pour remplacer la vidéo, chercher `xDSgXXqhoKw` dans `index.html` et
remplacer cet identifiant (deux occurrences) par celui de la nouvelle vidéo,
puis adapter le titre.

## Choix techniques

- Fichier unique : fonctionne hors connexion une fois la page chargée
- Polices intégrées au fichier : aucune requête vers Google Fonts
- Aucun cookie, aucun traceur, aucune mesure d’audience, aucune publicité
- Aucune connexion à un service extérieur pendant la visite, sauf si le
  visiteur s’inscrit à la newsletter (Google) ou lance la vidéo (YouTube)
- Testé jusqu’à 320 pixels de largeur
- Icônes déclarées en double syntaxe, pour les navigateurs antérieurs à 2017
- Le contenu reste visible même si le JavaScript échoue
- Animations désactivées pour qui a demandé à en réduire l’usage

## À faire après la mise en ligne

- Trois balises de partage pointent vers une adresse provisoire
  (`https://www.pnlir.cg`). Elles doivent être corrigées avec l’adresse
  réelle, sinon les liens partagés s’afficheront sans image ni titre.
- Compléter les coordonnées de l’hébergeur dans les mentions légales.
- Vérifier que la vidéo se lit bien sur le site en ligne.

## Contact

programmenir@gmail.com — 06 915 57 53 · 05 610 59 13
13, avenue Auxence Ickonga, enceinte du CHU de Brazzaville
