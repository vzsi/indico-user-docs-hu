Ezen az oldalon megmutatjuk, hogyan hozhatunk létre időrendet egy konferenciához. Az oldal minden elérhető időrendi funkciót és beállítást lefed. Ha inkább egy megbeszélés időrendjét készíted, először érdemes lehet megnézned [ezt az oldalt](../meetings/timetable.md), amely a legalapvetőbb dolgokat fedez le.

Bár a magyarázat nagy része konferenciákra összpontosít, a bemutatottak nagy része megbeszélésekre is alkalmazható. Ahol a viselkedés eltér, ott külön jelezzük.

### Egy időrend anatómiája

Függetlenül attól, hogy egy megbeszélést vagy egy konferenciát szervezel, egy időrend négy alapvető elemet tartalmaz:

- Ülésszakok
- Ülésszak blokkok
- Hozzájárulások
- Szünetek

Az ülésszakok kapcsolódó hozzájárulásokat (előadások/prezentációk) csoportosítanak össze. Ezeket a hozzájárulásokat ülésszak blokkokba szervezzük. Egy ülésszak blokk egy ülésszak "példánya" meghatározott kezdési és befejezési idővel. Például egy ülésszakot fel lehet osztani egy délelőtti és egy délutáni blokkra. Fontos megjegyezni, hogy az ülésszakokat közvetlenül nem lehet időrendbe ütemezni, csak az ülésszak blokkokat. Az ülésszakokról részletesebb magyarázatot [itt](./sessions.md) találsz.

A szünetek célja, hogy jelezzék a programban egy szünetet, mint például egy ebédszünet vagy egy kávészünet.

Egy megbeszélés időrendjének példája így nézhet ki:

![](../assets/meetings/timetable/finished_timetable.png)

Ez az időrend csak hozzájárulásokat használ. Sok megbeszélés viszonylag egyszerű és nem igényli a szünetek vagy ülésszak blokkok használatát, amelyeket általában konferenciákon használnak, mindazonáltal mégis lehetőség van ezek használatára.

Egy konferencia időrendjének példája így nézhet ki:

![](../assets/conferences/timetable/finished_timetable.png)

Részletes nézet használatával:

![](../assets/conferences/timetable/finished_timetable_detailed.png)

Ebben az időrendben van egy felső szintű hozzájárulás (Üdvözlő beszéd) és két ülésszak (Előadások & Műhelymunkák). Az _Előadások_ ülésszaknak két ütemezett ülésszak blokkja van, délelőtt és délután, mindegyik blokkban több hozzájárulással. Van egy szünet is a két blokk között. A Műhelymunkák ülésszaknak csak egy ütemezett ülésszak blokkja van, több hozzájárulással benne.

Annak ellenére, hogy az eseménynek két ülésszaka van, az időrend csak ülésszak blokkokat tartalmaz, mivel az ülésszakokat közvetlenül nem lehet ütemezni. Még ha egy ülésszaknak, mint a _Műhelymunkák_ ülésszaknak a példában, csak egy ülésszak blokkja van, akkor is létre kell hozni egy ülésszak blokkot.

A hozzájárulások mellett léteznek alcímek is, amelyek egy hozzájáruláson belül hozhatók létre. Azonban ezek egyszerűen csak a szülő hozzájárulás részei és nem ütemezhetők külön az időrendben.

### Időrend készítése

Ebben a szekcióban megmutatjuk, hogyan hozhatunk létre egy esemény időrendjét ülésszak blokkok, hozzájárulások és szünetek használatával.

Megjegyzendő, hogy a hozzájárulások viselkedése megbeszéléseknél és konferenciáknál kissé eltérő. Egy megbeszélésnél egy hozzájárulás egy bejegyzés az időrendben, amely egy beszélgetést vagy tárgyalási pontot képvisel, és az időrenden kívül nincs más célja. Konferenciáknál a hozzájárulások sokkal sokoldalúbbak, és az időrenden kívül használják őket az [Absztraktok felhívásához](./cfa.md), a [Korrektúrázás](./papers/introduction.md) és a [Szerkesztés](./papers/introduction.md) modulokban is.

