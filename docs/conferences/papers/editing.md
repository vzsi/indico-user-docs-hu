# Szerkesztés

### Bevezetés

Ez a rövid videó bemutatja az Indico szerkesztési folyamatát:

<iframe width="576" height="360" frameborder="0" src="https://cds.cern.ch/video/2728257?showTitle=true" allowfullscreen></iframe>

Ahogy a Kéziratlektorálási modul, úgy a Szerkesztési modul is egy olyan folyamatot biztosít, ahol a szerzők beküldik a cikkeiket, amiket aztán felülvizsgálnak és/vagy javítanak.
Pontosabban, a modul lehetővé teszi, hogy

- cikkeket, posztereket és diákat küldj be felülvizsgálatra,
- beállíts egy szerkesztői csapatot és szerkesztőket rendelj a szerkeszthető anyagokhoz,
- áttekintsd és értékeld a szerkeszthető anyagokat, és
- közzé tedd az elfogadott anyagokat.

!!! megjegyzés
    Ha nem vagy biztos abban, hogy melyik modult használd, nézd meg a [bevezetőt](./introduction.md) egy átfogó leíráshoz a Kéziratlektorálási és Szerkesztési modulokról.

Íme egy ábra, amely áttekintést nyújt a szerkesztési munkafolyamatról:

![](../../assets/papers/editing/editing_diagram.png)

A következő szakaszokban azt magyarázzuk el, hogyan használható a Szerkesztési modul a szervezők, szerzők és cikkértékelők szemszögéből.

### A Szerkesztési modul beállítása menedzser/szervezőként

#### A modul engedélyezése

Ahhoz, hogy elkezdd használni a Szerkesztési modult, először engedélyezned kell azt.
A rendezvény kezelési oldaláról kattints a bal menüben a _Szerkesztés_ fülre a _Munkafolyamatok_ alatt.
Kattints a _Modul engedélyezése_ gombra a Szerkesztési modul engedélyezéséhez.

![](../../assets/papers/editing/enable.png)

A modul bármikor kikapcsolható a _Funkciók_ fülön az _Haladó beállítások_ alatt.

![](../../assets/papers/editing/disable.png)

Amint a modul engedélyezve van, új fülek jelennek meg a konferencia menüjében, amikor átváltasz a megjelenítési területre.

![](../../assets/papers/editing/editing_enabled.png)

#### Hozzáférés biztosítása a Szerkesztési modulhoz

Alapértelmezés szerint az esemény menedzserei hozzáférhetnek a Szerkesztési modul kezelési területéhez.
Ezenkívül bárki, akinek a _Szerkesztési menedzser_ engedélye van, szintén kezelheti a modult.
Ezt az engedélyt az esemény _Védelem_ oldalán lehet beállítani.

![](../../assets/papers/editing/editing_manager.png)

#### Szerkeszthető típusok konfigurálása

Ahogy korábban említettük, a Szerkesztési modul lehetővé teszi, hogy nem csak cikkeket, hanem diákat és posztereket is beküldj. Ezeket szerkeszthető típusoknak nevezzük, és konfigurálhatod, hogy melyiket engedélyezed. A szerzők nem tudnak anyagot beküldeni az adott típushoz, hacsak azt nem engedélyezték.
Alapértelmezés szerint csak a _cikk_ szerkeszthető típus engedélyezett.

További szerkeszthető típusok engedélyezéséhez először navigálj a _Szerkesztés_ oldalra a kezelési területen. Ezután kattints a _Szerkeszthető típusok váltása_ gombra:

![](../../assets/papers/editing/editable_types.png)

Most már váltogathatod az egyes szerkeszthető típusokat:

![](../../assets/papers/editing/editable_types_toggle.png)

Ha befejezted, kattints a _Mentés_ gombra a változtatások mentéséhez.

Figyelembe kell venni, hogy minden szerkeszthető típus beállítása különálló. Megnyithatod őket azzal, hogy a szerkeszteni kívánt típus mellett a _Kezelés_ gombra kattintasz:

![](../../assets/papers/editing/editable_types_settings.png)

Ezen a beállítások oldalon láthatod:

![](../../assets/papers/editing/editable_types_settings_view.png)

Az alcím azt mutatja, hogy jelenleg melyik szerkeszthető típust szerkeszted. Ebben az esetben a cikkek beállításait szerkesztjük.

A következő szakaszokban különféle beállításokat magyarázunk el ezen az oldalon.

#### Fájltípusok kezelése

