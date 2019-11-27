# Qu'est-ce que Flask ?

Flask est un framework open source développé en Python , il est maintenu dans un seul fichier Python.
Il est très simple d'utilisation et à pour équivalent en NodeJS (au niveau de son poid et de ses fonctionnalités) le framework ExpressJS.
Dans notre projet , nous utilisons Flask pour définir les routes de notre application dans le fichier "app.py".

# Qu'est-ce que Pythonanywhere ?

Pythonanywhere est à la fois un environnement de développement intégré en ligne et un service d'hébergement Web basé sur le langage de programmation Python.

Il permet d'héberger gratuitement son application Python et de pouvoir la visualiser directement en ligne. Pour cela , il suffit d'importer un projet (fichiers et dossiers de celui-ci) sur une Web App que vous aurez préalablement créée sur votre compte Pythonanywhere puis d'indiquer la source de votre code (le path) et le fichier qui devra être éxécuté en premier. 

Il vous suffira ensuite d'accéder au lien de votre application fourni par Pythonanywhere et vous pourrez visualiser celle-ci.

# Que fait l'application flgaz ?

L'application flgaz dispose d'un fichier "gazouille.csv" contenant à chaque ligne des informations ( auteur du tweet & message du tweet ).

Ces informations sont utilisées par l'application de différentes façon selon l'url sur laquelle nous sommes. Chaque URL fera appel à une routes qui éxécutera un code précis. 

Par exemple :

- Si nous sommes sur l'url "/gaz" , nous aurons un formulaire que nous pourrons remplir afin d'ajouter une nouvelle ligne dans notre fichier csv.

- Si nous sommes sur l'url "/timeline" , nosu pourrons voir l'intégralité des informations stocké dans le fichier csv. 
