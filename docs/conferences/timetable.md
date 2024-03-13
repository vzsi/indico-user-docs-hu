Ezen az oldalon megmutatjuk, hogyan hozhat létre egy konferencia menetrendjét. Ez az oldal az összes elérhető menetrendfunkciót és beállítást tartalmazza. Ha ehelyett egy értekezlet menetrendjét hozza létre, akkor érdemes először [ezt az oldalt](../meetings/timetable.md) megnéznie, amely az alapokat tárgyalja.

Bár a magyarázat középpontjában a konferenciák állnak, a bemutatottak nagy része alkalmazható a megbeszélésekre is. Rámutatunk arra a néhány helyre, ahol a viselkedés eltér.

### Egy menetrend anatómiája

Függetlenül attól, hogy értekezletet vagy konferenciát szervez, az ütemterv négy alapvető elemből áll:

- Ülések
- Ülésblokkok
- Hozzájárulások
- Szünetek

Az ülések egymáshoz kapcsolódó hozzászólásokat (előadásokat/prezentációkat) csoportosítanak. Ezek a hozzászólások szekcióblokkokba vannak szervezve. Egy ülésblokk egy ülés "példánya", meghatározott kezdéssel és befejezéssel. Egy ülésszak például délelőtti és délutáni blokkokra osztható. Megjegyzendő, hogy az üléseket nem lehet közvetlenül ütemezni az órarendben, csak az ülésblokkokat lehet. A munkamenetek alaposabb magyarázata [itt](./sessions.md) található.

A szünetekkel a programban való szünetet, például ebéd- vagy kávészünetet lehet jelezni.

Egy példa egy ülés menetrendjére így nézhet ki:

![](../assets/meetings/timetable/finished_timetable.png)

Ez az ütemterv csak a hozzászólásokat használja. Sok értekezlet viszonylag egyszerű, és nem igényel szüneteket vagy ülésblokkokat, amelyeket általában a konferenciákon használnak, de ettől függetlenül mégis lehet használni őket.

Egy példa a konferencia menetrendjére a következőképpen nézhet ki:

![](../assets/conferences/timetable/finished_timetable.png)

A részletes nézet használata:

![](../assets/conferences/timetable/finished_timetable_detailed.png)

Ebben az ütemtervben egy legfelső szintű hozzászólás (Üdvözlő beszéd) és két szekció (Előadások és műhelyek) található. Az _Talks_ ülésszak két ütemezett ülésblokkot tartalmaz, délelőtt és délután, mindkét blokkban több hozzászólással. A két blokk között szünet is van. A Workshopok ülésszaknak csak egy tervezett ülésblokkja van, amelyben több hozzászólás is szerepel.

Vegye figyelembe, hogy annak ellenére, hogy a rendezvénynek két ülése van, az ütemterv csak ülések blokkjait tartalmazza, mivel az ülések nem ütemezhetők közvetlenül. Még ha egy ülésnek csak egy ülésblokkja van is, mint a fenti példában a _Workshops_ ülésnek, akkor is létre kell hozni egy ülésblokkot.

A hozzájárulásokon kívül léteznek al-hozzájárulások is, amelyek egy hozzájáruláson belül hozhatók létre. Ezek azonban egyszerűen a szülői hozzájárulás részét képezik, és nem ütemezhetők külön-külön az órarendben. 

### Órarend létrehozása

Ebben a szakaszban bemutatjuk, hogyan hozhatunk létre egy eseménymenetrendet az ülésblokkok, hozzájárulások és szünetek felhasználásával.

Vegye figyelembe, hogy a hozzájárulások kissé másképp viselkednek az üléseken és a konferenciákon. Egy értekezleten a hozzászólás egy előadást vagy vitapontot jelképező bejegyzés az ütemtervben, és nincs más célja az ütemterven kívül. Konferenciákon a hozzászólások sokkal sokoldalúbbak, és a menetrend mellett a [Call for abstracts](./cfa.md) és a [Peer reviewing](./papers/introduction.md) és a [Editing](./papers/introduction.md) modulok is használják őket.

#### Hozzájárulások

