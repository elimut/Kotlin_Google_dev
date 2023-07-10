# Kotlin Google Android avec Compose

## Premier programme avec Kotlin

    fun main() {
        println("Hello, world!")
    }

Comment ça marche ? 
**Un programme Kotlin doit disposer d'une fonction principale, qui correspond à l'endroit précis de votre code où commence le compilateur Kotlin. La fonction principale est le point d'entrée (ou point de départ) du programme.**

### Composantes d'une fonction

Une fonction est un segment d'un programme qui exécute une tâche spécifique. Votre programme peut avoir une seule ou plusieurs fonctions.

#### Définir vs appeler une fonction

Dans votre code, vous commencez par **définir ou déclarer une fonction**. Vous devez donc spécifier toutes les instructions nécessaires pour effectuer cette tâche.
Une fois la fonction définie, vous pouvez l'**appeler** afin que les instructions qu'elle contient soient effectuées ou exécutées.

##### Définir une fonction

Voici les éléments clés nécessaires pour définir une fonction :

- La fonction a besoin d'un **nom** pour que vous puissiez l'appeler plus tard.
- La fonction peut également nécessiter des entrées ou des informations à fournir une fois appelée. La fonction utilise ces entrées pour remplir son objectif. Les entrées sont facultatives, et certaines fonctions ne nécessitent aucune entrée.
- La fonction comporte également un **corps**, qui contient les instructions pour effectuer la tâche.

![Fonction](img/fonction.png)

Retenez les éléments clés d'une fonction présentés dans l'exemple d'une fonction principale que vous avez vu dans Kotlin Playground :

- **La définition de la fonction commence par le mot fun**.
- Le nom de la fonction est alors main.
-Comme il n'existe aucune entrée pour la fonction, les parenthèses sont vides.
- Le corps de la fonction contient une ligne de code, println("Hello, world!"), située entre les accolades d'ouverture et de fermeture de la fonction.

![Fonction](img/Fun_fonction.png)



## Sources

[Google dev](https://developer.android.com/codelabs/basic-android-kotlin-compose-first-program?hl=fr&continue=https%3A%2F%2Fdeveloper.android.com%2Fcourses%2Fpathways%2Fandroid-basics-compose-unit-1-pathway-1%3Fhl%3Dfr%23codelab-https%3A%2F%2Fdeveloper.android.com%2Fcodelabs%2Fbasic-android-kotlin-compose-first-program#3)