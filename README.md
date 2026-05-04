# 📝 Gestionnaire de Tâches (Todo List) en C++

une application console permettant de gérer efficacement des tâches personnelles avec organisation, filtrage et persistance des données.


## 🚀 Fonctionnalités

*   **Gestion complète des tâches** : Ajout, modification et suppression de tâches.
*   **Organisation intelligente** :
    *   **Priorités** : Haute, Moyenne, Basse.
    *   **Statuts** : À faire, En cours, Terminée.
    *   **Catégories** : Travail, Personnel, Urgent, Autre.
*   **Tri et Filtrage** : Visualisation ciblée par champ ou tri combiné par priorité et date de création.
*   **Persistance des données** : Sauvegarde automatique et chargement à partir de fichiers texte (`tasks.txt` pour la lecture humaine et `formated_tasks.txt` pour l'importation).

## 🛠️ Installation et Exécution

Vous pouvez utiliser ce gestionnaire de deux manières :

### 1. Utiliser l'exécutable (Windows)
Téléchargez directement le fichier `todolist.exe` depuis les "Releases" :
👉 [Lien de téléchargement version finale](https://github.com/6db9/mini-project-task-manager/releases/tag/v2)

### 2. Compiler à partir des sources
Si vous préférez compiler le code vous-même, récupérez le fichier source :
[Todo List.cpp](https://github.com/6db9/mini-project-task-manager/blob/main/Todo%20List/Todo%20List.cpp)

**Commande de compilation (nécessite un compilateur supportant le C++20) :**
```bash
# Compilation du code
g++ -std=c++20 'Todo List.cpp' -o TaskManager

# Exécution de l'application
./TaskManager
```

## 📋 Mode d'emploi
1.  **Lancement** : Exécutez le programme pour accéder au menu principal.
2.  **Ajout** : Saisissez le titre, la priorité et la catégorie. L'ID et l'heure de création sont générés automatiquement.
3.  **Sauvegarde** : Utilisez l'option **Export** avant de quitter pour conserver vos données.
4.  **Reprise** : Au prochain lancement, utilisez l'option **Import** et saisissez `formated_tasks.txt` pour restaurer votre liste.

---
**Auteur** : [Khalid Azaanoun]  
