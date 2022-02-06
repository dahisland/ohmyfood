# Projet OHMYFOOD

Ohmyfood! est une jeune startup qui voudrait s'imposer sur le marché de la restauration.

L'objectif est de développer un site 100% mobile qui répertorie les menus de restaurants gastronomiques.
En plus des systèmes classiques de réservation, les clients pourront composer le menu de leur repas pour que les plats soient prêts à leur arrivée.

Finis les temps d'attente au restaurant !

## Identité de la marque

Ohmyfood! est une entreprise de commande de repas en ligne.
Son concept permet aux utilisateurs de composer leur propre menu et de réduire leur temps d’attente dans les
restaurants car leur menu est préparé à l’avance.
Plus de perte de temps à consulter la carte !

## Services proposés

L'entreprise souhaite proposer à ses clients des menus de restaurants gastronomiques.
Développé à New-York dans un premier temps, elle cherche désormais à élargir son concept pour la capitale de la gastronomie : Paris.

## Public visé

Le positionnement de l'entreprise s'oriente vers un marché de niche, auprès de restaurants luxueux pour les villes
dans lesquelles ils sont établis.
Sa volonté est d'être identifiée comme une entreprise proposant des services haut de gamme.
Sa clientèle cible : classes moyennes et supérieures, connectées et souvent pressées, souhaitant déguster des
produits de qualité.

## Concurrence

Les points forts des entreprises concurrentes :

- Bonne implémentation en France.
- Tarifs préférentiels sur les menus.
- Site web très dynamique.
- Bon référencement.
- Beaucoup de choix de restaurants.
- Mise en valeur des menus proposés sur la page d'Accueil du site.

Les points faibles des entreprises concurrentes :

- Pas de possibilité de voir en détail les menus.
- Dates de réservation limitées à 2 jours par semaine.
- Pas de possibilité de réservation en ligne.
- Pas de possibilité d’agrandir les menus.

# Consignes de base

## Objectifs

1. Phase 1 : Développer un site proposant le menu de 4 grands restaurants parisiens.
2. Phase 2 : Permettre la réservation en ligne et la composition de menus.

## Spécifications techniques

1. Le développement devra se faire en CSS, sans JavaScript.
2. Aucun framework ne devra être utilisé, en revanche l’utilisation de SASS serait un plus.
3. Aucun code CSS ne devra être appliqué via un attribut style dans une balise HTML.
4. Tout le code doit être versionné sur GitHub et le site devra être accessible sur Github Pages une fois terminé.
5. Le site doit être développé en mobile-first et devra se conformer aux maquettes fournies.
   La mise en page est libre pour les versions tablettes et desktop.
6. L'ensemble du site doit être responsive pour les résolutions smartphones, tablettes et desktop.
7. Toutes les pages du sites doivent être conformes aux normes W3C en HTML et CSS.
8. Le site doit être parfaitement compatible sur les dernières versions de Chrome et Firefox.
9. Le site doit se conformer aux éléments de la charte graphique :
   - Police du logo et des titres : Shrikhand
   - Police du texte : Roboto
   - Couleur primaire : #9356DC
   - Couleur secondaire : #FF79DA
   - Couleur tertiaire : #99E2D0
10. Cette première version du site (le prototype) doit être livrée sous 1 mois.

## Livrables attendus

### Contenu des pages

1. PAGE D'ACCUEIL (x1) :

   - Affichage de la localisation des restaurants.
     À terme il sera possible de choisir sa localisation pour trouver des restaurants proches d’un certain lieu.
   - Une courte présentation de l’entreprise (voir maquette).
   - Une section contenant les 4 menus sous forme cartes.
     Au clic sur la carte, l’utilisateur est redirigé vers la page du menu correspondant.

2. PAGES DE MENUS (x4) :

   - 4 pages contenant chacune le menu d’un restaurant.
     (Le détail des textes des menus est fourni dans un fchier .txt).

3. FOOTER DES PAGES :

   - Le footer est identique sur toutes les pages.
   - Au clic sur “Contact”, un renvoi vers une adresse mail est effectué.

4. HEADER DES PAGES :

   - Le header est présent sur toutes les pages.
   - Sur la page d’accueil, il contient le logo du site.
   - Sur les pages de menu, il contient en plus un bouton de retour vers la page d’accueil.

### Effets graphiques et animations

Des effets accessibles au clic ou au survol sont visibles sur la maquette.
Ils devront utiliser des animations ou transitions CSS, pas de JavaScript ni de librairie.

1. BOUTONS :

   - Au survol, la couleur de fond des boutons principaux devra légèrement s’éclaircir.
     L’ombre portée devra également être plus visible.
   - À terme, les visiteurs pourront sauvegarder leurs menus préférés.
     Pour cela, un bouton "J’aime" en forme de cœur est présent sur la maquette.
     Au clic, il devra se remplir progressivement.
     Pour cette première version, l’effet peut apparaître au survol sur desktop au lieu du clic.

2. PAGE D'ACCUEIL :

   - Quand l’application aura plus de menus, un “loading spinner” sera nécessaire.
     Sur ce prototype, l'entreprise souhaite en avoir un aperçu.
     Il devra apparaître pendant 1 à 3 secondes quand on arrive sur la page d'accueil, couvrir l'intégralité de l'écran, et utiliser les animations CSS (pas de librairie).
     Le design de ce loader n’est pas défini, toute proposition est donc la bienvenue tant qu’elle est cohérente avec la charte graphique du site.

3. PAGES DE MENU :

   - À l’arrivée sur la page, les plats devront apparaître progressivement avec un léger
     décalage dans le temps.
     Ils pourront soit apparaître un par un, soit par groupe “Entrée”, “Plat” et “Dessert”.
     Un exemple de l’effet attendu est fourni.
   - Le visiteur peut ajouter les plats qu'il souhaite à sa commande en cliquant dessus.
     Cela fait apparaître une petite coche à droite du plat.
     Cette coche devra coulisser de la droite vers la gauche.
     Pour cette première version, l’effet peut apparaître au survol sur desktop au lieu du clic.
     Si l’intitulé du plat est trop long, il devra être rogné avec des points de suspension.
     Un exemple de l’effet attendu est fourni.

# Bilan du projet

Un prototype HTML/CSS a été réalisé conformément aux consignes énoncées précédemment.
Les fichiers rendus se composent d'un index.html accompagné de ses fichiers CSS de mise en forme.
Le projet répond aux attentes du client sur les point suivants :

- HTML et CSS conformes aux normes W3C.
- Design en mobile-first, également responsive pour les résolutions desktop et tablettes.
  Le design a également été optimisé pour les écrans larges afin d'optimiser le rendu du site sur toutes les résolutions.
- Respect du design et de la charte graphique, conformément aux maquettes et au brief fournis.
- Compatibilité du prototype avec les dernières versions de Chrome et de Firefox.
- Utilisation de flexbox et de grid pour optimiser le responsive design.
- Usage de balises sémantiques appropriées pour faciliter l'accessibilité et le référencement du site.
- Utilisation du pré-processeur SASS pour générer des fichiers CSS de qualité optimale et faciliter la lecture
  du code pour les équipes backend en charge de réaliser la seconde version du site.
- Le projet a été versionné sur Github et est hébergé sur Git pages.
- Aucun framework n'a été utilisé pour la conception de cette première version.
- Les différentes animations demandées ont été réalisées en CSS avec des @keyframes et des transitions.

  Temps de réalisation du projet : environ 3 semaines.