Ugyanebből a beállítások menüből kezelheted az engedélyezett fájltípusokat azzal, hogy a _Konfigurálás_ gombra kattintasz a _Fájltípusok_ mellett:

![](../../assets/papers/editing/file_types.png)

Alapértelmezés szerint a PDF van hozzáadva, mint az alapértelmezett fájltípus.

![](../../assets/papers/editing/pdf.png)

Ez azt jelenti, hogy alapértelmezés szerint a szerzők csak PDF fájlokat nyújthatnak be ezen a szerkeszthető típuson. Ha más fájltípusokat is szeretnél engedélyezni, például CSV fájlt további adatokkal, kattints az _Új fájltípus hozzáadása_ gombra az oldal alján.

![](../../assets/papers/editing/add_file_type.png)

Ez egy párbeszédablakot nyit meg több opcióval:

![](../../assets/papers/editing/create_file_type.png)

A _Fájlnév sablon_ egy opcionális fájlnév minta. Ezt használhatod annak biztosítására, hogy a benyújtott fájlok nevei megfeleljenek a megadott mintának. Például minden CSV fájl, ami '\_adat' végződéssel, és minden PDF fájl, ami '\_cikk' végződéssel zárul. Opcionálisan megadhatod az engedélyezett fájlkiterjesztéseket is, például '.csv' a CSV fájlokhoz és '.pdf' a PDF fájlokhoz. A párbeszédablak alján további opciókat kapcsolhatsz be vagy ki.

- Fájl szükséges - megadja, hogy ez a fájl szükséges-e a megadott szerkeszthető (cikk, poszter vagy diák) benyújtásakor.
- Több fájl - lehetővé teszi több fájl feltöltését ugyanahhoz a szerkeszthető típushoz, például több PDF fájl.
- Közzétehető - szabályozza, hogy a fájlok ezen a típuson közzétehetők-e az adott hozzájárulásban. Ez hasznos, ha bizonyos fájlokat csak a szerkesztőknek kell látniuk.

Ha kész vagy, kattints a _Beküldés_ gombra az új fájltípus létrehozásához. Ha később szeretnéd szerkeszteni a fájltípust, megteheted a mellette lévő szerkesztési ikonra kattintva. Egy fájltípus törlése akkor is lehetséges, ha még nem töltöttek fel ilyen típusú fájlt, és a fájltípus nincs hivatkozva a felülvizsgálati feltételekben (a következő szakaszban ismertetve).

![](../../assets/papers/editing/edit_file_type.png)

#### 'Felülvizsgálatra kész' feltételek beállítása

Amennyiben összetett benyújtási követelményeid vannak a fájltípusok alapján, hasznát veheted a felülvizsgálati feltételek beállításának. A felülvizsgálati feltételek akkor hasznosak, ha például egy konferencia megköveteli a szerzőktől, hogy PDF vagy Word dokumentumot küldjenek be egy CSV fájllal együtt. Mivel szeretnéd, ha a szerzők választhatnának a PDF és a Word között, egyik fájltípust sem teheted kötelezővé. Azonban azt szeretnéd, hogy legalább az egyikük benyújtásra kerüljön. A felülvizsgálati feltételek lehetővé teszik, hogy könnyedén kifejezd az ilyen összetett feltételeket.

Fontos megjegyezni, hogy ezek a feltételek nem akadályozzák meg a szerzőket az hiányos benyújtások feltöltésében, hanem a szerkeszthető idővonala figyelmeztetést jelenít meg, amíg a felülvizsgálati feltételek nem teljesülnek.

Új feltétel hozzáadásához kattints a _Konfigurálás_ gombra a kiválasztott szerkeszthető típus kezelési oldalán a _Felülvizsgálatra kész feltételek_ mellett.

![](../../assets/papers/editing/review_condition_btn.png)

A következő oldalon kattints a _Új fájltípus feltétel létrehozása_ gombra.

![](../../assets/papers/editing/review_condition.png)

Használd a legördülő menüt a korábban meghatározott fájltípusok kiválasztásához. Ha több fájltípust választasz ki, a kiválasztott fájltípusok kombinációját kell benyújtani.
Például, ha PDF-et és CSV-t választasz, a szerzőknek legalább egy fájlt kell feltölteniük minden típusból.

Amikor kiválasztottad az első feltételt, kattints a pipa ikonra a megerősítéshez:

![](../../assets/papers/editing/review_condition_create.png)

