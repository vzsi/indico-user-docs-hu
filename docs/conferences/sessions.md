Ez az oldal elmagyarázza a _Sessions_ célját az Indicóban, és azt, hogyan használjuk őket.

Egyszerűen fogalmazva, az ülések egy módja annak, hogy csoportosítsuk az egymáshoz kapcsolódó hozzájárulásokat, amikor egy órarendet készítünk.
Például egy konferenciát fel lehet osztani egy üdvözlő ülésre, egy előadásoknak szentelt ülésre, műhelyülésekre stb.

Ebben a részben a szervezők szemszögéből vizsgáljuk meg, hogyan hozhatók létre és kezelhetők az ülések. Ha szeretné megtanulni, hogyan használjuk az üléseket az órarend létrehozásakor, akkor tekintse meg [ezt az oldalt](./timetable.md).

### Üléstípus létrehozása

Mielőtt létrehoznánk egy munkamenetet, először létrehozunk egy munkamenet típust. A munkamenet-típusok segíthetnek a munkamenetek jobb szervezésében, de nem szükségesek, hacsak nem akarunk poszter munkameneteket használni (további részletekért lásd a [menetrend oldal](./timetable.md)).

Új ülésszak-típus létrehozásához navigáljon egy esemény kezelési területére, és válassza a _Organizáció_ alatt az _Sessions_ menüpontot.

![](../assets/conferences/sessions/sessions_management.png)

Kattintson felül a _Settings_ (Beállítások) gombra, és válassza ki a legördülő menüből a _Session types_ (Üléstípusok) menüpontot.

![](../assets/conferences/sessions/session_settings.png)

Az új párbeszédpanelben kattintson az _Új munkamenet típus_ gombra, és válasszon ki egy nevet.

![](../assets/conferences/sessions/add_session_type.png)

Ha bekapcsolja a _Poster_ kapcsolót, akkor minden ülés, amelynek ez az ülés típusa szerepel, poszter üléssé válik. Amikor egy poszterülés ütemtervét hozza létre, az ülésblokkban lévő összes hozzászólás automatikusan párhuzamosan, azonos kezdési időponttal és időtartammal kerül ütemezésre. A [menetrend oldal](./timetable.md) oldalon többet megtudhat az ülésblokkokról és a poszterülésekről.

### Ülés létrehozása

Ülés létrehozásához navigáljon egy esemény kezelési területére, és válassza az _Organizáció_ alatt az _Ülések_ lehetőséget. Ezen az oldalon megjelenik az összes üléseinek listája. Új ülés létrehozásához kattintson a felső menüben az _Új ülés hozzáadása_ gombra.

![](../assets/conferences/sessions/create_session.png)

A párbeszédablakban töltse ki a címet és opcionálisan a többi mezőt. A _Típus_ mezőben található legördülő listából kiválaszthatja a munkamenet típusát. Ezek a korábban létrehozott munkamenet-típusok. Az _Default contribution duration_ mező szabályozza az ebben a munkamenetben beütemezett hozzájárulások alapértelmezett időtartamát.
Ebben a munkamenetben a munkamenetblokkok alapértelmezett helyét is kiválaszthatja. A rendelkezésre álló helyszínek a [Szobafoglalás modul] (../room_booking/about.md) modulból származnak. Ha nem választ ki semmilyen helyszínt, akkor helyette az esemény helyszíne lesz alapértelmezettként használva. Miután kitöltötte a párbeszédpanelt, kattintson a _Mentés_ gombra a munkamenet létrehozásához.

![](../assets/conferences/sessions/create_session_2.png)

A munkamenetet később bármikor szerkesztheti, ha a munkamenet jobb oldalán lévő ceruza ikonra kattint:

![](../assets/conferences/sessions/edit_session.png)

### A munkamenet kezelése

Miután létrehoztunk egy munkamenetet, azt a munkamenetek listájához adjuk hozzá. 
A listából gyorsan megváltoztathatja a munkamenet típusát. Ha teljesen el szeretne távolítani egy munkamenet típust, egyszerűen kattintson újra a típusra, ami megvonja a kijelölést.

