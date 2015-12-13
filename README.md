# mysmsbackup
Development of application MySmsBackup (Exports SMSes to file or sync SMSes to Gmail account).

Ce projet a été créé sous Android Studio. Il ne comporte, sur GitHub, que les fichiers .JAVA
Une fois compilé et déployé, il permets de lancer une exportation des SMS vers un fichier texte sur le téléphone Android,
et permets aussi de synchroniser les SMS avec un ou plusieurs comptes GMAIL.
Au premier lancement, il y a création d'une base de données embarquée sur le téléphone, permettant de stocker les mots de
passe des comptes GMAIL détectés. Les mots de passes doivent être entrés manuellement à la première synchronisation et
le mot de passe entré n'est stocké que si l'authentification avec le serveur GMAIL se fait correctement.

Pour le moment cette application ne traite que les SMS et non les MMS.

Je suis en train de voir pour la synchronisation des MMS avec un serveur GMAIL, et aussi pour la possibilité de choisir de
synchroniser les fichiers attachés aux MMS avec un serveur GMAIL.

L'exportation vers un fichier texte ne permets pas la ré-importation. Cette fonction est destinée au personnes qui veulent
pouvoir imprimer rapidement leurs SMS.

Je dois donc ajouter la fonction d'export vers un fichier XML et la fonction de ré-import depuis le fichier XML.

Il reste encore beaucoup de travail. Cette version est grosso-modo un draft de l'application finale qui devrait être
développée dans les jours et semaines qui viennent.
