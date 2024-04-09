Voici un guide détaillé pour un utilisateur novice qui souhaite télécharger et exécuter mon projet à partir de GitHub. 

1. Téléchargement du Projet :
        - Téléchargez l'archive :
            1. Cliquez sur le bouton "Code" et sélectionnez "Download ZIP".
            2. Extrayez le fichier ZIP sur votre ordinateur.
  
2. Création de l'Environnement Virtuel:
    - créé un environnement virtuel:
        - Sur Windows :
            ```
            python -m venv env
            env\Scripts\activate
            ```
       
3. Installation des Dépendances :
    - Ouvrez une vs code
    - Accédez au répertoire du projet (où se trouve le fichier requirements.txt).
    - Exécutez la commande suivante pour installer les dépendances :
        ```
        pip install -r requirements.txt
        ```

4. Appliquer les Migrations :
    - exécutez dans le terminale :
        ```
        python manage.py makemigrations
        python manage.py migrate
        ```
6. Création d'un (Admin) :
    -  exécutez :
        ```
        python manage.py createsuperuser
        ```
    - Suivez les instructions pour entrer votre nom d'utilisateur, votre adresse e-mail et votre mot de passe.


