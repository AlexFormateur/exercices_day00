Pré-requis:

-   Les variables, propriétés, tableau etc doivent être en anglais. Les valeurs peuvent être n'importe quoi dans n'importe quelles langues.
-   `var` et `function` interdit ---> let, const et fonctions fléchées obligatoire.

Exemple:
var toto = "toto" --- interdit
let toto = "toto" --- autorisé
const toto = "toto" --- autorisé

function toto() { return true } --- interdit
const toto = () => { return true } --- autorisé

-   À vous de créer les objets, tableaux etc pour vos tests, ça vous entrainera à en écrire des objets, tableaux... par exemple et faire des recherches sur internet si besoin pour apprendre à le faire.
-   Les exercices sont "théoriquement" du plus facile au plus difficile.
-   Vous devez terminé un exercice pour passer au suivant.
-   Tout est autorisé, votre but est de savoir développer, copier coller bêtement ne vous fera pas décrocher de job, comprendre oui.
-   Ce n'est pas une course, comprennez ce que vous faites.
-   ChatGPT interdit sauf pour le formateur <3

"Puisses le sort vous être favorable."

## EXERCICES

1. Écrivez une fonction qui prend un nombre en entrée et renvoie un boolean `true` si ce nombre est un nombre premier, sinon un boolean `false`.

2. Écrivez une fonction qui prend une variable en entrée et affiche son type.

3. Écrivez une fonction qui prend en entrée un tableau d'éléments et renvoie un tableau qui ne contient que les éléments uniques de l'entrée.

Par exemple, si l'entrée est [1, 2, 3, 2, 1], la sortie sera [1, 2, 3]

4. Écrivez une fonction qui prend une chaîne de caractères en entrée et vérifie si cette chaîne est un mot de passe valide. La fonction doit renvoyer les boolean true ou false.
   (Le password doit contenir au moins 8 caractères, au moins une majuscule, au moins un chiffre)

5. Écrivez une fonction qui trie un tableau d'entiers par ordre croissant et renvoie le résultat.

6. Écrivez une fonction qui utilise la décomposition pour extraire les propriétés de l'objet books et les afficher.
   const books = { title: "Harry Potter", autor: "J.K. Rowling", editor: "Gallimard" }

7. Écrivez une fonction qui prend un tableau d'objets "employees" (employés) en entrée et renvoie la somme des salaires de tous les employés.
   Un objet "employee" sera formaté par exemple comme ceci:
   const employee1 = { name: "John Doe", salary: "1500" }
   const employee2 = { name: "Tidus", salary: "7500" }

8. Écrivez une fonction qui prend un objet employé en entrée et modifie son salaire. Affichez le nouveau salaire de l'employé.

9. Écrivez une fonction qui prend un tableau d'objets livre en entrée et renvoie un tableau qui ne contient que les livres écrits par un auteur spécifié.

10. Écrivez une classe qui représente un livre, avec les propriétés suivantes : title, autor, numberOfPages.
    Ecrire une méthode qui affiche les propriétés du livre.
    Instanciez un objet de cette classe et appelez la méthode d'affichage.