A legegyszerűbb esettel kezdjük, amely a hozzájárulások hozzáadása az órarendhez, ülésblokkok használata nélkül.

Hozzájárulás ütemezéséhez először navigáljon az esemény kezelési területén a _Ortajánló_ menüpontra. Ez megnyitja az órarend legfelső szintű nézetét. Ha az eseménye többnapos, akkor a tetején több lapot lát, amelyek mindegyike az órarend egy-egy napját jelöli. Ha ezek között váltogat, akkor az adott nap programját láthatja.

![](../assets/conferences/timetable/timetable_days.png)

Az itt látható napok az esemény kezdő és befejező dátumától függnek.

Hozzájárulás hozzáadásához válasszon ki egy napot, és kattintson az ütemterv jobb felső sarkában található _Add new_ gombra, majd válassza ki a legördülő menüből a _Contribution_ lehetőséget.

![](../assets/conferences/timetable/add_contrib.png)

A rendelkezésre álló hozzájárulások listájából válassza ki a beütemezni kívánt hozzájárulásokat. Lehetőség van több hozzászólás kiválasztására is, amelyek egymás után lesznek ütemezve. Erősítse meg a kiválasztást a _Add selected_ gombra kattintva.

![](../assets/conferences/timetable/add_contrib_select.png)

Ha nem találja a listában a beütemezni kívánt hozzájárulást, győződjön meg róla, hogy a hozzájárulás nincs hozzárendelve egy ülésszakhoz. Ha egy hozzászólás egy munkamenethez van hozzárendelve, akkor csak azon belül ütemezhető. Csak a munkamenethez nem rendelt hozzájárulások ütemezhetők a legfelső szinten. Ha ellenőrizni szeretné, hogy a hozzájárulásához van-e munkamenet hozzárendelve, lépjen a _A hozzájárulások oldalra_, és győződjön meg róla, hogy a _Munkamenet_ oszlopban az áll, hogy _Nincs munkamenet_.

![](../assets/conferences/timetable/no_session.png)

Az ütemterv lehetővé teszi a hozzászólás létrehozását és ütemezését is egyszerre. Ehhez kattintson ismét a _Új_ hozzáadása gombra, és válassza ki a legördülő menüből a _Contribution_ lehetőséget. Ezután kattintson a párbeszédpanel tetején az _Create a new one_ gombra.

![](../assets/conferences/timetable/create_contrib.png)

Megnyílik egy új párbeszédablak, ahol ki kell töltenie legalább a hozzájárulás címét, kezdési időpontját és időtartamát. A _People_ mezőben hozzáadhatja az előadókat, szerzőket és társszerzőket. Ha hozzáteszi az előadókat, akkor azok a hozzászólás alatt fognak megjelenni a menetrendben. Ha ülésmenetrendet hoz létre, akkor itt csak az előadók lesznek elérhetők.

![](../assets/conferences/timetable/create_contrib_dialog.png)

Ha végzett, kattintson a _Save_ gombra, és a hozzászólás automatikusan be lesz ütemezve a kiválasztott időpontra.

!!! Megjegyzés
    Ha nincsenek ütemezhető hozzászólásai, vagy éppen egy megbeszélés ütemtervét hozza létre, akkor a _Új hozzászólás hozzáadása_ -> __hozzájárulás_ gombra kattintás után közvetlenül megnyílik az új hozzászólás létrehozására szolgáló űrlap.

Ha módosítani szeretné egy hozzászólás kezdési időpontját, akkor egyszerűen felfelé vagy lefelé húzza azt az ütemtervben. Alternatívaként használhatja a felfelé és lefelé gombokat is, amelyek akkor válnak láthatóvá, ha az órarend bármely eleme fölé mozgatja a mutatót:

![](../assets/conferences/timetable/move_up_down.png)

Egy hozzászólás időtartamának megváltoztatásához kattintson és húzza a hozzászólás alsó szélét.

Ha az órarendben rákattint egy hozzászólásra, megjelenik egy ablak, amely néhány alapvető információt mutat róla, és lehetővé teszi a beállítások kezelését. A kezdési időpontot és az időtartamot is beállíthatja, ha rákattint a hozzájárulásra, majd az időre kattint:

