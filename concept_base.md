_______variables_________

**Definitions et deffirences**
 - var: permet de déclarer une variable et éventuellement d'initialiser sa valeur.
 - let:  permet de déclarer une variable dont la portée est celle du bloc courant, éventuellement en initialisant sa valeur.
 - const: permet de déclarer une variable constante qui ne peut pas être réassignée. La référence est fixe, mais le contenu des objets peut changer.

**cas d'utilisation**
 - Utilisez const par défaut pour toutes vos déclarations de variables. Cette option est la plus sûre car elle empêche les réassignations accidentelles et rend le code plus prévisible. Choisissez
   const chaque fois que la valeur de la variable n'a pas besoin d'être modifiée après son initialisation.
 - Optez pour let lorsque vous avez besoin de réassigner une variable dans votre code. Utilisez-le dans des cas spécifiques comme les compteurs de boucles, les variables qui doivent changer de valeur
   au cours de l'exécution, ou lorsque la valeur doit être mise à jour dynamiquement.
 - Évitez généralement var dans le code moderne. Bien qu'il fonctionne encore, var a une portée de fonction qui peut mener à des bugs subtils et des comportements inattendus. Réservez son usage
   uniquement pour la maintenance d'ancien code legacy.

   