#### Hozzájárulások

Kezdjük a legegyszerűbb esettel, amely a hozzájárulások ütemezése az időrendben ülésszak blokkok használata nélkül.

Hozzájárulás ütemezéséhez először navigálj az _Időrend_-hez az eseményed kezelőterületén. Ez megnyitja az időrend felső szintű nézetét. Ha az eseményed több napig tart, a tetején több fül látható, mindegyik egy-egy napot képvisel az időrendben. Ezek között váltogatva megtekintheted az adott nap programját.

![](../assets/conferences/timetable/timetable_days.png)

Az itt látható napok az eseményed kezdési és befejezési dátumától függnek.

Hozzájárulás hozzáadásához válaszd ki a napot, és kattints a jobb felső sarokban található _Új hozzáadása_-ra, majd a legördülő menüből válaszd a _Hozzájárulás_-t.

![](../assets/conferences/timetable/add_contrib.png)

A rendelkezésre álló hozzájárulások listájából válaszd ki azokat, amelyeket ütemezni szeretnél. Lehetőség van több hozzájárulás egyszerre történő kiválasztására is, amelyeket egymás után fognak ütemezni. A kiválasztás megerősítéséhez kattints az _Kiválasztottak hozzáadása_-ra.

![](../assets/conferences/timetable/add_contrib_select.png)

Ha nem találod a listában azt a hozzájárulást, amelyet ütemezni szeretnél, győződj meg róla, hogy a hozzájárulás nincs egy ülésszakhoz rendelve. Ha egy hozzájárulás egy ülésszakhoz van rendelve, akkor csak azon belül ütemezhető. Csak azok a hozzájárulások ütemezhetők a felső szinten, amelyek nincsenek ülésszakhoz rendelve. Annak ellenőrzéséhez, hogy a hozzájárulásod rendelkezik-e ülésszak hozzárendeléssel, menjen a _Hozzájárulások oldalára_, és győződjön meg arról, hogy az _Ülésszak_ oszlopban _Nincs ülésszak_ állapotot mutat.

![](../assets/conferences/timetable/no_session.png)

Az időrend lehetővé teszi egy hozzájárulás létrehozását és ütemezését is egyidejűleg. Ehhez ismét kattints az _Új hozzáadása_-ra, és válaszd a _Hozzájárulás_-t a legördülő menüből. Ezután kattints a párbeszédablak tetején található _Új létrehozása_-ra.

![](../assets/conferences/timetable/create_contrib.png)

Egy új párbeszédablak nyílik meg, ahol legalább a címet, a kezdési időt és a hozzájárulás időtartamát kell megadnod. A _Személyek_ mezőben hozzáadhatod az előadókat, szerzőket és társszerzőket. Ha előadókat adsz hozzá, akkor azok megjelennek a hozzájárulás alatt az időrendben. Ha egy megbeszélés időrendjét hozod létre, itt csak az előadók érhetők el.

![](../assets/conferences/timetable/create_contrib_dialog.png)

Amikor befejezted, kattints a _Mentés_-re, és a hozzájárulás automatikusan be lesz ütemezve az általad választott időpontra.

!!! note
    Ha nincsenek ütemezhető hozzájárulásaid, vagy egy megbeszélés időrendjét hozod létre, az új hozzájárulás létrehozásának űrlapja közvetlenül megnyílik az _Új hozzáadása_ -> _Hozzájárulás_ kiválasztása után.

Ha meg szeretnéd változtatni egy hozzájárulás kezdési idejét, egyszerűen húzd feljebb vagy lejjebb az időrendben. Alternatívaként használhatod a fel és le gombokat is, amelyek akkor válnak láthatóvá, amikor az egérmutatót egy elem fölé viszed az időrendben:

![](../assets/conferences/timetable/move_up_down.png)

A hozzájárulás időtartamának megváltoztatásához kattints és húzd a hozzájárulás alját.

