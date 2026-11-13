# Compteur XP pour Dofus 3

Outil Windows qui suit tes sessions Dofus : il lit tout seul l'XP, les kamas et le butin à l'écran (chat et fin de combat), même en multi-comptes. Gains par heure et par personnage, passages en donjon, objectifs de niveau, bilan de tes journées, valeur du butin selon les prix HDV et historique des sessions.

Simples captures d'écran : il ne touche pas au jeu et ne clique jamais à ta place. Gratuit, sans compte, sans connexion à Ankama. Projet de fan non officiel.

## Télécharger

**[⬇ Télécharger Compteur XP.zip](https://github.com/eltacosanchez/compteur-xp-dofus/raw/main/Compteur%20XP.zip)**

## Installer

1. **Avant de décompresser** : clic droit sur `Compteur XP.zip` > Propriétés > coche **« Débloquer »** en bas > OK. Sinon Windows peut bloquer le programme, parce qu'il vient d'internet.
2. Clic droit > **« Extraire tout… »**, et mets le dossier `Compteur XP` où tu veux.
3. Double-clique sur **`Compteur XP.vbs`**. La fenêtre s'ouvre après quelques secondes.

Il faut Windows 10 ou 11 avec la langue française installée (c'est déjà le cas sur un Windows en français), et Dofus 3 avec tes personnages connectés.

## Utiliser

- Joue normalement : la session démarre toute seule au premier combat.
- L'XP est lue dans le chat ; les kamas et le butin sur le panneau de fin de combat : laisse-le affiché 2 ou 3 secondes.
- En haut : **XP**, **Kamas** ou **Ressources**. Dans l'historique, double-clique sur une session pour voir ce qu'a gagné chaque personnage.
- Tes fenêtres Dofus peuvent être les unes derrière les autres, mais pas réduites dans la barre des tâches.

## Ce qu'il sait faire

- **Donjons** : il reconnaît tout seul le donjon et la salle, compte chaque passage (temps, XP, kamas, butin, boss), garde tes records et te dit quel donjon te rapporte le plus.
- **Objectif** : donne un niveau à atteindre, il affiche ce qu'il reste d'après la vraie barre d'XP du jeu, le temps de jeu nécessaire et la date probable. Objectifs d'XP du jour et de la semaine.
- **Bilan** : totaux du jour, de la semaine et du mois, courbes de la session, records, heures et zones les plus rentables, pour toute l'équipe ou un seul personnage.
- **Mini-compteur** posé par-dessus le jeu (Ctrl+Alt+X), alertes (objectif atteint, record battu, objet recherché, combat peut-être manqué).
- **Corrections à la main** par clic droit : un combat, une quantité, un nom d'objet, un prix.
- **Réglages** : taille de l'affichage, couleur, sons, alertes, export pour Excel, copies de secours.

## Prix des ressources : avec le Suivi HDV

La valeur de ton butin (onglet **Ressources**) est calculée grâce au **[Suivi HDV](https://github.com/eltacosanchez/suivi-HDV)**, l'autre outil gratuit qui relève les prix de l'Hôtel de vente quand tu regardes une ressource dans Dofus.

- Mets les dossiers `HDV` et `Compteur XP` côte à côte, dans un même dossier : le compteur prend tout seul le prix moyen de chaque ressource.
- Une ressource que tu n'as jamais relevée à l'HDV compte pour 0.
- Sans le Suivi HDV, tout le reste marche quand même : seule la valeur du butin reste à 0.

Tout est expliqué dans le fichier `LISEZ-MOI.txt` du dossier.

## Les autres compteurs

Même principe, pour d'autres jeux d'Ankama : ils lisent seulement l'écran, sans toucher au jeu. Chacun est un programme à part, qui s'installe comme le Compteur XP (débloquer le zip, extraire, double-cliquer sur le fichier `.vbs`).

- **Compteur Wakfu** : l'XP de chaque combat, ton niveau et le butin lus dans le chat de Wakfu, une carte par personnage et un objectif de niveau.
  **[⬇ Télécharger Compteur Wakfu.zip](https://github.com/eltacosanchez/compteur-xp-dofus/raw/main/Wakfu/Compteur%20Wakfu.zip)**
- **Compteur Rétro** : l'XP, les kamas et l'XP de la monture lus dans le chat de Dofus Rétro, gains par heure et objectif de niveau.
  **[⬇ Télécharger Compteur Rétro.zip](https://github.com/eltacosanchez/compteur-xp-dofus/raw/main/Retro/Compteur%20R%C3%A9tro.zip)**

Ces deux-là ne se mettent pas encore à jour tout seuls : pour une nouvelle version, retélécharge le zip et garde ton dossier `donnees`.

## Mises à jour

Elles sont **automatiques** : au démarrage, le compteur regarde s'il existe une nouvelle version ici. Si oui, un bouton doré **« Installer la v… »** apparaît en haut : un clic, et c'est installé. Tes sessions et ton historique sont gardés.

Tu as une version d'avant la 1.3 ? Installe une fois **[la mise à jour à la main](https://github.com/eltacosanchez/compteur-xp-dofus/raw/main/Compteur%20XP%20-%20mise%20%C3%A0%20jour.zip)** : décompresse-la, puis double-clique sur `Installer la mise à jour.vbs`. Ensuite, les mises à jour arriveront toutes seules.

Les nouveautés de chaque version sont dans `NOUVEAUTES.txt`.