![](../assets/conferences/timetable/adjust_start_duration.png)

A hozzájárulás beállításait és védelmét is gyorsan szerkesztheti:

![](../assets/conferences/timetable/quick_edit.png)

Ha egy hozzászólást másik napra szeretne áthelyezni, kattintson a két nyíllal ellátott ikonra (_Move contribution_):

![](../assets/conferences/timetable/move.png)

Az új párbeszédablakban kiválaszthatja a hozzájárulás másik napját. Ha az órarend már tartalmaz ülésblokkokat, akkor a hozzájárulást ezek egyikén belül is áthelyezheti. Ez a művelet automatikusan hozzárendeli a hozzájárulást az üléshez.

![](../assets/conferences/timetable/move_dialog.png)

Ha egyszerűen csak egy hozzájárulást szeretne áthelyezni a legfelső szintről egy munkamenetblokkba, akkor a hozzájárulást a munkamenetblokk fölé is húzhatja, ami automatikusan a blokk belsejébe helyezi azt.

Ne feledje, hogy a hozzájárulásoknak az órarendből való eltávolítása tekintetében különbség van az ülések és a konferenciák között. Egy konferencián egy hozzászólás biztonságosan törölhető az ütemtervből, miközben az adatai érintetlenül maradnak. Egy értekezleten, amikor egy hozzászólást eltávolítanak az ütemtervből, az egyben törlődik is.

Ha el szeretne távolítani egy hozzászólást a menetrendből, kattintson a szemetes ikonra (konferenciák esetében a _Tervezett hozzászólás megszüntetése_, értekezletek esetében a _Bejegyzés törlése_), majd erősítse meg a _OK_ gombra kattintva.

![](../assets/conferences/timetable/unschedule.png)

#### Ülésblokkok

Egy munkamenetblokk egy példányt vagy egy munkamenet egy részét jelenti, meghatározott kezdettel és véggel. Egy munkamenetnek egy vagy több munkamenetblokkja lehet. Ez lehetővé teszi, hogy szükség esetén egy munkamenetet több részre osszon fel. Például egy munkamenetnek lehet egy délelőtti és egy délutáni része. Egy másik példa: egy több napon át tartó munkamenetnek minden napra juthat egy munkamenetblokk.

A munkamenetblokkokat az különbözteti meg a hozzájárulásoktól, hogy a munkamenetblokkoknak saját menetrendjük van. Ez lehetővé teszi, hogy a hozzászólásokat és a szüneteket ne csak a legfelső szinten, hanem az ülésblokkokon belül is be lehessen ütemezni.

Új munkamenetblokk hozzáadásához kattintson az _Új hozzáadása_ gombra, és válassza ki a legördülő menüből a _Munkamenetblokk_ lehetőséget.

![](../assets/conferences/timetable/session_block.png)

A _Add another block to_ alatt kiválaszthatja a szülő munkamenetet. Az _Új munkamenet létrehozása_ gombra kattintva először egy teljesen új munkamenetet, majd azon belül egy új munkamenetblokkot hoz létre. A munkameneteket a _Munkamenetek_ fülön is létrehozhatja - további részletek [itt](./sessions.md).

A munkamenet kiválasztása után megnyílik egy munkamenetblokk párbeszédpanel. Töltse ki a kezdési időpontot és időtartamot, valamint opcionálisan a többi mezőt. A munkamenetblokk címe opcionális. Ha üresen hagyja, a munkamenetblokk csak a munkamenet címét fogja megjeleníteni. A _Location_ mezőben adott esetben kiválaszthat egy helyszínt a [Szobafoglalás modul](../room_booking/about.md) modulból.

Végül az ülésblokkhoz hozzáadhatja a __Conveners_ (Összehívók_) mezőt is. Ezek különböznek a munkamenet-koordinátoroktól, amint azt [itt](./sessions.md) elmagyarázzuk. A munkamenet összehívóknak nincsenek extra jogaik, hasonlóan a hozzászólások előadóihoz. A munkamenet összehívói a munkamenet blokkjuk jobb felső sarkában jelennek meg.

