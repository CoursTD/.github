# Comment partager votre exercice :

## Initialiser Git & GitHub
1. Créez un compte GitHub
2. Envoyez-moi votre adresse mail de compte GitHub pour que je vous donne la permission de partager votre code
3. Téléchargez Git pour avoir les commandes git dans votre invite de commande : [Windows x64](https://github.com/git-for-windows/git/releases/download/v2.42.0.windows.2/Git-2.42.0.2-64-bit.exe) / [Mac OS](https://sourceforge.net/projects/git-osx-installer/files/latest/download)
4. Ouvrez l'executable/installer téléchargé et suivez les étapes d'installation

## Partager votre exercice
### Initialiser le répertoire
1. Sélectionnez le dépôt en fonction du canal de votre exercice :
   - <a href="https://github.com/CoursTD/c-fundamentals" target="_BLANK">C Fundamentals</a>
2. Sélectionnez le bouton vert <img alt="**Code**" src="https://cdn.discordapp.com/attachments/1012372287640567948/1166035471361642586/image.png?ex=65490628&is=65369128&hm=a9042bc9a298e8a8b64e7306e078edaaaa57bf33008f45f3ebbc5270af337010&" height="30px"/> et copiez l'URL (exemple: https://github.com/CoursTD/c-fundamentals.git)
3. Dirigez-vous dans le répertoire où vous désirez mettre vos cours/exercices et faites **clic droit > ouvrir dans le terminal**
4. Dans le terminal, executez `git clone coller-url` en remplaçant par l'URL précédemment copiée
5. Créez une nouvelle branche à votre nom avec `git branch nomPrenom` en remplaçant par votre nom et votre prénom
6. Executez la commande `git checkout nomPrenom` en remplaçant par votre nom et votre prénom pour focus cette branche et travailler dessus
### Travailler sur la branche
7. Ensuite, ouvrez le dossier et vous pouvez mettre vos exercices (vous pouvez ouvrir le dossier dans votre IDE sans soucis)
   - Vous pouvez soit copier/coller vos programmes dans le `main.c`, soit les faire directement dedans, soit remplacer le `main.c` par votre fichier `main.c`
9. Ensuite, vous pouvez partager vos modifications en effectuant la suite de commandes ci-dessous :
   - `git add .`
   - `git commit -m "Voici mon exercice"`
   - `git push origin nomPrenom` (en remplaçant par votre nom et votre prénom)
### Dernière étape de partage
10. Rendez-vous sur GitHub dans le répertoire de l'exercice (exemple: https://github.com/CoursTD/c-fundamentals) et cliquez sur le bouton <img alt="**Code**" src="https://cdn.discordapp.com/attachments/1012372287640567948/1166040535732076555/image.png?ex=65490adf&is=653695df&hm=486d2711e51727fba50761047da7ed5128e2053bc46de527ea7ea36358a5e811&" height="30px"/> et validez avec <img alt="**Code**" src="https://cdn.discordapp.com/attachments/1012372287640567948/1166041170900697220/image.png?ex=65490b77&is=65369677&hm=ab426969f251f58af99a02d800915d7f7351444ba5b50673185c690c73a4f845&" height="30px"/>

C'est tout bon !
