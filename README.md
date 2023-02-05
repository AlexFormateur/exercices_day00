Exercices Javascript / ES6+

Prérequis:

-   Les variables, propriétés, tableaux etc doivent être en anglais. Les valeurs peuvent être n'importe quoi, dans n'importe quelles langues.
-   `var` et `function` sont interdits ---> let, const et fonctions fléchées obligatoires.

Exemple:

    -   `var toto = "toto"` --- interdit
    -   `let toto = "toto"` --- autorisé
    -   `const toto = "toto"` --- autorisé
    -   `function toto() { return true }` --- interdit
    -   `const toto = () => { return true }` --- autorisé

-   À vous de créer les objets, tableaux etc pour vos tests. (Vous n'avez pas besoin d'effacer les données utiliser pour vos tests, ce sera plus pratique pour la correction)
-   Les exercices sont "théoriquement" des plus faciles au plus difficile.
-   Vous devez terminer un exercice pour passer au suivant.
-   Tout est autorisé, sauf si c'est interdit.
-   Votre but est de devenir développeur, copier coller bêtement ne vous fera pas décrocher de job, comprendre ce que vous copier coller, oui.
-   Ce n'est pas une course, comprennez ce que vous faites.
-   Les exercices servent à évaluer votre niveau, en aucun cas ne pas atteindre le dernier niveau sera préjudiciable !
-   ChatGPT interdit (sauf pour le formateur <3)
-   Les fonctions natives comme .map(), .filter(), etc, sont vos amis ! Vous pouvez choisir entre les boucles `for`, etc ou utiliser les fonctions natives du langage.
-   Une consigne doit être strictement respectée.
-   Un bug ou consigne non respecté vaut 0.
-   Google est votre ami, vos voisins et si besoin le formateur aussi !
-   Chaque exercice devra être nommé dans un fichier formater de cette manière: numeroExercice.js (1.js)
-   Le fichier sera lancé via la commande `node` et s'afficher dans le terminal.
-   Des objets, variables, tableaux qui auront servi pour vos tests devront être présent dans le fichier de l'exercice pour votre correcteur.
-   Le correcteur pourra modifier vos données de tests ou en créer de nouveau si besoin.

"Puisses le sort vous être favorable."

## EXERCICES

1. Écrivez une variable nommé `name` qui prend en valeur la sring "Sephiroth".

2. Écrivez un tableau `years` qui prend en valeurs les integer: 2020, 2021, 2022.

3. Écrivez une fonction qui prend une variable en entrée et affiche son type.

4. Écrivez une fonction qui prend un integer en entrée et renvoie un boolean `true` si c'est un nombre pair, sinon renvoyer un boolean `false`.

5. Écrivez un object qui contient les propriétés: `title`, `autor`, `editor` qui prend en valeur les string: "lord of the rings", "J.R.R.Tolkien" "HarperCollins Publishers Ltd".

6. Écrivez une fonction qui prend une string en entrée et vérifie si cette chaîne est un mot de passe valide. La fonction doit renvoyer les boolean `true` ou `false`.
   Le password doit contenir au moins 8 caractères, au moins une majuscule, au moins un chiffre, pas d'espace.

7. Écrivez une fonction qui trie un tableau d'integer par ordre croissant et renvoie le résultat.

8. Écrivez une fonction qui utilise la décomposition (destructuring) pour extraire les propriétés de l'objet books et les afficher en les séparants par une virgule.
   `const books = { title: "Harry Potter", autor: "J.K. Rowling", editor: "Gallimard" }`

9. Écrivez une fonction qui prend un objet `employee` en entrée et modifie son salaire en ajoutant 100 a la valeur. Affichez le nouveau salaire de l'employé.
   Exemple d'objet:
   `const employee = { name: "John Doe", salary: "1500" }`

10. Écrivez une fonction qui prend un tableau d'objets "employees" (employés) en entrée et renvoie la somme des salaires de tous les employés.
    Exemple d'objet:
    Voir exercice 9.

11. Écrivez une fonction qui prend en entrée un tableau d'éléments et renvoie un tableau qui ne contient que les éléments uniques de l'entrée.
    Par exemple, si l'entrée est [1, 2, 3, 2, 1], la sortie sera [1, 2, 3]
    Les entrées peuvent être de type string ou number.

12. Écrivez une fonction qui prend un tableau d'objets livre en entrée et renvoie un tableau qui ne contient que les livres écrits par un auteur spécifié.
    Exemple d'objet:
    Voir exercice 8.

13. Écrivez une classe qui représente un livre, avec les propriétés suivantes : `title`, `autor`, `numberOfPages`.
    Ecrire une méthode qui affiche les propriétés du livre.
    Instanciez un objet de cette classe et appelez la méthode d'affichage.
