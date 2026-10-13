# SEG2505 — Laboratoire 5 : RecyclerView (Java)

## Objectif
Implémenter une liste dynamique Android avec `RecyclerView`, `Adapter`, `ViewHolder` et `LinearLayoutManager`, d'après la documentation Android « Créer des listes dynamiques avec RecyclerView ».

## Application
L'application affiche les douze mois de l'année dans une liste verticale défilante. Chaque ligne est définie dans `text_row_item.xml` et alimentée par `CustomAdapter.java`.

## Structure
- `app/src/main/java/ca/uottawa/seg2505/mdc102/MainActivity.java` : jeu de données et configuration du RecyclerView.
- `app/src/main/java/ca/uottawa/seg2505/mdc102/CustomAdapter.java` : création et liaison des vues.
- `app/src/main/res/layout/activity_main.xml` : écran principal.
- `app/src/main/res/layout/text_row_item.xml` : ligne individuelle.
- `app/build.gradle` : dépendances AndroidX.

## Exécution
1. Ouvrir le dossier `MDC-102` dans Android Studio.
2. Attendre la synchronisation Gradle (SDK Android 35 requis ; AGP 8.7.3 et JDK 17).
3. Sélectionner un émulateur et lancer la configuration `app`.
4. Faire défiler la liste jusqu'à « Décembre » et revenir en haut.

## Tests à réaliser
- Démarrage de l'application sans erreur.
- Affichage des douze mois dans le bon ordre.
- Défilement jusqu'au dernier élément.
- Rotation portrait/paysage et accessibilité des éléments.

**Statut :** exemple de projet fourni pour aider à réaliser le tutoriel ; compilation et tests réels à effectuer sur l'ordinateur de l'étudiant. Ne pas utiliser des captures simulées comme preuves.