Példánk befejezéséhez adjunk hozzá egy második feltételt Word dokumentumhoz és CSV fájlhoz. A végső állapot így fog kinézni:

![](../../assets/papers/editing/review_condition_final.png)

Ezek a példafeltételek azt jelentik, hogy a szerzőknek CSV fájlt kell benyújtaniuk egy PDF vagy Word dokumentummal együtt.
Ha a feltételek nincsenek teljesítve, a szerzők és a szerkesztők egyaránt figyelmeztetést fognak látni a szerkeszthető idővonalán:

![](../../assets/papers/editing/unmet_conditions.png)

#### A szerkesztői csapat beállítása

A Szerkesztési modul lehetővé teszi, hogy szerkesztői csapatot állíts be. Ez a funkció hasonló a Kéziratlektorálási modulban található lektorálói csapatokhoz.
Csak azok a felhasználók láthatják a szerkeszthető anyagok listáját és tekinthetik át őket, akiket hozzáadtak a szerkesztői csapathoz.
A Kéziratlektorálási modultól eltérően itt nincs különbség a lektorok és a bírálók között - a szerkesztők mindkét szerepet betöltik.

A szerkesztői csapat különálló minden szerkeszthető típushoz, ami azt jelenti, hogy például a cikkek szerkesztői csapata eltér a poszterek vagy diák szerkesztői csapatától.

Szerkesztő hozzáadásához a szerkesztői csapathoz kattints a _Csapat kezelése_ gombra a _Szerkesztői csapat_ mellett:

![](../../assets/papers/editing/team.png)

Itt add hozzá a felhasználóidat és kattints a _Beküldés_ gombra. Ugyanezt a eljárást használhatod szerkesztők eltávolítására is.

![](../../assets/papers/editing/team_add.png)

Miután beállítottad a szerkesztői csapatot, mostantól egyszerűen kapcsolatba léphetsz az összes szerkesztővel emailen keresztül, ha szükséges. Kattints a _Kapcsolat_ gombra,
válaszd ki a címzetteket és kattints a _Levelek küldése_ gombra, ami egy párbeszédablakot nyit meg, ahol beírhatod az emailt.

![](../../assets/papers/editing/team_contact.png)

A Szerkesztési modul lehetővé teszi továbbá, hogy a szerkesztők ne legyenek nyilvánosak.
Ez azt jelenti, hogy a szerzők nem láthatják a szerkesztők személyazonosságát, akik áttekintik és megjegyzéseket fűznek a benyújtásaikhoz.

A szerkesztők alapértelmezés szerint láthatóak. Ahhoz, hogy elrejtsd őket, kapcsold be a _Szerkesztői csapat tagjainak anonim tartását_ a _Szerkesztői csapat_ mellett:

![](../../assets/papers/editing/team_anonymous.png)

#### A benyújtás és szerkesztés megnyitása

Amikor befejezted a Szerkesztési modul konfigurálását, megnyithatod a benyújtásokat és a szerkesztést. Ez lehetővé teszi a szerzők számára, hogy szerkeszthető anyagokat nyújtsanak be, és a lektorok áttekinthessék azokat.
Minden szerkeszthető típus (cikkek, diák és poszterek) külön-külön nyitható és zárható meg. Mind a benyújtásokat, mind a lektorálást megnyithatod a szerkeszthető típus kezelési oldaláról a _Most indítás_ gombra kattintva:

![](../../assets/papers/editing/submissions.png)

A benyújtások vagy a lektorálás lezárásához egyszerűen kattints a _Most bezárás_ gombra.

#### Szerkeszthető anyagok hozzárendelése

A szerkesztők csak azokat a szerkeszthető anyagokat tekinthetik át, amelyeket a szerkesztési menedzserek rendeltek hozzájuk. A szerkesztők hozzárendeléséhez a kiválasztott szerkeszthető típus _Szerkesztői hozzárendelés_ szakaszában kattints a _Lista_ gombra.

![](../../assets/papers/editing/assign.png)

Itt láthatod az összes hozzájárulás listáját. Azok a hozzájárulások, ahol a jelenlegi típus szerkeszthető anyaga benyújtásra került, aktívak lesznek, az állapotuk _Felülvizsgálatra kész_ lesz.

![](../../assets/papers/editing/editable_list.png)

A _SZERKESZTŐ_ oszlop mutatja a jelenleg hozzárendelt szerkesztőt.

