Avaa Git Bash ->
cd Desktop
CD GitProject
git init
touch tim.py						/Luo tiedosto
touch readme.txt					/Luo tiedosto

git status
git add .						/Lisää tiedostot
git status

git commit -m "first Change"

Lisää tekstiä readme.txt-tiedostoon ja tallenna
git status
git add readme.txt

git config --global user.email "riku.leino11@gmail.com" /Lisää sähköpostiosoite

git rm --cached tim.py					/Poistaa tiedoston
git commit -m "third Change"				/Poisto vahvistettava

git branch login					/Lisätään haara
git checkout login					/Avataan haara
Lisää tim.py tiedostoon import os ja tallenna
git add .
git commit -m "Update"
git checkout master					/Siirrytään masteriin jossa ei ole tim.py tiedostoa 
git merge login						/Yhdistää login haaran master haaraan ja yliajaa tiedostot

Luo github repository verkossa
https://github.com/Ripelein/test			/Lisää vain nimi ja lisää

git remote
https://github.com/Ripelein/test.git

git remote add tutorial https://github.com/Ripelein/test.git /Lisätty repository

Lisätään toimivat tiedosto githubiin
git push -u tutorial master				/master versio
git push -u tutorial login				/login haara
git config --global user.name Riku


Näin kopioidaan projekti githubista
cd Desktop
mkdir chess						/Luodaan kansio chess
git pull https://github.com/Ripelein/test.git





