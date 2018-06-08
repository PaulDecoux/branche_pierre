FORKEZ ce repo

cd ~/Sites

mkdir branch_test

cd branch_test

git init

git remote add fork [VOTRE LIEN FORK]

git remote add branch git@github.com:PierreDemailly/branche_pierre.git

git pull branch master

git checkout -b [VOTRE PRENOM]

[AJOUTEZ VOTRE FICHIER DANS ~/Sites/branch_test]: soit style.css, soit work.html, soit contact.html

git add [VOTRE FICHIER]

git commit -m "Votre message"

git push fork [VOTRE PRENOM]

Faites une PULL REQUEST
