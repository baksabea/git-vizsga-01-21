$ git init -  lokális repository létrehozva, a mappa inicializálása megtörtént.
$ git clone - a repository klónozása/másolása, saját gépre és saját mappába.
$ git status - git repository statuszának ellenőrzése. Verziókezelésben résztvevő fájlok, mappának megtekintése.
$ git add - README.md fájl hozzáadása a gyűjteményhez.
$ git commit -m "" - README.md fájl tartalmának, és az erre vonatkozó üzenet szövegének rögzítése. 
$ git branch console - console nevű ág létrehozása.
$ git checkout console - váltás a console ágra.
$ git add . - az app.js módosítás hozzáadása a gyűjteményhez, ebben az esetben az összes fájl hozzáadása a gyűjteményhez.
$ git commit -m "" - az app.js fájl módosításának rögzítése
$ git add . - style.css módosításának hozzáadása a gyűjteményhez.
$ git commit -m "" - style.css módosítások eltárolása, rögzítése egy verzióban, a módosításra vonatkozó üzenettel.
$ git status - státusz ellenőrzés, az utoljára létrehozott változásokról.
$ git log - előzmények mutatása, megmutatja a commitok listáját.
$ git checkout main - váltás a main ágra.
$ git branch - megmutatja az ágakat, ellenőrzés céljából mégegyszer megnéztem.
$ git status - mégegy ellenőrzés.
$ git remote add origin projectlink - távoli gyűjtemény megadása.
$ git push -u origin main - push-sal feltöltöm a munkámat ( a fő ágamat) a távoli repositoryba, az az a Githubra.
$ git push console - feltöltöm a console branchet is a távoli repositoryba.