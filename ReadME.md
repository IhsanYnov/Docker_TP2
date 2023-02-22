2. Compléter le Dockerfile afin de builder correctement l’application contenu dans src/

  a. Une option de npm vous permet de n’installer que ce qui est nécessaire.
     Quelle est cette option ? Quelle bonne pratique Docker permet t-elle de
     respecter ?
     
     RUN npm install --production
     
     L'option --production permet de ne télécharger que les fichiers pertinents
