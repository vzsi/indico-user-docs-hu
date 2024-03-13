# Program kódok

A programkódok bizonyos elemek (ülések, ülésblokkok, hozzájárulások és al-hozzájárulások) megjelölésére szolgálnak, hogy az Indicón kívül könnyebben lehessen rájuk hivatkozni.
Ezeket a kódokat vagy manuálisan lehet beállítani minden egyes tételen, vagy automatikusan generálhatók előre beállított szekvenciák alapján, amelyeket a _Advanced options_ (Speciális beállítások) lap _Programkódok_ fülén lehet megadni a sablonok szerkesztésével.

![](../assets/conference_program_codes.png)

Minden elemhez egy kód tartozhat.
Az egyes tételek kódja manuálisan is beállítható a szerkesztés során - például a hozzájárulások esetében a szerkesztési párbeszédpanel megnyitásakor a _Advanced_ részben található egy _Programkód_ mező.

![](../assets/conference_program_codes_manual.png)

Ahhoz, hogy a kódokat automatikusan hozzárendelje a meglévő tételekhez, be kell állítania egy sablont a Programkódok lapon a Speciális beállítások között, majd a sablon mellett lévő nyílra kell kattintania.
Például az ülések esetében beállíthatja a `S{id}` sablont, és a generált ülések kódjai a létrehozás sorrendjében az `S1`,`S2`,...,`Sn` lesznek. Hozzájárulások esetén beállíthat valami olyasmit, mint a `C_{év}{hónap}{nap}_{id}`, és a generált kódok a következők lesznek: `C_20220601_1`, `C_20220602_2`, ...

![](../assets/conference_program_codes_assign.png)

A programkódok hasznosak a párhuzamos ülések és ülésblokkok rendezéséhez is az órarendben, valamint szűrési kritériumként a szerkeszthetők listáján.

![](../assets/conference_program_codes_filter.png)