![](../assets/conferences/sessions/set_session_type.png)

Az egyes munkamenetekben a _Blocks_ oszlopban láthatja az ütemezett munkamenetblokkokat. Ha anyagot szeretne feltölteni az üléshez, kattintson a _Material_ nevű oszlopban található linkre. Ekkor megjelenik egy párbeszédablak, ahol fájlokat tölthet fel a munkamenetbe. Vegye figyelembe, hogy ez a fájlokat az egész munkamenethez, nem pedig egy munkamenetblokkhoz adja hozzá.

![](../assets/conferences/sessions/blocks_material.png)

A feltöltött fájlok láthatóak lesznek az eseménynaptárban az adott üléshez tartozó minden ülésblokkban. A fájlok az ülés részleteiben is elérhetők a _Prezentációs anyagok_ alatt.

![](../assets/conferences/sessions/material.png)

Egy adott ülésszak menetrendjének megtekintéséhez kattintson a jobb oldali óra ikonra:

![](../assets/conferences/sessions/session_timetable.png)

Egy ülés törléséhez kattintson a kuka ikonra. Vigyázzon, hogy egy munkamenet törlése törli az összes munkamenetblokkját, és az azokban szereplő összes hozzászólás ütemezését.

![](../assets/conferences/sessions/delete_session.png)

Alapértelmezés szerint az eseménykezelők a munkamenet minden aspektusát kezelhetik - szerkeszthetik az adatokat, valamint kezelhetik a munkamenetblokkokat és a hozzájárulásokat. Ha azt szeretné, hogy további felhasználók is kezelhessenek egy munkamenetet, kattintson a pajzs ikonra:

![](../assets/conferences/sessions/protection.png)

Az új párbeszédablakban kiválaszthatja, hogy kik kezelhetik még a munkamenetet. Kiválaszthatja a teljes körű kezelési jogokat, amely teljes ellenőrzést biztosít a munkamenet felett, vagy csak _Coordination_ jogokat adhat.

![](../assets/conferences/sessions/coordinate.png)

Az úgynevezett munkamenet-koordinátorok alapértelmezés szerint megtekinthetik a munkamenet adatait, beoszthatják a hozzászólásokat és szüneteket hozhatnak létre. Az üléskoordinátorok további jogokat is kaphatnak az esemény _Védelem_ főoldalán az _Üléskoordinátori jogok_ alatt.

![](../assets/conferences/sessions/coordination_rights.png)

A _Contributions_ bekapcsolásával az üléskoordinátorok is módosíthatják az üléseken szereplő hozzájárulásokat. A _Session blocks_ bekapcsolásával az üléskoordinátorok is képesek lesznek az ülésblokkok kezelésére, beleértve az újak létrehozását is.

Bármely személy, akit kifejezetten legalább egy munkamenet menedzsereként vagy koordinátoraként jelöltek ki, a rendezvény főoldalán a _Mi munkameneteim_ alatt tudja majd kezelni a munkameneteit:

![](../assets/conferences/sessions/my_sessions.png)

### Az ülésszak-koordinátorok és az összehívók megkülönböztetése

Mind a koordinátorok, mind az összehívók az ülésekhez kapcsolódnak, azonban van különbség a kettő között.
Az ülésszak-koordinátorok olyan szerepkör, amely extra jogokkal jár. Ők kezelhetik az üléseiket, és jogaik terjedelme a korábban ismertetett _Üléskoordinátori jogok_tól függ.

Ezzel szemben az ülésszak összehívói inkább a hozzászólás előadóihoz hasonlítanak, mivel nem kapnak extra jogokat az ülésszak felett. Az ülésszakok összehívói csupán az egyes ülésblokkok jobb felső sarkában lévő órarendben megjelenő személyek:

![](../assets/conferences/sessions/conveners.png)

A [menetrend oldal](./timetable.md) segítségével megtudhatja, hogyan rendelheti az összehívókat az ülésblokkokhoz.