![](../assets/conferences/timetable/block_dialog.png)

Miután minden adatot kitöltött, kattintson a _Save_ gombra az ülésblokk létrehozásához és ütemezéséhez. Az adatok későbbi szerkesztéséhez egyszerűen kattintson az ülésblokkra az órarendben, majd kattintson a ceruza ikonra az ülésblokk résznél.

![](../assets/conferences/timetable/block_edit.png)

A hozzájárulásokhoz hasonlóan az ülésblokkra kattintva és azt felfelé vagy lefelé húzva módosíthatja a kezdési időpontot. Az időtartamot az alsó szélére kattintva és azt húzva lehet beállítani. A kezdési időpont és az időtartam a blokkra kattintva, majd az időre kattintva is módosítható:

![](../assets/conferences/timetable/block_change_time.png)

Az ülés beállításait és védelmét közvetlenül az órarendből is lehet kezelni, ha az ülésblokkra kattintunk:

![](../assets/conferences/timetable/block_edit_session.png)

!!! Megjegyzés
    Egy ülésblokk nem terjedhet ki több napra. Ha az ülés több napon át tart, hozzon létre egy ülésblokkot minden napra.

Az ülésblokkok alapértelmezés szerint üresen jönnek létre. Ahhoz, hogy egy ülésblokkban hozzájárulást vagy szünetet tervezzen, először navigáljon az ülésblokk órarendjéhez. Ehhez kattintson az ülésblokkra, és válassza a _Menj az ülésblokk menetrendjéhez_ lehetőséget.

![](../assets/conferences/timetable/block_timetable.png)

Ez megnyit egy új oldalt, amelyen az ülésblokkok menetrendje látható. Az éppen megtekintett blokk neve a jobb felső sarokban jelenik meg. A _Up to timetable_ gombra kattintva bármikor visszatérhet a teljes órarendhez.

![](../assets/conferences/timetable/up_to_timetable.png)

Egy ülésblokkon belül beoszthat egy hozzászólást vagy egy szünetet. A szünetekkel a következő szakaszban foglalkozunk. Új hozzászólás hozzáadásához kattintson az _Add new_ gombra, majd válassza a __Contribution_ lehetőséget. Vegye figyelembe, hogy csak olyan hozzájárulásokat ütemezhet, amelyek ugyanahhoz a munkamenethez vannak rendelve, mint az aktuális munkamenetblokk. Ha olyan hozzájárulást szeretne ütemezni, amely más munkamenethez tartozik, először lépjen a _Contributions_ oldalra, és keresse meg a kérdéses hozzájárulást. Ezután módosítsa a _Session_-t úgy, hogy az megegyezzen annak az ülésblokknak az ülésblokkjával, ahová ütemezni szeretné.

![](../assets/conferences/timetable/change_session.png)

