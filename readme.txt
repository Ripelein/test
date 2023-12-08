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

rit rm --cached tim.py					/Poistaa tiedoston
