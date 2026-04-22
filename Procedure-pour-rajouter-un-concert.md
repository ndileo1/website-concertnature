Bonjour jeune padawan,

Tu vas devoir suivre cette procédure pour rajouter un concert :

1. Aller dans le dossier concerts-model
2. Copier les 2 fichiers en-xxxx et fr-xxxx
3. Les coller dans le dossier content/en/post et content/fr/post
4. Modifier les fichiers avec les informations du concert (information importante :
        - date: 2026-04-25T23:59:00 
            La date au format Année-Mois-Jour, A modifier  
            T : Un séparateur standard (Time) 23:59:00 : L'heure au format Heures:Minutes:Secondes.) Ne pas modifier l'heure
        - Le reste des informations sont à modifier selon le concert (images, lieu, description, etc)


5. Créer une branche Git
    git checkout -b add-concert-nom-du-concert

6. Ajouter les modifications
    git add .

7. Commiter les modifications
    git commit -m "Ajout du concert : nom-du-concert"

8. Pousser les modifications
    git push -u origin add-concert-nom-du-concert

9. Créer une Pull Request
    Allez sur GitHub : https://github.com/ndileo1/website-concertnature
    Cliquez sur le bouton "Compare & pull request" qui vient d'apparaître.

![alt text](image.png)

    Puis cliquez sur "Create pull request".

![alt text](image-1.png)


10. Fusionner (Merge) sur GitHub
    Une fois la Pull Request créée, cliquez sur le bouton vert "Merge pull request"
    
![alt text](image-2.png)

    Puis cliquez sur "Confirm merge".

![alt text](image-3.png)

11. Bravo ton site est en ligne ! Maintenant il te faut revenir à la normale sur ton ordinateur (en local)
    git checkout master
    git pull

    