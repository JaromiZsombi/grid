# Git verziókezelés

## Helyi repo létrehozása

- helyi repo inicializálása
    > git init
- ellenőrzés:
    > git status
- előkészítjük az commit-ra (a verzió létrehozására):
    > git add .
- ellenőrzés:
    >git status
- commit:
    >git commint -m "first commit"
- a commit-ok listázása
    > git log

## Helyi repo összekapcsolása a távoli repoval

- távoli repo létrehozása 
- a helyi repo összekapcsolása a távolival
    > git remote add origin ...token@github.com...
- a legelső alkalommal a push:
    > git push -u origin master
-a továbbiakban:
    > git push

-magamnak git init után:
    > git config user.name
    > git config user.email