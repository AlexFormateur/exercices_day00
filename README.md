Exercices Javascript / ES6+

Pré-requis:

-   Les variables, propriétés, tableau etc doivent être en anglais. Les valeurs peuvent être n'importe quoi dans n'importe quelles langues.
-   `var` et `function` interdit ---> let, const et fonctions fléchées obligatoire.

Exemple:

    -   `var toto = "toto"` --- interdit
    -   `let toto = "toto"` --- autorisé
    -   `const toto = "toto"` --- autorisé
    -   `function toto() { return true }` --- interdit
    -   `const toto = () => { return true }` --- autorisé

-   À vous de créer les objets, tableaux etc pour vos tests. (Vous n'avez pas besoin d'effacer les données utiliser pour vos tests)
-   Les exercices sont "théoriquement" du plus facile au plus difficile.
-   Vous devez terminé un exercice pour passer au suivant.
-   Tout est autorisé, sauf si c'est interdit =D.
-   Votre but est de devenir developpeur, copier coller bêtement ne vous fera pas décrocher de job, comprendre ce que vous copier coller, oui.
-   Ce n'est pas une course, comprennez ce que vous faites.
-   Les excercices servent à évaluer votre niveau, en aucun cas ne pas atteindre le dernier niveau sera péjudiciable !
-   ChatGPT interdit (sauf pour le formateur <3)
-   Les boucles for etc c'est bien, les fonctions natives comme .map(), .filter(), etc, c'est mieux ! À votre guise.
-   Google est votre ami, si besoin de le formateur aussi !

"Puisses le sort vous être favorable."

## EXERCICES

1. Écrivez une variable nommé `name` qui prend en valeur "Sephiroth"

2. Écrivez un tableau `years` qui prend en valeurs: 2020, 2021, 2022

3. Écrivez un object qui contient les propriétés: title, autor, editor qui prend en valeur: "lord of the rings", "J.R.R.Tolkien" "HarperCollins Publishers Ltd".

4. Écrivez une fonction qui prend une variable en entrée et affiche son type.

5. Écrivez une fonction qui prend un nombre en entrée et renvoie un boolean `true` si ce nombre est un nombre premier, sinon un boolean `false`.

6. Écrivez une fonction qui prend une chaîne de caractères en entrée et vérifie si cette chaîne est un mot de passe valide. La fonction doit renvoyer les boolean `true` ou `false`.
   (Le password doit contenir au moins 8 caractères, au moins une majuscule, au moins un chiffre)

7. Écrivez une fonction qui trie un tableau d'entiers par ordre croissant et renvoie le résultat.

8. Écrivez une fonction qui utilise la décomposition pour extraire les propriétés de l'objet books et les afficher.
   ` const books = { title: "Harry Potter", autor: "J.K. Rowling", editor: "Gallimard" }`

9. Écrivez une fonction qui prend un objet employé en entrée et modifie son salaire. Affichez le nouveau salaire de l'employé.

10. Écrivez une fonction qui prend un tableau d'objets "employees" (employés) en entrée et renvoie la somme des salaires de tous les employés.
    Un objet "employee" sera formaté par exemple comme ceci:
    `const employee1 = { name: "John Doe", salary: "1500" }`
    `const employee2 = { name: "Tidus", salary: "7500" }`

11. Écrivez une fonction qui prend en entrée un tableau d'éléments et renvoie un tableau qui ne contient que les éléments uniques de l'entrée.

    Par exemple, si l'entrée est [1, 2, 3, 2, 1], la sortie sera [1, 2, 3]

12. Écrivez une fonction qui prend un tableau d'objets livre en entrée et renvoie un tableau qui ne contient que les livres écrits par un auteur spécifié.

13. Écrivez une classe qui représente un livre, avec les propriétés suivantes : title, autor, numberOfPages.
    Ecrire une méthode qui affiche les propriétés du livre.
    Instanciez un objet de cette classe et appelez la méthode d'affichage.
