# Verziókezelés git

- helyi repo létrehozása
    > git init

- ellenörzés: milyen fájlok változtak?(az előző verzióhoz képest)
    > git status
- előkészítjük(stage=színpad) az új verziót, minden fájlt amiben történt módusolás:
    >git add .
- ellenőrzünk:
    >git status
- felhasználónév beállítása:
    >git config user.name felhasznalonev
- email cím beállítása:
    > git config user.email emailcim
- az új verzió megszületése:
    > git commit -m "first commit"


- távoli repo létrehozása(GitHub)
- a helyi repo és a GitHub repo összekapcsolása, úgy hogy PAT történjen a hitelesítés(token@):
    > git remote add origin https://token@github.com/sbtsmk/....
- Az első push:
    > git push -u origin master
- további push-ok esetén:
    > git push