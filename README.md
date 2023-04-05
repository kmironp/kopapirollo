#rockpaperscissorsgame

A kő-papír-olló játék programja, amelyet az előbb írtunk, egy olyan webalkalmazás, amely futtatható bármely modern webböngészőben, és nem függ az operációs rendszertől. Tehát a program ugyanúgy működik Linuxon, Windows-on, macOS-en vagy bármilyen más operációs rendszeren, amely támogatja a webböngészőket. A webalkalmazás HTML, CSS és JavaScript nyelveket használ, amelyeket a böngészők támogatnak és értelmeznek.
---
CSS rész
Ez a CSS kód a játék kinézetét kezeli. A body rész a betűtípust és az elrendezést állítja be, az h1 a címet formázza, a button a gombok stílusát állítja be, beleértve a betűméretet, a margót, a színét és az árnyékát. A #result a játék eredményének stílusát állítja be, beleértve a betűméretet, a vastagságot és a margót, valamint az eredmény színét állítja be az osztályok win, lose és tie szerint.
---
HTML rész
Az HTML kód tartalmazza az alapvető szerkezetet, beleértve a címet, a CSS fájl hivatkozását, a címet és az oldal tartalmát. A h1 a címet tartalmazza, a gombok (button) lehetővé teszik a játékos választását, az eredmény (result) pedig megjeleníti a játék eredményét. Az app.js szkript fájl hivatkozása a JavaScript kódot tartalmazó fájlra utal.
---
JavaScript része
Ez a JavaScript kód kezeli a gombok kattintását, véletlenszerűen választja ki a számítógép választását, és ellenőrzi a felhasználó és a számítógép választását, majd megjeleníti az eredményt a result elemen keresztül.

Az alábbi linken kipróbálható: http://kmironp.rockpaperscissors.nhely.hu/