A hozzászólás beütemezésének eljárása egy ülésblokkban ugyanaz, mint a hozzászólás hozzáadása az órarend legfelső szintjének hozzáadásához, ahogyan azt az [előző szakaszban](#contributions) elmagyarázzuk. A szünetek hozzáadásának módját a [következő szakaszban](#szünetek) ismertetjük.

Egy munkamenetblokk nem helyezhető át másik napra, és nem lehet egy munkamenetblokk egy másik munkamenetblokkba ágyazva. Ha egy munkamenetblokkot más napra szeretne áthelyezni, akkor az egyetlen megoldás, ha az egyik napon törli, és egy másik napon újra létrehozza. Vegye figyelembe, hogy egy munkamenetblokk törlése automatikusan feloldja (konferenciák esetében) vagy törli (értekezletek esetében) a benne lévő összes hozzászólást. A benne lévő összes szünetet is törölni fogja.

Egy ülésblokk törléséhez kattintson az ülésblokkra, majd kattintson a szemetes ikonra:

![](../assets/conferences/timetable/block_delete.png)

##### Poszter szekciók

Az ütemezés másképp működik, ha egy ülésblokk egy poszterüléshez tartozik (további részletek a poszterülések létrehozásának módjáról [itt](./sessions.md)). Ha ez a helyzet, a blokkban lévő hozzászólásokat poszterként kezeljük, és automatikusan párhuzamosan ütemezzük őket, a kezdési és befejezési idő megegyezik a szülő ülésblokkéval. Ezenkívül nem lehetséges szünetet beiktatni egy poszter ülésen belül.

Ha egy poszter-üléshez tartozó ülésblokkban szeretne hozzászólást ütemezni, kattintson a jobb felső sarokban a _Add poster_ gombra, és válassza ki a beütemezni kívánt hozzászólásokat:

![](../assets/conferences/timetable/add_poster.png)

Vegye észre azt is, hogy az ütemterv másképp néz ki - ahelyett, hogy az egyes hozzászólások kezdő és befejező időpontját mutatná, egyszerűen egy listát jelenít meg. 

#### Szünetek

A szünetek szünetet tartanak a program egyéb tervezett programpontjai, például az ebédszünet között. A szünetet az órarend legfelső szintjén vagy egy munkamenetblokkban lehet beütemezni. A legfelső szintű szünet hozzáadásához kattintson az _Új hozzáadása_ gombra, és válassza a _Szünet_ lehetőséget:

![](../assets/conferences/timetable/break.png)

Töltse ki a címet, a kezdési és befejezési időt, valamint opcionálisan a leírást, a helyszínt és a színt. Erősítse meg a _Save_ gombra kattintva, amely beütemezi a szünetet.

![](../assets/conferences/timetable/add_break.png)

Ezeket a részleteket később bármikor szerkesztheti, ha a szünetre kattint, amely egy párbeszédablakot nyit meg.

![](../assets/conferences/timetable/edit_break.png)

A kezdési időpont megváltoztatásához a szünet felfelé és lefelé húzható, csakúgy, mint a hozzászólások és az ülésblokkok. Az időtartam a szünet alsó szélének húzásával módosítható. A hozzájárulásokhoz hasonlóan a szünetek is áthelyezhetők más napokra vagy ülésblokkokba, akár a _Mozgatás_ ikonra kattintva, akár a szünetet egy ülésblokk fölé húzva.

A szünet törléséhez kattintson a szemetes ikonra, majd erősítse meg a _OK_ gombra kattintva.

Ha szünetet szeretne létrehozni egy munkamenetblokkon belül, először nyissa meg a munkamenetblokkok órarendjét a munkamenetblokkra kattintva, majd válassza a _Menj a munkamenetblokkok órarendjéhez_ lehetőséget.

![](../assets/conferences/timetable/block_timetable.png)

Ezután ugyanazokat a lépéseket követheti, mint a fent leírt felső szintű szünet esetében.

#### Újratervezés

Ha úgy találja, hogy egy adott nap vagy egy ülésblokk összes bejegyzésének kezdési időpontját vagy időtartamát módosítani kell, használhatja az _Reschedule_ funkciót. Ez automatikusan módosítja az összes bejegyzést, ahelyett, hogy minden egyes bejegyzést kézzel kellene beállítania.

A kezdéshez válassza ki a legfelső szintű órarendet vagy egy ülésblokk órarendjét, majd kattintson a _Útütemezés_ gombra a jobb felső sarokban.

![](../assets/conferences/timetable/reschedule.png)
![](../assets/conferences/timetable/reschedule_dialog.png)

Beállíthatja a kezdési időpontot vagy az időtartamot. Ha a kezdési időpont beállítása mellett dönt, az ütemterv első bejegyzése úgy kerül áthelyezésre, hogy a kezdési időpontja megegyezzen az esemény kezdési időpontjával. Ülésblokkok esetén a bejegyzés úgy kerül áthelyezésre, hogy az akkor kezdődjön, amikor az ülésblokk kezdődik. Az összes többi bejegyzés az első bejegyzés után kerül "egymásra", hogy a bejegyzések közötti hézagokat teljesen kitöltse.

Ez egy példa az ülésblokk menetrendjére a kezdési időpont beállítása előtt:

../assets/conferences/timetable/before_reschedule_start_time.png)

