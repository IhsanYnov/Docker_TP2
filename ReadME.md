2. Compléter le Dockerfile afin de builder correctement l’application contenu dans src/
   Dockerfile annexe
  a. Une option de npm vous permet de n’installer que ce qui est nécessaire.
     Quelle est cette option ? Quelle bonne pratique Docker permet t-elle de
     respecter ?
     > RUN npm install --production
     L'option --production permet de ne télécharger que les fichiers pertinents

3. A l’aide de la commande docker build, créer l’image ma_super_app
   >docker build . --tag ma_super_app

4. Compléter le fichier docker-compose.yml afin d’éxécuter ma_super_app avec sa
   base de données.
   docker-compose.yml annexe
