## Použití verzovacího nástroje GIT
Tento návod Ti pomůže s použitím GITu během předmětu 4IZ268. Hodně štěstí!



### Setup, Ready, Go!
1. Nainstaluj si GIT v počítači -- [https://git-scm.com/downloads](https://git-scm.com/downloads), všude dávej Next.
2. Registruj se na GitHub -- [https://github.com/join](https://github.com/join).
3. Otevři příkazové okno CMD nebo PowerShell v domovském adresáři, např. v **`C:\Users\User\Projects\`**, 
    - tj. otevřeš tuto složku, podržíš SHIFT, klikneš někam pravou myší a vybereš CMD nebo PowerShell.
4. **Naklonuj** si tento repozitář, 
    - tj. spustíš příkaz **`git clone https://{XXXX}@github.com/nvbach91/4IZ268-{YYYY}-{YYYY}-{SS}.git`**, přitom: 
        - nahradíš **`{XXXX}`** svým **username** na github, např. **`nvbach91`**,
        - nahradíš **`{YYYY}-{YYYY}`** aktuálními roky, např. **`2018-2019`**,
        - nahradíš **`{SS}`** buď **`ZS`** nebo **`LS`**,
        - tedy celkem např. **`git clone https://nvbach91@github.com/nvbach91/4IZ268-2018-2019-ZS.git`**,
        - takhle dostaneš adresář s názvem **`4IZ268-2018-2019-ZS`**.
5. **Přesuň se** do tohoto adresáře, 
    - tj. spustíš příkaz **`cd 4IZ268-2018-2019-ZS`**.
6. Vytvořiš si **vlastní branch**, 
    - tj. spustíš příkaz **`git checkout -b student-{xname}`** (nahraď **`{xname}`** svým **xname**).
7. Publikuješ tuto **branch** a přitom ji nastavíš jako **upstream** u sebe, 
    - tj. spustíš příkaz **`git push --set-upstream student-{xname}`** (nahraď **`{xname}`** svým **xname**).
8. Vytvoříš si svou složku ve složce **`www`**, kterou nazveš svým **xname**, 
    - např. **`C:\Users\User\Projects\4IZ268-2018-2019-ZS\www\nguv03\`**.
9. Sem vložíš své **HTML** soubory a jsi připraven.



### Vývojové prostředí a GIT
Pokud sis zvolil nějaké slušné **vývojové prostředí**, např. [VS Code](https://code.visualstudio.com/download), udělal jsi dobře! **IDE** ti totiž bude ukazovat změny v kódu a také se postará o příkazy na dva kliky.



### Standardní proces schválení změn v kódu pomocí příkazů
1. Uděláš nějaké změny v kódu a chceš to uložit na GIT, tak spustíš CMD ve složce tvého projektu.
2. Podíváš se na vyznačené změny, 
    - tj. spustíš příkaz **`git diff`**. Z toho odejdeš pomocí klávesy **`Q`**.
3. Přidáš tyto změny do **fáze** (stage), 
    - tj. spustíš příkaz **`git add -A`**.
4. Potvrdíš tyto změny, 
    - tj. spustíš příkaz **`git commit -m "MESSAGE"`**. Tady místo **`MESSAGE`** napíšeš krátký popis těch změn nebo jejich účel.
5. Publikuješ tyto změny, 
    - tj. spustíš příkaz **`git push`**. Zadáš heslo a tvůj kód je v cloudu na tvém **branch**i.
6. Pokud chceš publikovat změny na produkci (Pull Request), pokračuj dál, jinak můžeš tady skončit.
7. Teď mě požádáš o schválení tvých změn na produkci, 
    - tj. jdeš na GitHub repozitář pro tento projekt, najdeš si svůj **branch** a uděláš **Pull Request**.
8. Já se na to podívám a schválím, 
    - tj. já udělám **review** a **merge** tvého **branch**e na **master branch** a do minuty se to projeví na webu.
9. Zkontroluješ si svůj nový web a budeš šťastný. (Odkaz na svůj web ti sdělím na cvičení)

