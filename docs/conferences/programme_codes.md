# Programkódok

A programkódok egy módszert jelentenek bizonyos elemek (ülések, üléscsoportok, hozzájárulások és alhozzájárulások) megjelölésére, hogy azokat könnyebben lehessen hivatkozni az Indicón kívül.
Ezek a kódok manuálisan állíthatók be minden elemen, vagy automatikusan generálhatók előre konfigurált sorozatok alapján, amelyek a _Programkódok_ fülön állíthatók be az _Haladó beállítások_ részben a sablonok szerkesztésével.

![](../assets/conference_program_codes.png)

Minden elemhez egy kód tartozhat.
Az egyes elemek kódját manuálisan lehet beállítani szerkesztéskor - például a hozzájárulások esetében, amikor megnyitod a szerkesztési párbeszédablakot, van egy _Programkód_ mező az _Haladó_ szakaszban.

![](../assets/conference_program_codes_manual.png)

A meglévő elemekhez automatikusan kódok hozzárendeléséhez be kell állítanod egy sablont a Programkódok fülön a haladó beállításokban, majd meg kell nyomnod a sablon melletti nyilat.
Például az ülésekhez beállíthatsz egy `S{id}` sablont, és a generált üléskódok `S1`,`S2`,...,`Sn` lesznek, a létrehozás sorrendjében. A hozzájárulásokhoz beállíthatsz valamit, mint `C_{év}{hónap}{nap}_{id}`, és a generált kódok valami ilyesmi lehetnek: `C_20220601_1`, `C_20220602_2`, ...

![](../assets/conference_program_codes_assign.png)

A programkódok hasznosak a párhuzamos ülések és üléscsoportok időrendi táblázatban való rendezéséhez, valamint szűrési kritériumként a szerkeszthetők listáján.

![](../assets/conference_program_codes_filter.png)
