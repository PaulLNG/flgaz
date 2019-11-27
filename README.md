# Découverte des outils - Rédigez un court texte répondant aux questions suivantes

- Que propose le site PythonAnywhere.com ? Quelles actions ont été réalisés ?

Pythonanywhere est à la fois un environnement de développement intégré en ligne et un service d'hébergement Web basé sur le langage de programmation Python.

Il permet d'héberger gratuitement son application Python et de pouvoir la visualiser directement en ligne. Pour cela , il suffit d'importer un projet (fichiers et dossiers de celui-ci) sur une Web App que vous aurez préalablement créée sur votre compte Pythonanywhere puis d'indiquer la source de votre code (le path) et le fichier qui devra être éxécuté en premier. 

Il vous suffira ensuite d'accéder au lien de votre application fourni par Pythonanywhere et vous pourrez visualiser celle-ci.

- Qu'est-ce que Flask ? 

Flask est un framework open source développé en Python , il est maintenu dans un seul fichier Python.
Il est très simple d'utilisation et à pour équivalent en NodeJS (au niveau de son poid et de ses fonctionnalités) le framework ExpressJS.
Dans notre projet , nous utilisons Flask pour définir les routes de notre application dans le fichier "app.py".

- Quels sites connus utilise FLASK ? 

Des sites connus comme google , spotify ou bien isntagram utilisent FLASK.

# Description des actions réalisées

Quelles étapes avez-vous suivi ?

- Créer un compte sur Pythonanywhere 
- Créer une Web App à partir de notre compte Pythonanywhere
- Importer notre projet (fichiers et dossiers) sur la web app précedemment créée
- Configurer le chemin du wordspace , du code source ainsi que le nom du fichier à éxécuté lors de l'accès au lien de l'application
- Accéder au lien de l'application via le dashboard

Quelles difficultés avez-vous rencontrées ?

Je n'ai pas rencontré de réelles difficultés pour mettre en place l'application sur Pythonanywhere et pour appréhender les fonctionnalités que propose celles-ci.

# Réflexions sur le projet

- Quels sont, selon vous, les aspects techniques limitants du projet FLGAZ dans l'état initial ?

La non disposition de bouton empêche une navigation rapide entre les différentes fonctionnalités de l'application. Il faut changer l'URL à chaque fois.


- Quelles sont, selon vous, les menaces auxquelles un tel projet peut être soumis ?

Le framework FLASK est très légers et ne dispose pas de toutes les fonctionnalités requises pour la sécurisation d'une application.


# Que fait l'application FLGAZ ?

L'application flgaz dispose d'un fichier "gazouille.csv" contenant à chaque ligne des informations ( auteur du tweet & message du tweet ).

Ces informations sont utilisées par l'application de différentes façon selon l'url sur laquelle nous sommes. Chaque URL fera appel à une routes qui éxécutera un code précis. 

Par exemple :

- Si nous sommes sur l'url "/gaz" , nous aurons un formulaire que nous pourrons remplir afin d'ajouter une nouvelle ligne dans notre fichier csv.

- Si nous sommes sur l'url "/timeline" , nosu pourrons voir l'intégralité des informations stocké dans le fichier csv. 