Az időrendben egy hozzájárulásra kattintva egy ablak jelenik meg, amely néhány alapvető információt mutat róla, és lehetővé teszi a beállításainak kezelését. Az indulási időt és az időtartamot is beállíthatod úgy, hogy a hozzájárulásra kattintasz, majd az időre:

![](../assets/conferences/timetable/adjust_start_duration.png)

Gyorsan szerkesztheted a hozzájárulás beállításait és védelmét is:

![](../assets/conferences/timetable/quick_edit.png)

Ha egy hozzájárulást másik napra szeretnél áthelyezni, kattints a két nyíl ikonra (_Hozzájárulás áthelyezése_):

![](../assets/conferences/timetable/move.png)

Az új párbeszédablakban kiválaszthatod a hozzájárulás számára egy másik napot. Ha az időrended már tartalmaz ülésszak blokkokat, akkor a hozzájárulást áthelyezheted az egyikbe is. Ez a művelet automatikusan hozzárendeli a hozzájárulást az ülésszakhoz.

![](../assets/conferences/timetable/move_dialog.png)

Ha egyszerűen csak egy hozzájárulást szeretnél egy ülésszak blokkba helyezni a felső szinten, akkor húzd át a hozzájárulást az ülésszak blokk fölé, ami automatikusan azon belül helyezi el.

Fontos megjegyezni, hogy a megbeszélések és a konferenciák között van különbség, amikor egy hozzájárulást eltávolítanak az időrendből. Egy konferenciánál egy hozzájárulás biztonságosan ütemezhető ki úgy, hogy az adatai érintetlenek maradnak. Egy megbeszélésnél, amikor egy hozzájárulást eltávolítanak az időrendből, az törlődik.

Egy hozzájárulás eltávolításához az időrendből kattints a kukára (_Hozzájárulás ütemezésének megszüntetése_ konferenciáknál vagy _Hozzájárulás törlése_ megbeszéléseknél) és erősítsd meg az _OK_-val.

![](../assets/conferences/timetable/unschedule.png)

#### Ülésszak blokkok

Egy ülésszak blokk egy ülésszak egy adott részét vagy egy példányát képviseli meghatározott kezdési és befejezési idővel. Egy ülésszaknak egy vagy több ülésszak blokkja lehet. Ez lehetővé teszi egy ülésszak több részre való felosztását, ha szükséges. Például egy ülésszaknak lehet egy délelőtti és egy délutáni része. Másik példa, egy több napos ülésszaknak lehet egy-egy ülésszak blokkja minden napon.

Ami az ülésszak blokkokat és a hozzájárulásokat különbözteti meg, az az, hogy az ülésszak blokkoknak saját időrendjük van. Ez lehetővé teszi, hogy a hozzájárulásokat és a szüneteket nem csak a felső szinten, hanem az ülésszak blokkokon belül is ütemezni lehessen.

Új ülésszak blokk hozzáadásához kattints az _Új hozzáadása_-ra és válaszd az _Ülésszak blokk_-ot a legördülő menüből.

![](../assets/conferences/timetable/session_block.png)

Az _Hozzáadás egy másikhoz_ alatt kiválaszthatod a szülő ülésszakot. Az _Új ülésszak létrehozása_ kiválasztásával először egy teljesen új ülésszakot hozhatsz létre, majd azon belül egy új ülésszak blokkot. Az ülésszakokat az _Ülésszakok_ fülön is létrehozhatod - részletekért lásd [itt](./sessions.md).

Az ülésszak kiválasztása után megnyílik egy ülésszak blokk párbeszédablak. Töltsd ki a kezdési időt és az időtartamot, és opcionálisan a többi mezőt is. Az ülésszak blokk címe opcionális. Ha üresen hagyod, az ülésszak blokk csak az ülésszak címét jeleníti meg. A _Helyszín_ mezőben kiválaszthatsz egy helyszínt a [Helyfoglalási modulból](../room_booking/about.md), ha alkalmazható.

Végül hozzáadhatsz _Konveneroket_ az ülésszak blokkhoz. Ezek különböznek az ülésszak koordinátoroktól, ahogy [itt](./sessions.md) magyaráztuk. Az ülésszak konveneroknek nincsenek extra jogai, hasonlóan a hozzájárulás előadóihoz. Az ülésszak konvenerok az ülésszak blokk jobb felső sarkában jelennek meg.