Szerkesztő hozzárendeléséhez egy szerkeszthetőhöz válassz ki egy hozzájárulást, és kattints a felső menüben a _Hozzárendel_ gombra. Hozzárendelhetsz egy szerkeszthetőt magadhoz is a _Magamhoz rendel_ gombra kattintva. Egy cikk lerendeléséhez válassz ki egy hozzájárulást és kattints az _Leválaszt_ gombra. Megjegyzendő, hogy egy szerkesztő lerendelése nem távolítja el az ő áttekintését a szerkeszthetőről.

Ezt a szerkeszthető anyagok listáját arra is használhatod, hogy gyorsan letöltsd több szerkeszthető anyag fájljait a _Fájlok letöltése_ segítségével. Több hozzájárulást kiválasztva letöltheted az összes fájljukat egyetlen zip archívumban.

Az osztályozási folyamat egyszerűsítése érdekében használhatod a felső menüben található szűrési lehetőségeket. Lehetőség van a hozzárendelt szerkesztő, a hozzájárulás kulcsszavai, a programkód és a szerkeszthető állapota szerinti szűrésre. Támogatott a keresés szöveg vagy azonosító alapján is.

![](../../assets/papers/editing/editable_list_filter.png)

A szerkeszthető lehetséges állapotai:

- Nem nyújtották be
- Felülvizsgálatra kész
- Elfogadva
- Elutasítva
- A beküldőnek változtatásokra van szüksége
- A beküldő megerősítésére van szükség

Amikor még nem nyújtottak be szerkeszthetőt, az állapot _Nem nyújtották be_. Beküldés után a szerkeszthető _Felülvizsgálatra kész_ lesz. Ebben a pontban egy szerkesztő hozzárendelhető, és elindul a felülvizsgálati folyamat.
Ha egy szerkeszthetőt elfogadnak vagy elutasítanak, a Szerkesztési folyamat befejeződik. Az elfogadott szerkeszthetők automatikusan közzéteszik a hozzájárulásban. A közzétett fájlok pontosan attól függenek, hogy a fájltípus beállításai között a fájltípust _közzétehetőként_ jelölték-e meg.

Ha egy szerkesztő úgy ítéli meg, hogy a cikk _A beküldőnek változtatásokra van szüksége_, a szerző képes lesz egy új változat benyújtására további felülvizsgálat céljából.
Egy szerkesztő maga is benyújthat egy új változatot - az állapot _A beküldő megerősítésére van szükség_ lesz, mivel az eredeti szerzőnek jóvá kell hagynia az új változatot.
Amint jóváhagyásra kerül, a szerkeszthető automatikusan elfogadásra kerül. Ha a szerző elutasítja a változtatásokat, akkor új változatot nyújthat be helyette.

Általában csak a szerkesztési menedzserek rendelhetnek hozzá cikkeket szerkesztőkhöz, azonban van lehetőség arra, hogy a szerkesztők maguk is hozzárendelhessék magukat a szerkeszthetőkhöz. Ez az opció a _Szerkesztői hozzárendelés_ szakaszban található a megadott szerkeszthető típus kezelési oldalán - _Engedélyezze a szerkesztőknek, hogy maguk rendeljék hozzá a szerkeszthetőket_.

![](../../assets/papers/editing/self_assign.png)

#### Jogosultságok

A Szerkesztési modul új szerepeket vezet be az Indico felhasználói számára. Itt bemutatjuk, hogy milyen engedélyek szükségesek a Szerkesztési modullal kapcsolatos leggyakoribb műveletek elvégzéséhez.

| Művelet                               | Szükséges engedélyek                                                 |
| ------------------------------------ | -------------------------------------------------------------------- |
| Egy szerkeszthető beküldése          | Absztrakt vagy hozzájárulás beküldői                                 |
| A szerkeszthető lista elérése        | Szerkesztők, szerkesztési menedzserek és esemény menedzserek         |
| Egy szerkeszthető bírálata/értékelése | Szerkesztők, szerkesztési menedzserek és esemény menedzserek (hozzá kell lenniük rendelve) |
| Szerkeszthetők hozzárendelése és beállítások kezelése | Szerkesztési menedzserek és esemény menedzserek                      |

### Szerkesztés szerzőként

A szerzők anyagokat (cikkeket, diákat és posztereket) nyújthatnak be a hozzájárulás oldalról az adott szerkeszthető típus kiválasztásával és a releváns fájlok feltöltésével.
Egy szerkeszthető beküldéséhez először kattints a _Saját hozzájárulások_ gombra a oldalsávban a _Saját konferencia_ alatt.

