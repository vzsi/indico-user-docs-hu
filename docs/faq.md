# Gyakran ismételt kérdések

!!!! megjegyzés
    Ez a rész még aktív fejlesztés alatt áll


## A hovatartozási információm nem terjedt át az összes eseményre, miután megváltoztattam a profilomon. Ez normális?

**Nagy valószínűséggel igen**. Az Indico több szinten tárolja a felhasználói információkat. A profilodban végrehajtott módosítások és csak
csak a **a módosítás után létrehozott eseményekre** terjednek át. Értesítenie kell a kérdéses esemény menedzserét, amennyiben
szeretné, ha az adatait frissítenék benne.


### Miért történik ez így?

Mert az Indico igyekszik megőrizni az adatokat **úgy, ahogyan azok az esemény bekövetkezésekor voltak**. Ha Ön egy konferencián beszélt
2010-ben, amikor még az X. Egyetemen volt, akkor valószínűleg az adott eseményen is ezzel a hovatartozással szeretne szerepelni, és nem az alábbiakban.
az intézet, ahol most dolgozik.
Hasonlóképpen, ha két munkahelye van, az egyik az X egyetemen, a másik pedig az Y vállalatnál, és úgy szerepel, mint aki a következő cég nevében beszél.
cég nevében szerepel egy konferencián, nem szeretné, ha ez az információ felülíródna, ha megváltoztatja a fő hovatartozását.

További információkat olvashat arról, hogy az Indico hogyan kezeli a felhasználói információkat [itt](./conferences/people.md).


## Szeretném használni az Indicót az intézményemben. Fizetnem kell érte? Hogyan kaphatok fiókot?

Az Indico **nyílt forráskódú szoftver**, ami azt jelenti, hogy a forráskódja bárki számára korlátozás nélkül elérhető. A licenc [megengedő licenc](https://github.com/indico/indico/blob/master/LICENSE) alatt áll, amely lehetővé teszi, hogy ingyenesen használd, módosítsd és terjeszd tovább, amíg tiszteletben tartod a szerzői jogi hivatkozást és a licenc egyéb feltételeit. A CERN ezt a terméket ingyenesen bocsátja rendelkezésre a [küldetése](https://home.cern/about/who-we-are/our-mission) részeként, amely a technológia határainak világszerte történő előmozdítására irányul.

Az Indico egy **web alkalmazás**, ami azt jelenti, hogy a futtatásához szerver infrastruktúrára van szükség. Ennek ellenére, ha szeretné, hogy az Indico az Ön szervezetében is működjön, a következő lehetőségek állnak rendelkezésére:

 * **(Legegyszerűbb)** Megbízhat valakit, hogy **futtassa Ön helyett** - ez azt jelenti, hogy talál egy kereskedelmi tárhelyszolgáltatót, aki vagy az Ön IT-infrastruktúrájára vagy az övékre telepíti és ennek megfelelően karbantartja.
 * **(Legolcsóbb)** **Futtasd **magad**, feltéve, hogy te vagy az informatikai részleged rendelkezik Linux rendszergazdai ismeretekkel. Nagyon teljes [telepítési útmutatót](https://docs.getindico.io/en/stable/installation/production/) kínálunk, amely végigvezeti Önt ezen a folyamaton.
 * [**Global Indico**](https://indico.cern.ch/category/5372/) kategória - **specifikus körülmények között** lehetséges, hogy az "indico.cern.ch" címen is tudunk Önnek tárhelyet biztosítani, nevezetesen, ha Ön egy kutatási vagy oktatási intézmény tagja. Ehhez el kell fogadnia a [méltányos használatra vonatkozó szabályzatunkat](https://cern.service-now.com/service-portal?id=kb_article&n=KB0004606). Nyugodtan lépjen kapcsolatba velünk, ha ezt szeretné kipróbálni.
 * Van még egy utolsó lehetőség, ami az, hogy megkérsz egy **másik Indico szervert** a közösségben, hogy adjon neked egy fiókot. Ha oktatási intézmény vagy laboratórium vagy, lehetséges, hogy a kutatási hálózatodban egy másik szervezetnek már van szervere.

A CERN **nem** nyújt jelenleg semmilyen kereskedelmi Indico szolgáltatást.