![](../assets/conferences/timetable/block_dialog.png)

Miután minden adatot kitöltöttél, kattints a _Mentés_-re az ülésszak blokk létrehozásához és ütemezéséhez. A későbbiekben az adatok szerkesztéséhez egyszerűen kattints az ülésszak blokkra az időrendben, majd kattints a ceruza ikonra az ülésszak blokk szekcióban.

![](../assets/conferences/timetable/block_edit.png)

Hasonlóan a hozzájárulásokhoz, kattintással és húzással az ülésszak blokkot feljebb vagy lejjebb mozgathatod a kezdési idő megváltoztatásához. Az időtartamot a blokk alsó szélét kattintva és húzva állíthatod be. A kezdési időt és az időtartamot is beállíthatod úgy, hogy a blokkra kattintasz, majd az időre:

![](../assets/conferences/timetable/block_change_time.png)

Az ülésszak beállításait és védelmét is közvetlenül az időrendből kezelheted, ha egy ülésszak blokkra kattintasz:

![](../assets/conferences/timetable/block_edit_session.png)

!!! note
    Egy ülésszak blokk nem tarthat több napig. Ha az ülésszak több napon át tart, akkor minden napra hozz létre egy-egy ülésszak blokkot.

Az ülésszak blokkok alapértelmezés szerint üresek. Ahhoz, hogy egy hozzájárulást vagy szünetet ütemezz egy ülésszak blokkban, először navigálj az adott ülésszak blokk időrendjéhez. Ezt úgy teheted meg, hogy a blokkra kattintasz, majd kiválasztod a _Menj az ülésszak blokk időrendjéhez_ opciót.

![](../assets/conferences/timetable/block_timetable.png)

Ez egy új oldalt nyit meg, amely megjeleníti az ülésszak blokk időrendjét. A jelenleg megtekintett blokk neve a jobb felső sarokban jelenik meg. Mindig visszatérhetsz a teljes időrendhez a _Vissza az időrendhez_ gombra kattintva.

![](../assets/conferences/timetable/up_to_timetable.png)

Egy ülésszak blokkban hozzájárulást vagy szünetet ütemezhetsz. A szünetekről a következő szekcióban lesz szó. Új hozzájárulás hozzáadásához kattints az _Új hozzáadása_-ra, és válaszd a _Hozzájárulás_ lehetőséget. Figyelembe véve, hogy csak azokat a hozzájárulásokat ütemezheted, amelyek ugyanahhoz az ülésszakhoz vannak rendelve, mint az ülésszak blokk, amelyben éppen vagy. Ha egy másik ülésszakhoz tartozó hozzájárulást szeretnél ütemezni, először menj a _Hozzájárulások_ oldalra, és keresd meg a kérdéses hozzájárulást. Ezután változtasd meg a _Hozzájárulás_ ülésszakát arra, amelyik az ülésszak blokkéval megegyezik.

![](../assets/conferences/timetable/change_session.png)

