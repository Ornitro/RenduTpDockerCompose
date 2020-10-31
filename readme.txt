Ouvrez un terminal de commande linux
Allez à l'endroit où vous souhaitez récupérer les fichiers nécessaires à la création du docker à l'aide de la commande "cd" (et ajouter le nom du dossier dans lequel aller, ou .. pour sortir du dossier actuel)
tapez la commande "docker-compose up"
Attendez la fin de la création du docker
Ouvrez une page internet et tapez "http://localhost:5001/"
Vous devriez voir le résultat du code présent dans le app.py (ici un code qui compte le nombre de fois que cette page à été ouverte).

Pour arréter le docker :
ctrl+c
lancez la commande "docker-compose down"
