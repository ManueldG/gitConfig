imposta user e email
git config --global user.name "ManueldG"
git config --global user.email manuel.dellagala@gmail.com

dichiara la directory affidabile
git config --global --add safe.directory D:/giorno5

crea chiave da inserire nelle impostazioni github
ssh-keygen -t rsa -C "manuel.dellagala@gmail.com"

test del collegamento
ssh -T git@github.com

crea ramo
git branch -M main

imposta ramo remoto
git remote add origin https://github.com/ManueldG/exJava.git

abilita upstream
git push --set-upstream exJava master