Egy ülésszak blokkban hozzájárulás ütemezésének eljárása megegyezik a felső szinten történő hozzájárulás hozzáadásával, ahogy a [korábbi szekcióban](#contributions) elmagyaráztuk. A szünetek hozzáadását a [következő szekcióban](#breaks) ismertetjük.

Egy ülésszak blokkot nem lehet másik napra áthelyezni, sem egy másik ülésszak blokkba beágyazni. Ha egy ülésszak blokkot másik napra szeretnél áthelyezni, az egyetlen módja annak, hogy töröld az egyik napon, és újra létrehozd egy másikon. Ne feledd, hogy egy ülésszak blokk törlése automatikusan ütemezés nélkül hagyja (konferenciáknál) vagy törli (megbeszéléseknél) az összes benne lévő hozzájárulást. Ezenkívül törli az összes benne lévő szünetet is.

Egy ülésszak blokk törléséhez kattints egy ülésszak blokkra, majd kattints a kukára:

![](../assets/conferences/timetable/block_delete.png)

##### Poszter ülésszakok

A poszter ülésszakok esetében az ütemezés eltérően működik (további részletek a poszter ülésszakok létrehozásáról [itt](./sessions.md)). Ha egy ülésszak blokk poszter ülésszakhoz tartozik, a blokkban lévő hozzájárulásokat poszterként kezelik, és automatikusan párhuzamosan ütemezik, ugyanazzal a kezdési és befejezési idővel, mint a szülő ülésszak blokk. Ezenkívül nem lehet szünetet hozzáadni egy poszter ülésszakhoz.

Egy hozzájárulás ütemezéséhez egy poszter ülésszak blokkban kattints a jobb felső sarokban található _Poszter hozzáadása_-ra, és válaszd ki az ütemezni kívánt hozzájárulásokat:

![](../assets/conferences/timetable/add_poster.png)

Vegye figyelembe, hogy az időrend különbözően néz ki - az egyes hozzájárulások kezdési és befejezési ideje helyett egyszerűen egy listát jelenít meg.

#### Szünetek

A szünetek olyan szüneteket jelölnek a programban, mint például egy ebédszünet. Egy szünetet vagy a felső szinten az időrendben, vagy egy ülésszak blokkon belül lehet ütemezni. Egy felső szintű szünet hozzáadásához kattints az _Új hozzáadása_-ra, és válaszd a _Szünet_ lehetőséget:

![](../assets/conferences/timetable/break.png)

Töltsd ki a címet, a kezdési és befejezési időt, és opcionálisan a leírást, helyszínt és színt. A _Mentés_ gombra kattintva ütemezd be a szünetet.

![](../assets/conferences/timetable/add_break.png)

Ezeket az adatokat később is szerkesztheted, ha a szünetre kattintasz, ami egy párbeszédablakot nyit meg.

![](../assets/conferences/timetable/edit_break.png)

A kezdési idő megváltoztatásához, a szünetet feljebb vagy lejjebb húzhatod, hasonlóan a hozzájárulásokhoz és az ülésszak blokkokhoz. Az időtartamot a szünet alsó szélét húzva állíthatod be. A szüneteket más napokra vagy ülésszak blokkokba is áthelyezheted, vagy kattinthatsz a _Mozgatás_ ikonra, vagy egyszerűen áthúzhatod a szünetet egy ülésszak blokk fölé.

A szünet törléséhez kattints a kukára, majd erősítsd meg az _OK_-val.

Egy szünet létrehozásához egy ülésszak blokkon belül először nyisd meg az ülésszak blokk időrendjét az ülésszak blokkra kattintva, majd válaszd a _Menj az ülésszak blokk időrendjéhez_ opciót.

![](../assets/conferences/timetable/block_timetable.png)

Ezután követheted a felső szintű szünet leírásában említett lépéseket.

#### Újraütemezés

Ha szükséges egy adott nap vagy ülésszak blokk összes bejegyzésének kezdési idejét vagy időtartamát módosítani, használhatod az _Újraütemezés_ funkciót. Ez automatikusan módosítja az összes bejegyzést, ahelyett, hogy egyenként kellene őket módosítani.

Az újraütemezés megkezdéséhez válaszd ki a teljes időrendet vagy egy ülésszak blokk időrendjét, és kattints az _Újraütemezés_ gombra a jobb felső sarokban.

![](../assets/conferences/timetable/reschedule.png)
![](../assets/conferences/timetable/reschedule_dialog.png)

Beállíthatod a kezdési időt vagy az időtartamot. Ha a kezdési időt választod, az időrend első bejegyzése úgy lesz áthelyezve, hogy a kezdési ideje megegyezzen az esemény kezdési idejével. Egy ülésszak blokk esetében a bejegyzés úgy lesz áthelyezve, hogy az ülésszak blokk kezdetekor kezdődjön. Az összes többi bejegyzés egymás után lesz 'halmozva', hogy teljesen kitöltse a bejegyzések közötti réseket.

Íme egy példa az ülésszak blokk időrendjére a kezdési idő módosítása előtt:

![](../assets/conferences/timetable/before_reschedule_start_time.png)

És íme a végeredmény. Vegyük észre, hogy a kezdési idő 16:00-ról 15:20-ra (az ülésszak blokk kezdési idejére) lett áthelyezve, és a bejegyzések közötti rések eltávolításra kerültek. A bejegyzések időtartama változatlan maradt.

![](../assets/conferences/timetable/after_reschedule_start_time.png)

A második újraütemezési opció, amely az összes bejegyzés időtartamát módosítja, kitölti az egyes bejegyzések közötti üres rést az időtartamuk kiterjesztésével, de a kezdési időt változatlanul hagyja.
Ha ugyanezt a példát használjuk, és az időtartamokat módosítjuk, akkor ez lesz a végeredmény:

![](../assets/conferences/timetable/after_reschedule_duration.png)

Vegyük észre, hogy az utolsó hozzájárulás időtartama nem változott, mivel ez az utolsó bejegyzés az időrendben, így nincs 'rés' a kitöltésre.

Mindkét fent említett opcióval kapcsolatban megadható egy 'időrés'. Ez minden egyes bejegyzéspár között rést hagy, ahelyett, hogy teljesen kitöltené őket.

![](../assets/conferences/timetable/reschedule_gap.png)

Ha ugyanazt a példát vesszük, és az időrés 10 percre állítjuk, akkor ezt kapjuk:

![](../assets/conferences/timetable/after_reschedule_gap.png)

Minden esemény korábbi időpontra lett áthelyezve, miközben 10 perces rést hagytak közöttük.

#### Tartalomhoz illesztés

Ha egy ülésszak blokk időtartama nagyobb, mint a tartalma teljes időtartama, akkor automatikusan összezsugorítható, hogy pontosan lefedje a bejegyzéseket. Ez magában foglalja a blokk kezdési idejének beállítását az első bejegyzés kezdési idejére, és a blokk befejezési idejének beállítását az utolsó bejegyzés befejezési idejére. Ez a művelet nem mozdítja el az egyes bejegyzéseket az ülésszak blokkon belül.

Az ülésszak blokk tartalomhoz való illesztéséhez kattints a _Tartalomhoz illesztés_ gombra az ülésszak blokk időrendjének jobb felső sarkában:

![](../assets/conferences/timetable/fit_to_content.png)

A tartalomhoz való illesztést minden ülésszak blokk esetében elvégezheted egy adott napon a felső szintű időrend _Újraütemezés_ gombjára kattintva és bejelölve a _Minden ülésszakot a tartalmukhoz igazít_ opciót.

![](../assets/conferences/timetable/fit_to_content_reschedule.png)

!!! note
    A _Tartalomhoz igazítás_ csak akkor szükséges, ha az ülésszak blokkot szeretnéd összezsugorítani. Egy ülésszak blokk automatikusan növekszik, hogy befogadja a tartalmát. Valójában nem lehetséges az ülésszak blokk időtartamát rövidebbre állítani, mint a tartalma időtartama.

### Az időrend nyilvánossá tétele (csak konferenciák esetén)

Alapértelmezés szerint az esemény hozzájárulásai 'Vázlat módban' vannak. Ez azt jelenti, hogy a rendes felhasználók nem láthatják a hozzájárulások listáját, az időrendet, az absztraktok könyvét és a szerzők valamint előadók listáját. A vázlat mód létezik annak megakadályozására, hogy a résztvevők lássák az időrendet, amíg az készül.

Amikor nyilvánossá szeretnéd tenni az időrendet, kikapcsolhatod a vázlat módot. Ezt úgy teheted meg, hogy a _Hozzájárulások_ oldalra navigálsz, és a jobb felső sarokban átkapcsolod a _Vázlat_ gombot.

![](../assets/conferences/timetable/draft.png)

Ugyanezt megteheted a _Beállítások_ vagy az _Időrend_ oldalról is, a figyelmeztetésen belül a _Hozzájárulások közzététele_ gombra kattintva.

![](../assets/conferences/timetable/draft_warning.png)