![](../../assets/papers/editing/my_contribs.png)

Itt kattints arra a hozzájárulásra, amelyhez anyagot szeretnél beküldeni, és görgetsd le a _Szerkesztési szakasz_ részhez. Ha a szakasz nem látható, akkor valószínűleg még nem nyitották meg a beküldéseket. A beküldések megnyitásával lehetőséged lesz beküldeni:

![](../../assets/papers/editing/submit_editable.png)

Ha több szerkeszthető típust engedélyeztek, először ki kell választanod a beküldeni kívánt anyag típusát a legördülő menüből:

![](../../assets/papers/editing/submit_multiple.png)

A megnyíló párbeszédablakban tölts fel minden szükséges fájlt, és erősítsd meg a _Beküldés_ gombra kattintva.
Ha több fájltípus engedélyezett, a párbeszédablak minden típushoz külön dobozt jelenít meg. A szükséges fájlkiterjesztések a dobozok bal felső sarkában láthatók, minden fájltípus neve alatt. Ha egy adott típusú fájl kötelező, a doboz jobb felső sarkában egy piros csillag ikon jelenik meg.

![](../../assets/papers/editing/upload_files.png)

Beküldés után nyomon követheted a benyújtásod állapotát a hozzájárulás oldalán a _Menj az idővonalra_ gombra kattintva.

![](../../assets/papers/editing/go_to_timeline.png)

Az idővonalon található minden frissítés a benyújtásoddal kapcsolatban kronológiai sorrendben.
Mint szerző, hozzászólhatsz a benyújtásodhoz és további fájlokat tölthetsz fel.

![](../../assets/papers/editing/timeline.png)

Ha figyelmeztetést látsz a felülvizsgálati feltételek teljesítetlenségéről, azt jelenti, hogy attól függően, hogy milyen fájlokat nyújtottál be már,
további fájlokra lehet szükség, amelyeket a konferencia szervezői határoztak meg, és lehet, hogy be kell őket szolgáltatnod.

![](../../assets/papers/editing/review_conditions_warning.png)

Ebben a pontban egy szerkesztő lesz hozzárendelve a benyújtásodhoz. Ők megjegyzéseket fűzhetnek a benyújtáshoz, vagy hagyhatnak egy felülvizsgálatot.
Egy felülvizsgálat egy javasolt intézkedéssel jár együtt. Egy szerkesztő vagy elfogadhatja, vagy elutasíthatja a benyújtásodat. Kérhetnek javításokat is, ebben az esetben a szerzőnek egy új, javított változatot kell feltöltenie. Végül, egy szerkesztő maga is feltölthet egy javított változatot. A szerző ekkor vagy elfogadhatja az új változatot, ami automatikusan jelzi a benyújtás elfogadását, vagy elutasíthatja. Ha a szerkesztő által javított változatot elutasítják, a szerző maga nyújthat be egy új változatot.

![](../../assets/papers/editing/needs_confirmation.png)

#### Ha a Kéziratlektorálási modul engedélyezve van

Ha a Kéziratlektorálási modul engedélyezve van, a kéziratlektorálási idővonalról is beküldhetsz egy cikket a Szerkesztési modulban, miután a cikket elfogadták a Kéziratlektorálási modulban.
A cikk beküldéséhez a Szerkesztési modulban kattints a _Beküldés szerkesztésre_ gombra, és válaszd ki a beküldeni kívánt fájlokat.

![](../../assets/papers/editing/submit_for_editing.png)

### Szerkesztés szerkesztőként

A szerkesztők minden felülvizsgálandó cikket megtalálhatnak a konferencia _Szerkesztés_ szekciójában.
Különböző alrészlegek láthatók (Cikkek, Diák, Poszterek) attól függően, hogy a szerkesztő tagja-e az adott szerkeszthető típus szerkesztői csapatának.

![](../../assets/papers/editing/editing_tab.png)

Az egyik hivatkozásra kattintva az adott típus szerkeszthetőinek listájához jutsz:

![](../../assets/papers/editing/editable_list_editor.png)

Mindig láthatod, hogy éppen melyik szerkeszthető típussal dolgozol, a lap bal felső részén lévő címben. A cím vagy _Cikkszerkesztés_, _Diákszerkesztés_ vagy _Poszterszerkesztés_ lesz.

