## DMBootstrap

### Structure géneral de la page 
La page est enveloppée dans une div class="container">. Cette classe Bootstrap est utilisée pour créer une mise en page centrée et réactive. Elle assure que le contenu de la page est correctement aligné et dimensionné sur différents dispositifs.

### En-tête (Header)
 Le logo est inclus dans la div id="logo">. Aucune classe Bootstrap n'est utilisée ici, ce qui est approprié car il s'agit d'une image personnalisée.
 La barre de recherche est contenue dans <div role="search" id="recherche_conteneur"> avec un formulaire personnalisé en Css.

### Menu de navigation
Le menu de navigation utilise les classes Bootstrap pour créer un menu déroulant. 
la classe nav class="navbar navbar-expand-lg">, crée une barre de navigation extensible qui s'adapte aux écrans de taille moyenne et supérieure.

Chaque élément de menu est défini dans une liste non ordonnée ul avec des éléments de liste li. Les sous-menus déroulants sont créés avec des ul imbriqués et des classes Bootstrap pour gérer le déroulement.

### Fil d'Ariane (Breadcrumb)

J'ai également utilisé le fil d'Ariane (vu en cours) avec la classe Bootstrap list-unstyled et un élément de liste pour chaque étape ce qui permet d'avoir une liste ordonée

### Contenu principal

Le contenu principal est encapsulé dans un élément <main> avec la classe Bootstrap col-md-9. Cette classe assure que la colonne occupera 9 colonnes sur les écrans de taille moyenne et supérieure. Les différentes rubriques du tableau de bord sont affichées dans des div class="rubriques col-lg-4"> avec une image et une liste d'éléments. Les classes Bootstrap col-lg-4 sont utilisées pour gérer la mise en page, garantissant que chaque rubrique occupe 4 colonnes sur les écrans de taille large.

### Colonne de droite (Sidebar)

La colonne de droite est encapsulée dans un élément aside> avec la classe Bootstrap col-md-3. Cette classe assure que la colonne occupera 3 colonnes sur les écrans de taille moyenne et supérieure.

Les "Astuces" et "Actualités" sont affichées dans des div class="rubrique2 rubriques"> et div class="rubrique1 rubriques">. Ces classes Bootstrap aident à styliser les sections.

### Footer

Le pied de page est structuré en utilisant des classes Bootstrap pour créer des colonnes et des listes. Les liens et les informations légales sont organisés dans des listes stylisées.


### Conclusion

En résumé, j'ai choisi de faire l'integralité de la page en Bootstrap pour améliorer la mise en page tout en préservant la personnalisation de certains éléments tels que le logo et la barre de recherche. 
