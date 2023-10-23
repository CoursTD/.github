# Comment partager votre exercice :

## Initialiser Git & GitHub
1. Créez un compte GitHub
2. Envoyez-moi votre adresse mail de compte GitHub pour que je vous donne la permission de partager votre code
3. Téléchargez Git pour avoir les commandes git dans votre invite de commande : [Windows x64](https://github.com/git-for-windows/git/releases/download/v2.42.0.windows.2/Git-2.42.0.2-64-bit.exe) / [Mac OS](https://sourceforge.net/projects/git-osx-installer/files/latest/download)
4. Ouvrez l'executable/installer téléchargé et suivez les étapes d'installation

## Partager votre exercice
1. Sélectionnez le dépôt en fonction du canal de votre exercice :
   - [C Fundamentals](https://github.com/CoursTD/c-fundamentals)
2. Sélectionnez le bouton vert <img alt="**Code**" src="https://cdn.discordapp.com/attachments/1012372287640567948/1166035471361642586/image.png?ex=65490628&is=65369128&hm=a9042bc9a298e8a8b64e7306e078edaaaa57bf33008f45f3ebbc5270af337010&" width="75px"/> et copiez l'URL (exemple: https://github.com/CoursTD/c-fundamentals.git)
3. Dirigez-vous dans le répertoire où vous désirez mettre vos cours/exercices et faites **clic droit > ouvrir dans le terminal**
4. Dans le terminal, executez `git clone coller-url` en remplaçant par l'URL précédemment copiée
5. Executez la commande `git checkout nomPrenom` en remplaçant par votre nom et votre prénom
6. Ensuite, ouvrez le dossier et vous pouvez mettre vos exercices (vous pouvez ouvrir le dossier dans votre IDE sans soucis)
   - Vous pouvez soit copier/coller vos programmes dans le `main.c`, soit les faire directement dedans, soit remplacer le `main.c` par votre fichier `main.c`
7. Ensuite, vous pouvez partager vos modifications en effectuant la suite de commandes ci-dessous :
   - `git add .`
   - `git commit -m "Voici mon exercice"`
   - `git push origin nomPrenom` (en remplaçant par votre nom et votre prénom)
C'est tout bon !