A bal oldali sávban linkek találhatóak más kapcsolódó modulokhoz - Kéziratlektorálás és Absztraktok Felhívása, feltéve, ha ezeket engedélyezték a konferencián. A _Megjelenítés_ gombra kattintva visszatérsz a konferencia oldalára.

Jobb oldalon látható az összes hozzájárulás listája. Azok a hozzájárulások, amelyekhez már benyújtottak egy szerkeszthetőt, aktívak lesznek. A hozzájárulás nevére kattintva az adott szerkeszthető idővonalára jutsz. Mint szerkesztő, megjegyzéseket fűzhetsz bármelyik szerkeszthetőhöz, de csak azokat a szerkeszthetőket bírálhatod, amelyeket a szerkesztési menedzserek hozzád rendeltek. Minden szerkeszthetőhöz egy szerkesztő van hozzárendelve. A szerkesztőt a szerkeszthető lista _SZERKESZTŐ_ oszlopában találod. Minden szerkeszthetőnek van egy állapota (_ÁLLAPOT_) is, ami az adott szerkeszthető állapotát jelzi. A hozzájárulások, amelyekhez még nem nyújtottak be szerkeszthetőt, az _Nem nyújtották be_ állapotúak, míg a már benyújtott szerkeszthetővel rendelkező hozzájárulások _Felülvizsgálatra kész_ állapotúak.

![](../../assets/papers/editing/editable_list_example.png)

Hogy gyorsan megtaláld azokat a szerkeszthetőket, amelyek hozzád vannak rendelve, használhatod a szűrő funkciót. Kattints a _Szűrő_ gombra a jobb felső sarokban, kattints az _Szerkesztő_ lehetőségre, és válaszd ki a nevedet a listából.
A szűrés helyett kereshetsz a hozzájárulások között név vagy azonosító alapján is.

![](../../assets/papers/editing/editable_list_filter_editor.png)

Miután megtaláltál egy hozzád rendelt szerkeszthetőt, kattints a névre a szerkeszthető idővonalának megnyitásához:

![](../../assets/papers/editing/editor_judge.png)

Az idővonalon letöltheted a feltöltött fájlokat a _Zip letöltése_ gombra kattintva. Lehetőség van a fájlok egyenkénti letöltésére is, a fájlnevekre kattintva.
Miután az szerkesztő áttekintette a fájlokat, ítéletet hozhat a szerkeszthetőről. Négy cselekvési javaslat áll rendelkezésre az szerkesztő számára:

- Elfogad - A szerkeszthetőt elfogadják olyan állapotban, ahogy van, további változtatások nem lehetségesek, kivéve ha az ítéletet az szerkesztő visszaállítja. A szerkeszthető állapota _Elfogadva_.
- Elutasít - A szerkeszthetőt elutasítják. További változtatások nem lehetségesek, kivéve ha visszaállításra kerül. A szerkeszthető állapota _Elutasítva_.
- Változtatások kérése - A szerzőnek lehetősége lesz egy javított változat beküldésére, amit újra át kell tekinteni. A szerkeszthető állapota _A beküldőnek változtatásokra van szüksége_.
- Változtatások elvégzése - Az szerkesztő maga tölthet fel egy javított változatot. Az új változatot az eredeti szerzőnek kell jóváhagynia. A szerkeszthető állapota _A beküldő megerősítésére van szükség_.

!!! megjegyzés
    Mindig lehetőség van egy ítélet visszaállítására a visszavonás ikonra kattintva:
    ![](../../assets/papers/editing/reset_judgment.png)

#### Szerkeszthetők önálló hozzárendelése

Ha egy szerkesztési menedzser engedélyezte a szerkeszthetők önálló hozzárendelésének lehetőségét, akkor egy gomb jelenik meg a szerkeszthetők listája felett, ami vagy _Következő cikk megszerzése_, _Következő diák megszerzése_ vagy _Következő poszter megszerzése_ felirattal lesz ellátva attól függően, hogy éppen melyik szerkeszthető típust nézed. A gombra kattintva egy párbeszédablak jelenik meg a szerkeszthetők listájával. Ezen a listán keresztül hozzárendelheted magadhoz a szerkeszthetőket.

![](../../assets/papers/editing/get_next_slides.png)
![](../../assets/papers/editing/assign_self.png)

Lehetőség van arra is, hogy a szerkeszthető idővonalán keresztül hozzárendeld vagy leválaszd magad a szerkeszthetőről, az _Assign myself_ vagy _Unassign_ gombokra kattintva:

![](../../assets/papers/editing/assign_self_timeline.png)





