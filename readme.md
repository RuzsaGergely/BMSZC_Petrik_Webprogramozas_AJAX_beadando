# AJAX beadandó - webprog

Készíts CRUD vite projektet.
- Projekt neve: sajatnev-ajax-crud formában legyen megadva.
- Beadandó: github repo, aminek a neve egyezzen meg a projekt nevével.
- A projekt backendje legyen interneten keresztül elérhető.
    - A backend alkalmazás is legyen képes CRUD végrehajtására.
    - Használhatod az órákon is használt retool api generatort: https://retool.com/api-generator . 
    - A backend alkalmazás más adatokat adjon vissza, mint az órai projektben (legalább 3 olyan adat szerepeljen, amit órán nem használtunk). 
    - Az alkalmazásban különböző adattípusok legyenek (szöveg, szám, logikai, stb.).

Az alkalmazás legyen képes:
- Adatok listázása:
    - táblázat vagy kártyák segítségével. 
    - Az oldal betöltődésekor, illetve minden művelet végrehajtása után a teljes táblázat tartalma frissüljön.
- Új adat felvételére: 
    - A listázó komponens felett helyezz el egy űrlapot hozzá
    - Az űrlapon ügyelj az beviteli mezők típusára
    - Legalább 3 beviteli mező típust használj
    - Minden beviteli mezőhöz tartozzon label is
    - Az űrlapon legyen Felvétel és Mégse gomb
    - Sikeres felvétel után is álljon az űrlap alaphelyzetbe
    - Mégse gombra kattintva is álljon alaphelyzetbe az űrlap
- Adat módosítására
    - Megjelenítésre szolgáló komponens végén helyezz el egy gombot a módosítás megkezdéséhez
    - A gombra kattintva a felvételi űrlapba töltsd be az adatokat. A Felvétel gomb helyett egy Módosítás gomb jelenjen meg.
    - Sikeres módosítás esetén vagy a mégse gombra kattintva az űrlap álljon vissza alaphelyzetbe. Az űrlapon a módosítás gomb helyett ismét a felvétel gomb jelenjen meg.
- Adat törlésére
    - A megjelenítésre szolgáló komponens utolsó elemeként helyezz el egy törlés gombot.
    - Gombra kattintva töröld az adatot

Minden művelet a backend alkalmazás megfelelő végpontjait meghívva történjen. Végpontok meghívásához az alábbiak egyikét használd:

- fetch (javasolt)
- axios
- jquery ajax
- XMLHttpRequest

A teljes oldalt formázd bootstrap segítségével. Megfelelő stílusosztályok alkalmazásával formázd:

- Az űrlapelemeket
- Ügyelj rá, hogy checkbox / radio button esetében más stílusosztály kell mind az - űrlap elemhez, mind a hozzá tartozó felirathoz.
- A gombokat
- Felvétel / Módosítás / Törlés gomb külön színnel (törlés gombra javasolt piros vagy szürke szín)
- A megjelenítésre szolgáló komponenst
- Táblázat esetén legalább felváltott sorszín legyen
- Kártyák esetén, nagy kijelzőn legalább 2 kártya legyen egymás mellett.