Ez pedig a végeredmény. Vegye észre, hogy a kezdési időpont 16:00-ról 15:20-ra (az ülésblokk kezdési időpontja) került át, és a bejegyzések közötti hézagok eltűntek. A bejegyzések időtartama nem változott.

![](../assets/conferences/timetable/after_reschedule_start_time.png)

A második átütemezési lehetőség, amely az összes bejegyzés időtartamát módosítja, az egyes bejegyzéspárok közötti üres hézagot úgy tölti ki, hogy a bejegyzések időtartamát meghosszabbítja, de a kezdési időt változatlanul hagyja.
Ha az előző példát használjuk, és kiigazítjuk az időtartamokat, ezt a végeredményt kapjuk:

![](../assets/conferences/timetable/after_reschedule_duration.png)

Vegyük észre, hogy az utolsó hozzászólás időtartama nem változott, mivel ez az utolsó bejegyzés az órarendben, és így nincs kitöltendő "rés".

A fent ismertetett mindkét opcióval megadható egy "időhézag". Ezáltal minden egyes bejegyzési pár között marad egy rés, ahelyett, hogy teljesen kitöltené azt.

![](../assets/conferences/timetable/reschedule_gap.png)

Ha ugyanezt a példát újra vesszük, és a kezdési időpontot 10 perces időkülönbséggel állítjuk be, akkor ezt kapjuk:

![](../assets/conferences/timetable/after_reschedule_gap.png)

Az összes eseményt korábbi időpontra helyeztük át, miközben 10 perc hézagot hagytunk közöttük.

#### Illeszkedés a tartalomhoz

Ha egy ülésblokk időtartama nagyobb, mint a tartalma teljes időtartama, lehetőség van arra, hogy automatikusan összezsugorítsa, hogy pontosan lefedi a bejegyzéseket. Ehhez a blokk kezdő időpontját az első bejegyzés kezdő időpontjára, a blokk végét pedig az utolsó bejegyzés végére kell beállítani. Ez a művelet nem mozgatja az egyes bejegyzéseket a munkamenetblokkon belül.

Ha egy munkamenetblokkot a tartalmához szeretne igazítani, kattintson a munkamenetblokk ütemtervének jobb felső sarkában található _Tartalomhoz igazítás_ gombra:

![](../assets/conferences/timetable/fit_to_content.png)

Egy adott nap összes ülésblokkját is tartalomhoz illesztheti, ha a felső szintű órarendben a _Újratervezés_ gombra kattint, és bejelöli az _Minden ülésblokkot a tartalomhoz illeszteni_ jelölőnégyzetet.

![](../assets/conferences/timetable/fit_to_content_reschedule.png)

!!! Megjegyzés
    Vegye figyelembe, hogy a _Fit to content_ csak akkor szükséges, ha egy ülésblokkot szeretne összezsugorítani. Egy munkamenetblokk mindig automatikusan megnő a tartalmának megfelelően. Valójában nem lehet beállítani, hogy egy munkamenetblokk időtartama kisebb legyen, mint a tartalma időtartama.

### Az órarend nyilvánosságra hozatala (csak konferenciák esetén)

Alapértelmezés szerint az eseményekhez való hozzászólások "Tervezet módban" vannak. Ez azt jelenti, hogy a rendszeres felhasználók nem láthatják a hozzászólások listáját, az időbeosztást, az absztraktok könyvét, valamint a szerzők és előadók listáját. A vázlatos üzemmód azért van, hogy a résztvevők ne láthassák az ütemtervet, amíg az elkészül.

Ha nyilvánossá kívánja tenni az ütemtervet, kikapcsolhatja a tervezet módot. Ehhez navigáljon a _Contributions_ oldalra, és kapcsolja be a jobb felső sarokban a _Draft_ lehetőséget.

![](../assets/conferences/timetable/draft.png)

Ugyanezt megteheti a _Settings_ vagy a _Timetable_ oldalról is, ha a figyelmeztetésen belül a _Publish contributions_ gombra kattint.

![](../assets/conferences/timetable/draft_warning.png)
