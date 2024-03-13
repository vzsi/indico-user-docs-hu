# A funkciókészlet összefoglalása

## Általános

Általános jellemzők:

* Önálló üzemmód vagy Indico **eseményhez** kötve.
  * Az önálló mód lehetővé teszi a foglalást, a foglalások kezelését és az adminisztrációs dolgok elvégzését. Nem kell Indico eseményt létrehoznia \(a foglalások nem lesznek hozzárendelve semmilyen Indico eseményhez\).
  * Az Indico eseményhez kötött mód lehetővé teszi, hogy szobákat foglaljon le az eseményhez. A lefoglalt termeket hozzárendelheti konferenciákhoz, előadásokhoz, megbeszélésekhez, ülésekhez, hozzászólásokhoz vagy szünetekhez.
* Ismétlődő foglalások, pl. _Napi_, _Heti_, _Havi_ foglalások.
* E-mail értesítések \(a felhasználóknak és a teremfelelősöknek, minden fontos eseményről\).
* Három felhasználói szerepkör: \(1\) Indico adminisztrátor, \(2\) szobafenntartó és \(3\) szobafenntartó.
  \(3\) közönséges felhasználó.
* Opcionális foglalási moderáció. Minden szoba a következő módok egyikében működhet:
  * A foglalásokhoz a szobafenntartó kifejezett megerősítése szükséges, _vagy_ a szobafoglalásokhoz a szobafenntartó kifejezett megerősítése.
  * A foglalások automatikusan elfogadásra kerülnek.


## Felhasználó

A rendszeres felhasználók számára elérhető lehetőségek:

* Szobafoglalás
* Saját foglalások kezelése \(követés, módosítás, klónozás, törlés\)
* Szobák keresése
* Foglalások keresése \(beleértve az archiválást is\)
* Meglévő szobafoglalások megtekintése



## Szobakezelő

Azon túlmenően, amihez a felhasználó hozzáférhet, a szobamenedzser a következőket teheti:

* Elfogadhatja és elutasíthatja az előzetes foglalásokat \(a saját szobájára\(s\)\)
* Visszautasítani a foglalásokat \(a szobájára\(s\)\)
* Szobafoglalások blokkolása \(a szoba tulajdonosának megerősítésével\)
* Blokkolási kérelmek elfogadása \(a szobájára\(s\)\)


## Indico adminisztrátor

Azon túlmenően, amihez a szobafenntartónak hozzáférése van, az Indico adminisztrátor a következőkre is képes:


* Be- és kikapcsolhatja a szobafoglalási modult
* Szobafoglalási pluginok konfigurálása az admin szekcióban
* Helyszín hozzáadása/eltávolítása
* Meghatározhatja a helységre jellemző szobaattribútumokat.
* Meghatározhatja a helyiség lehetséges felszerelését a helyszínre jellemzően.
* Tárgyalótermek kezelése \(hozzáadás/módosítás/eltávolítás\)


## Korlátozások

A teremnek rendelkeznie kell kezelővel. Egy teremhez nem lehet több menedzsert definiálni \(ezt megkerülheti egy több ember által megosztott Indico fiók létrehozásával).

A szobának rendelkeznie kell egy meghatározott épülettel, amelynek egy számnak kell lennie. Ez kötelező. Ha nincs szükség épületre, akkor bármilyen számot megadhat \(például '0'\). Ha az Ön épület elnevezési rendszere betűket tartalmaz, sajnáljuk - a szoftver nem elég rugalmas az Ön számára.

A szobának meghatározott emelettel \(alfanumerikus \) és a szoba 'számával' \(alfanumerikus \) kell rendelkeznie.

Korlátozások vonatkozhatnak arra az időtartamra, amelyre időszakos foglalást definiálhat, pl. ugyanazt a szobát minden nap ugyanabban az időpontban foglalhatja, de legfeljebb X hétre/hónapra.

---