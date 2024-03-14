# Funkciók Összefoglalása

## Általános

Az általános funkciók:

* Önálló módban vagy egy Indico **eseményhez** kötve.
  * Az önálló mód lehetővé teszi a foglalást, foglalások kezelését és az adminisztrációs feladatokat. Nem kell létrehoznod egy Indico eseményt \(a foglalások nem lesznek hozzárendelve semmilyen Indico eseményhez\).
  * Az Indico eseményhez kötött mód lehetővé teszi, hogy helyiségeket foglalj az eseményedhez. A foglalt helyiségeket konferenciákhoz, előadásokhoz, megbeszélésekhez, ülésszakokhoz, hozzájárulásokhoz vagy szünetekhez rendelheted.
* Ismétlődő foglalások, pl. _Napi_, _Heti_, _Havi_.
* E-mail értesítések \(felhasználóknak és helyiség menedzsereknek, minden fontos tevékenységről\).
* Három felhasználói szerep: \(1\) Indico adminisztrátor, \(2\) helyiség menedzser és \(3\) átlagos felhasználó.
* Opcionális foglalás moderálás. Minden helyiség az alábbi módban működhet:
  * A foglalásokat a helyiség menedzserének explicit megerősítése szükséges, _vagy_
  * A foglalások automatikusan elfogadásra kerülnek.

## Felhasználó

Az átlagos felhasználók számára elérhető opciók:

* Helyiség foglalása
* Saját foglalások kezelése \(követés, módosítás, klónozás, lemondás\)
* Helyiségek keresése
* Foglalások keresése \(archiváltakat is beleértve\)
* Meglévő helyiség blokkolások megtekintése

## Helyiség Menedzser

A felhasználókhoz képest, a helyiség menedzser további hozzáféréssel rendelkezik:

* Előfoglalások elfogadása és elutasítása \(a saját helyiség\(ei\)hez\)
* Foglalások elutasítása \(a saját helyiség\(ei\)hez\)
* Helyiségek blokkolása a foglalás elől \(a helyiség tulajdonosának jóváhagyásával\)
* Blokkolási kérelmek elfogadása \(a saját helyiség\(ei\)hez\)

## Indico Adminisztrátor

A helyiség menedzserhez képest, az Indico Adminisztrátor további hozzáféréssel rendelkezik:

* A Helyiségek Foglalási Modul be-/kikapcsolása
* Helyiség foglalási pluginok konfigurálása az admin szekcióban
* Helyszín hozzáadása/eltávolítása
* A helyszínre specifikus helyiség attribútumok meghatározása
* A helyszínre specifikus lehetséges helyiség felszereltség meghatározása
* Tárgyalók kezelése \(hozzáadás/módosítás/eltávolítás\)

## Korlátozások

A helyiségnek rendelkeznie kell menedzserével. Nem lehetséges több menedzsert megadni egyetlen helyiséghez \(megkerülhető egy több ember által megosztott Indico fiók létrehozásával\).

A helyiségnek rendelkeznie kell meghatározott épülettel, amely számnak kell lennie. Ez kötelező. Ha nem szükséges az épület, írj be bármilyen számot \(mint '0'\). Ha az épület nevei betűket tartalmaznak, sajnáljuk - a szoftver nem elég rugalmas az Ön számára.

A helyiségnek rendelkeznie kell meghatározott emelettel \(alfanumerikus\) és helyiség 'számmal' \(valójában alfanumerikus\).

Korlátozások vonatkozhatnak az időszakra, amelyre periódikus foglalást definiálhatsz, pl. lefoglalhatod ugyanazt a helyiséget minden nap ugyanabban az időben, de nem több mint X hét/hónap.

---
