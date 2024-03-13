# Szerkesztés

### Bevezetés

Ez a rövid videó az Indico szerkesztési folyamatát mutatja be:

<iframe width="576" height="360" frameborder="0" src="https://cds.cern.ch/video/2728257?showTitle=true" allowfullscreen></iframe>

A Szerkesztés modul a Szakmai bírálat modulhoz hasonlóan egy olyan munkafolyamatot biztosít, amelynek során a szerzők beküldik a dolgozatokat, amelyeket ezt követően átnéznek és/vagy javítanak.
Konkrétan a modul lehetővé teszi, hogy

- dolgozatok, poszterek és diák beküldését felülvizsgálatra,
- szerkesztőcsoportot állíthat fel, és szerkesztőket rendelhet a szerkeszthető anyagokhoz,
- a szerkeszthető anyagok áttekintését és elbírálását, valamint
- az elfogadott anyagok közzétételét.

!!!! megjegyzés
    Ha nem biztos benne, hogy melyik modult kell használnia, nézze meg a [introduction](./introduction.md) a Peer Reviewing és Editing modulok magasabb szintű leírását.

Itt egy folyamatábra, amely a szerkesztési munkafolyamat áttekintését mutatja:

![](../../assets/papers/editing/editing_diagram.png)

A következő szakaszok a Szerkesztés modul használatát ismertetik a szervezők, a szerzők és a dolgozat bírálók szemszögéből.

### A Szerkesztés modul konfigurálása menedzserként/szervezőként

#### A modul engedélyezése

A Szerkesztés modul használatának megkezdéséhez először engedélyeznie kell azt.
Az eseménykezelő oldalon kattintson a bal oldali menüben, a _Munkafolyamatok_ alatt található _Szerkesztés_ fülre.
A Szerkesztés modul engedélyezéséhez kattintson a _Modul engedélyezése_ gombra.

![](../../assets/papers/editing/enable.png)

A modul bármikor letiltható a _Features_ fülön a _Advanced options_ alatt.

![](../../assets/papers/editing/disable.png)

Ha a modul engedélyezve van, a konferencia menüjében új lapok jelennek meg a váltáskor
a megjelenítési területre való áttéréskor.

![](../../assets/papers/editing/editing_enabled.png)

#### A Szerkesztés modulhoz való hozzáférés engedélyezése

Alapértelmezés szerint az eseménykezelők hozzáférhetnek a Szerkesztés modul kezelési területéhez.
Ezen kívül bárki, aki rendelkezik a _Szerkesztéskezelő_ jogosultsággal, szintén kezelheti a modult.
Ezt a jogosultságot az esemény _Védelem_ oldalán lehet beállítani.

![](../../assets/papers/editing/editing_manager.png)

#### Szerkeszthető típusok beállítása

Mint korábban utaltunk rá, a Peer Reviewing modullal ellentétben a Szerkesztés modulban nem csak előadások, hanem diák és poszterek beküldését is lehetővé teszi.
Ezeket szerkeszthető típusoknak nevezzük, és beállíthatja, hogy melyiket engedélyezze. A szerzők csak akkor tudnak anyagot benyújtani az adott típushoz, ha az engedélyezve van.
Alapértelmezés szerint csak a _paper_ szerkeszthető típus van engedélyezve.

További szerkeszthető típusok engedélyezéséhez először navigáljon a kezelési terület _Szerkesztés_ oldalára. Ezután kattintson a _Szerkeszthető típusok bekapcsolása_ gombra:

![](../../assets/papers/editing/editable_types.png)

Most már átkapcsolhatja az egyes szerkeszthető típusokat:

![](../../assets/papers/editing/editable_types_toggle.png)

Ha végzett, kattintson a _Save_ gombra a módosítások elmentéséhez.

Vegye figyelembe, hogy az egyes szerkeszthető típusok beállításai különállóak. Ezeket a szerkeszthető típus mellett található _Manage_ gombra kattintva tudja megnyitni:

![](../../assets/papers/editing/editable_types_settings.png)

Ezt a beállítások oldalt fogja látni:

![](../../assets/papers/editing/editable_types_settings_view.png)

A felirat megmondja, hogy éppen milyen szerkeszthető típust szerkesztesz. Ebben az esetben a papírok beállításait szerkesztjük.

A következő szakaszokban az ezen az oldalon található különböző beállításokat ismertetjük. 

#### Fájltípusok kezelése

Ugyanebből a fenti beállítások menüből a _Fájltípusok_ mellett található _Configure_ gombra kattintva kezelheti az engedélyezett fájltípusokat:

![](../../assets/papers/editing/file_types.png)

Alapértelmezés szerint a PDF kerül hozzá alapértelmezett fájltípusként.

![](../../assets/papers/editing/pdf.png)

Ez azt jelenti, hogy a szerzők alapértelmezés szerint csak PDF fájlokat küldhetnek be ehhez a szerkeszthető típushoz. Ha más fájltípusokat, például további adatokat tartalmazó CSV-fájlt szeretne engedélyezni, kattintson az oldal alján található _Add new a file type_ gombra.

![](../../assets/papers/editing/add_file_type.png)

Ekkor egy párbeszédablak nyílik meg több lehetőséggel:

![](../../assets/papers/editing/create_file_type.png)

A _Filename sablon_ egy opcionális fájlnévminta. Ezzel biztosíthatja, hogy a beküldött fájlnevek megfeleljenek a megadott mintának. Például az összes CSV fájl végződését
"\_data"-ra végződik, és az összes PDF-fájl "\_paper"-re végződik. Opcionálisan megadhatja a megengedett fájlkiterjesztéseket is, például a CSV-fájlok esetében a ".csv", a PDF-fájlok esetében pedig a ".pdf" kiterjesztést. A párbeszédpanel alján van még néhány opció, amelyet átkapcsolhat.

- Fájl szükséges - az adott szerkeszthető (papír, poszter vagy diák) benyújtásakor szükséges-e ez a fájl.
- Több fájl - lehetővé teszi több fájl feltöltését ugyanahhoz a szerkeszthető típushoz, például több PDF-fájl feltöltését.
- Publishable - szabályozza, hogy az adott típusú fájlokat közzé kell-e tenni a megfelelő hozzájárulásban. Ez abban az esetben hasznos, ha egyes fájloknak csak a szerkesztők számára kell láthatónak lenniük.

Ha kész, kattintson a _Submit_ gombra az új fájltípus létrehozásához. Ha később módosítani szeretné a fájltípust, a mellette lévő szerkesztés ikonra kattintva megteheti. Egy fájltípus törlése mindaddig lehetséges, amíg nem töltöttek fel az adott típusú fájlt, és a fájlra nem hivatkoznak a felülvizsgálati feltételek (a következő szakaszban ismertetjük).

![](../../assets/papers/editing/edit_file_type.png)

#### "Felülvizsgálatra kész" feltételek beállítása

Abban az esetben, ha összetett, fájltípusokon alapuló benyújtási követelményei vannak, előnyös lehet felülvizsgálati feltételek beállítása. Egy példa arra, amikor a felülvizsgálati feltételek hasznosak lehetnek, ha egy konferencia megköveteli a szerzőktől, hogy vagy PDF- vagy Word-dokumentumot nyújtsanak be egy CSV-fájlt csatolva. Mivel azt szeretné, hogy a szerzők választhassanak a PDF és a Word között, nem teheti kötelezővé egyik fájltípust sem. Azt azonban továbbra is szeretné, hogy legalább az egyiket be kelljen nyújtani. A felülvizsgálati feltételek lehetővé teszik az ehhez hasonló összetett feltételek egyszerű kifejezését.

Vegye figyelembe, hogy ezek a feltételek nem fogják egyenesen megakadályozni a szerzőket abban, hogy hiányos beadványokat töltsenek fel, hanem a szerkeszthető idővonal figyelmeztetést fog megjeleníteni, amíg a felülvizsgálati feltételek nem teljesülnek.

Új feltétel hozzáadásához kattintson a kiválasztott szerkeszthető típus kezelőlapján a _Készenlétben az átnézési feltételek_ mellett a _Konfigurálás_ gombra.

![](../../assets/papers/editing/review_condition_btn.png)

A következő oldalon kattintson az _Create new file type condition_ gombra.

![](../../assets/papers/editing/review_condition.png)

A legördülő listából válassza ki a korábban meghatározott fájltípusokat. Ha egynél több fájltípust választ ki, akkor a kiválasztott fájltípusok kombinációja lesz kötelező.
Ha például PDF és CSV formátumot választ, a szerzőknek mindkét típusból legalább egy-egy fájlt kell feltölteniük.

Ha kiválasztotta az első feltételt, kattintson a pipa ikonra a megerősítéshez:

![](../../assets/papers/editing/review_condition_create.png)

Példánk befejezéseként hozzáadunk egy második feltételt egy Word dokumentumhoz és egy CSV fájlhoz. A végső állapotnak így kell kinéznie:

![](../../assets/papers/editing/review_condition_final.png)

Ezek a példafeltételek azt jelentik, hogy a szerzőknek egy CSV-fájlt kell benyújtaniuk egy PDF- vagy egy Word-dokumentummal együtt.
Ha a feltételek nem teljesülnek, a szerzők és a szerkesztők egyaránt figyelmeztetést látnak a szerkeszthetőség idővonalán:

![](../../assets/papers/editing/unmet_conditions.png)

#### A szerkesztőcsoport beállítása

A Szerkesztés modul lehetővé teszi egy szerkesztői csapat beállítását. Ez a funkció hasonló a Peer Reviewing modulban található bírálócsapatokhoz.
Csak a szerkesztőcsapathoz hozzáadott felhasználók tekinthetik meg a szerkeszthető anyagok listáját és vizsgálhatják felül azokat.
A Peer Reviewing modullal ellentétben itt nincs elkülönítés a bírálók és a bírálók között - a szerkesztők mindkettő szerepét betöltik.

A szerkesztőcsapat szerkeszthető típusonként különálló, ami azt jelenti, hogy például a papírok szerkesztőcsapata különbözik a poszterek vagy diák szerkesztőcsapatától.

Ha szerkesztőt szeretne felvenni a szerkesztőcsapatba, kattintson a _Szerkesztőcsapat_ mellett található _Szerkesztőcsapat kezelése_ gombra:

![](../../assets/papers/editing/team.png)

Itt adja hozzá a felhasználókat, és kattintson a _Submit_ gombra. Ugyanezt az eljárást használhatja a szerkesztők eltávolítására is.

![](../../assets/papers/editing/team_add.png)

Miután létrehozta a szerkesztői csapatot, szükség esetén most már könnyedén kapcsolatba léphet az összes szerkesztővel e-mailben. Kattintson a Kapcsolat_ gombra,
válassza ki a címzetteket, majd kattintson az _Emailek küldése_ gombra, amely megnyit egy párbeszédablakot, ahol beírhatja az e-mailt.

![](../../assets/papers/editing/team_contact.png)

A Szerkesztés modulban a szerkesztők is privátan tarthatók.
Ez azt jelenti, hogy a szerzők nem láthatják a beadványaikat véleményező és kommentáló szerkesztők kilétét.

A szerkesztők alapértelmezés szerint láthatóak. Ha el akarja rejteni őket, kapcsolja be a _Szerkesztői csapat tagjainak anonimizálása_ kapcsolót a _Szerkesztői csapat_ mellett:

![](../../assets/papers/editing/team_anonymous.png)

#### Beküldés és szerkesztés megnyitása

Miután befejezte a Szerkesztés modul konfigurálását, megnyithatja a beadványokat és a szerkesztést. Ez lehetővé teszi a szerzők számára a szerkeszthető anyagok beküldését, a bírálók számára pedig azok átnézését.
Az egyes szerkeszthető típusok (dolgozatok, diák és poszterek) egymástól függetlenül megnyithatók és bezárhatók. Mind a beadványok, mind a bírálat a szerkeszthető típus kezelőoldaláról nyitható meg a _Start now_ gombra kattintva:

![](../../assets/papers/editing/submissions.png)

A beadványok vagy a felülvizsgálat lezárásához egyszerűen kattintson a _Bezárás most_ gombra.

#### Szerkeszthetőségek hozzárendelése

A szerkesztők csak azokat a szerkeszthetőségeket vizsgálhatják felül, amelyeket a szerkesztésirányítók osztottak ki számukra. A szerkesztők dolgozathoz való hozzárendeléséhez kattintson a _List_ gombra a _Szerkesztők hozzárendelése_ szakaszban a kiválasztott szerkeszthető típusnál.

![](../../assets/papers/editing/assign.png)

Itt megjelenik az összes hozzászólás listája. Azok a hozzájárulások, amelyekhez az aktuális (az oldal alcímében látható) szerkeszthető típushoz már beküldött hozzájárulást, aktívak lesznek, és az állapotukra az lesz írva, hogy _Készen áll az ellenőrzésre_.

![](../../assets/papers/editing/editable_list.png)

A _EDITOR_ oszlopban az aktuálisan kijelölt szerkesztő látható.

Ha szerkesztőt szeretne hozzárendelni egy szerkeszthetőséghez, jelölje ki a hozzájárulást, és kattintson a felső menüben a _Assign_ (Hozzárendelés) gombra. Egy szerkeszthetőt saját magához is hozzárendelhet, ha a _Assign to myself_ (Hozzárendelés magamhoz) gombra kattint. Egy dolgozat hozzárendelésének feloldásához jelölje ki a hozzájárulást, és kattintson a _Unassign_ (Hozzárendelés feloldása) gombra. Vegye figyelembe, hogy egy szerkesztő hozzárendelésének feloldása nem távolítja el a szerkeszthetőségből a véleményét.

A szerkeszthetők ezen listája arra is használható, hogy a _Fájlok letöltése_ segítségével gyorsan letöltse több szerkeszthető anyagot. Több hozzászólás kiválasztásával az összes fájljukat letöltheti egy zip-archívumban.

A hozzárendelési folyamat egyszerűsítése érdekében használhatja a felső menüben található szűrési lehetőségeket. Lehetőség van a hozzárendelt szerkesztő, a hozzájárulás kulcsszavai, a programkód és a szerkeszthetőség állapota alapján szűrni. Támogatott a karakterlánc vagy azonosító szerinti keresés is.

![](../../assets/papers/editing/editable_list_filter.png)

A szerkeszthető listák lehetséges státuszai a következők:

- Nincs beküldve
- Felülvizsgálatra olvasva
- Elfogadva
- Elutasítva
- A benyújtó változtatásokat igényel
- A benyújtó megerősítésére van szükség

Ha még nem küldtek be szerkeszthető anyagot, az állapot _Nem küldték be_. A benyújtás után a szerkeszthető anyag _Készen áll a felülvizsgálatra_ státuszba kerül. Ekkor ki lehet jelölni egy szerkesztőt, és megkezdődik a felülvizsgálati folyamat.
Ha egy szerkeszthető anyagot elfogadnak vagy elutasítanak, a szerkesztési folyamat befejeződik. Az elfogadott szerkeszthetők automatikusan megjelennek a hozzájárulásban. Hogy pontosan mely fájlok kerülnek közzétételre, az attól függ, hogy a fájltípus beállításaiban _kiadható_ként lett-e beállítva.

Ha egy szerkesztő úgy ítéli meg, hogy egy dolgozat _Elküldendő változtatásokra szorul_, a szerzőnek lehetősége van egy új változatot benyújtani további felülvizsgálatra.
A szerkesztő maga is benyújthat új verziót - a státusz _Needs submitter approval_ (benyújtó jóváhagyása szükséges) lesz, mivel az eredeti szerzőnek jóvá kell hagynia az új verziót.
A jóváhagyást követően a szerkeszthető automatikusan elfogadásra kerül. Ha a szerző elutasítja a változtatásokat, helyette maga is benyújthat egy új verziót.

Normális esetben csak a szerkesztési menedzserek oszthatnak ki dolgozatokat szerkesztőknek, azonban van egy olyan lehetőség, amely lehetővé teszi a szerkesztők számára, hogy saját maguk oszthassanak ki dolgozatokat. Az opció a menedzsmentben található
oldalon az adott szerkeszthető típushoz a _Szerkesztők hozzárendelése_ szakaszban - _Allow editors to self-assigned editables_.

![](../../assets/papers/editing/self_assign.png)

#### Jogosultságok

A Szerkesztés modul új szerepköröket hoz létre, amelyekkel az Indico felhasználók rendelkezhetnek. Itt adunk egy listát arról, hogy milyen jogosultságok szükségesek ahhoz, hogy elvégezhessék
a Szerkesztés modulhoz kapcsolódó leggyakoribb műveletek elvégzéséhez.

| Művelet | Szükséges engedélyek |
| ------------------------------------ | -------------------------------------------------------------------- |
| Szerkeszthető | Absztrakt vagy hozzájárulás benyújtása |
| Hozzáférés a szerkeszthető listához | Szerkesztők, szerkesztéskezelők és eseménykezelők |
| Szerkeszthető | Szerkesztők, szerkesztésvezetők és eseményvezetők bírálata/áttekintése (ki kell jelölni) | Szerkesztők, szerkesztésvezetők és eseményvezetők |
| Szerkeszthetők hozzárendelése és beállítások kezelése | Szerkesztésvezetők és eseményvezetők |

### Szerkesztés szerzőként

A szerzők a hozzájárulási oldalon nyújthatnak be anyagokat (előadásokat, diákat és posztereket) a szerkeszthető típus kiválasztásával és a megfelelő fájlok feltöltésével.
Szerkeszthető anyag beküldéséhez először kattintson az oldalsávban, a _Konferenciám_ alatt található _A hozzájárulásaim_ menüpontra.

![](../../assets/papers/editing/my_contribs.png)

Itt kattintson arra a hozzászólásra, amelyhez anyagot szeretne beküldeni, és görgessen le a _Szerkesztés_ részhez. Ha a szakasz nem látható, akkor valószínűleg még nem nyitották meg a beadványokat. Ha a beadványok megnyíltak, meg kell jelennie a beküldés lehetőségének:

![](../../assets/papers/editing/submit_editable.png)

Ha több szerkeszthető típus van engedélyezve, akkor először ki kell választania a legördülő listából, hogy milyen típusú anyagot szeretne beküldeni:

![](../../assets/papers/editing/submit_multiple.png)

A megnyíló párbeszédablakban töltse fel az összes szükséges fájlt, majd erősítse meg a _Submit_ gombra kattintva.
Ha több fájltípus engedélyezett, a párbeszédpanel mindegyikhez egy-egy mezőt jelenít meg. A szükséges fájlkiterjesztések minden egyes doboz bal felső sarkában a fájltípus neve alatt szerepelnek. Ha egy adott fájltípusra van szükség, a doboz jobb felső sarkában egy piros csillag ikon jelenik meg.

![](../../assets/papers/editing/upload_files.png)

A beküldés után a hozzájárulás oldaláról a _Go to timeline_ gombra kattintva nyomon követheti a beküldés előrehaladását.

![](../../assets/papers/editing/go_to_timeline.png)

Az idővonalon a beadványával kapcsolatos összes frissítést időrendi sorrendben találja.
Szerzőként megjegyzéseket fűzhet beadványához, és további fájlokat tölthet fel.

![](../../assets/papers/editing/timeline.png)

Ha a nem teljesített felülvizsgálati feltételekről szóló figyelmeztetést lát, az azt jelenti, hogy a már benyújtott fájloktól függően,
a konferencia szervezői által meghatározottak szerint további fájlokra lehet szükség, és előfordulhat, hogy ezeket kérik Öntől.

![](../../assets/papers/editing/review_conditions_warning.png)

Ezen a ponton egy szerkesztőt jelölnek ki az Ön beadványához. Ők vagy hozzászólhatnak a beadványhoz, vagy véleményt hagyhatnak róla.
Az értékeléshez egy javasolt intézkedés is tartozik. A szerkesztő elfogadhatja vagy elutasíthatja a beadványát. Kérhet javításokat is, amely esetben a szerző
egy új, javított változatot kell feltöltenie. Végül a szerkesztő maga is benyújthat egy javított változatot. A szerző ezután vagy elfogadja az új változatot, ami automatikusan elfogadottnak jelöli a beadványt, vagy elutasítja azt. Ha a szerkesztő verziója elutasításra kerül, a szerző maga is benyújthat egy új verziót.

![](../../assets/papers/editing/needs_confirmation.png)

#### Ha a Peer Reviewing modul engedélyezve van.

Ha a Peer Reviewing modul engedélyezve van, akkor a Peer Reviewing idővonalról is beadhat egy dolgozatot, miután a dolgozatot elfogadták a Peer Reviewing modulban.
A dolgozat benyújtásához a Szerkesztés modulban kattintson a _Szerkesztésre benyújtás_ gombra, és válassza ki a benyújtani kívánt fájlokat.

![](../../assets/papers/editing/submit_for_editing.png)

### Szerkesztőként történő szerkesztés

A szerkesztők a konferencia _Szerkesztés_ szekciójában találják meg az összes átnézendő dolgozatot.
Különböző alszekciókat (Papers, Slides, Posters) lát attól függően, hogy az adott szerkeszthető típushoz tartozó szerkesztői csoport tagja-e.

![](../../assets/papers/editing/editing_tab.png)

A linkek valamelyikére kattintva a kiválasztott típus szerkeszthetőségeinek listájára juthat:

![](../../assets/papers/editing/editable_list_editor.png)

Az oldal bal felső részén található cím alapján mindig láthatja, hogy melyik szerkeszthető típussal dolgozik. Ez vagy a _Papírszerkesztés_, _Fóliák szerkesztése_ vagy _Poszterszerkesztés_ feliratot fogja tartalmazni.

A bal oldalsáv más kapcsolódó modulokra - Peer Reviewing és Call for Abstracts - mutató linkeket tartalmaz, feltéve, hogy a konferencia számára engedélyezve vannak. A _Megjelenítés_ gombra kattintva visszatérhet a konferencia oldalára.

A jobb oldalon az összes hozzászólás listája látható. Azok a hozzájárulások, amelyek már rendelkeznek szerkeszthető beküldött anyaggal, aktívak lesznek. A hozzájárulás nevére kattintva a szerkeszthető idővonalra jut. Szerkesztőként bármely szerkeszthetőhöz megjegyzéseket hagyhat, de csak azokat a szerkeszthetőket tekintheti át, amelyeket a szerkesztésért felelősök kijelöltek Önnek. Minden szerkeszthetőhöz csak egy szerkesztő van hozzárendelve. A szerkesztő a szerkeszthető listában a _SZERZŐ_ oszlopban szerepel. Minden szerkeszthetőnek van egy státusza is (_STATUS_ oszlop), amely a szerkeszthető állapotát jelzi. A szerkeszthetőség nélküli hozzájárulások státusza _Nem benyújtott_, míg a benyújtott szerkeszthetőséggel rendelkező hozzájárulások státusza _Készen áll a felülvizsgálatra_.

![](../../assets/papers/editing/editable_list_example.png)

Ha gyorsan meg szeretné tudni, hogy mely szerkeszthetőségek vannak hozzárendelve, használhatja a szűrőfunkciót. Kattintson a _Szűrő_ gombra a jobb felső sarokban, majd kattintson a _Szerkesztőre_, és válassza ki a nevét a listából.
Szűrés helyett a hozzájárulásokat név vagy azonosító alapján is keresheted.

![](../../assets/papers/editing/editable_list_filter_editor.png)

Ha megtalálta a hozzárendelt szerkeszthetőt, kattintson a nevére a szerkeszthető idővonal megnyitásához:

![](../../assets/papers/editing/editor_judge.png)

Az idővonalban a _Download zip_ gombra kattintva letöltheti a feltöltött fájlokat. A fájlokat egyenként is le lehet tölteni a fájlnevekre kattintva.
Miután a szerkesztő átnézte a fájlokat, megítélheti a szerkeszthetőséget. A szerkesztő négyféle műveletet javasolhat:

- Elfogadás - A szerkeszthetőséget úgy fogadjuk el, ahogy van, további módosításra nincs lehetőség, kivéve, ha a szerkesztő visszaállítja a bírálatot. A szerkeszthető státusza _Accepted_ (Elfogadva).
- Elutasítás - A szerkeszthető anyag elutasításra kerül. További módosítások nem lehetségesek, kivéve, ha visszaállítják. A szerkeszthetőség állapota _Elutasítva_.
- Request changes - A szerzőnek lehetősége lesz egy javított változat beküldésére, amelyet felül kell vizsgálni. A szerkeszthetőség állapota _Elküldő változtatásokat igényel_.
- Módosítások elvégzése - A szerkesztő maga is feltölthet egy javított változatot. A módosításokat ezután az eredeti szerzőnek jóvá kell hagynia. A szerkeszthetőség állapota _Elküldő jóváhagyása szükséges_.

!!! megjegyzés
    Mindig lehetőség van az ítélet visszaállítására a visszaállítás ikonra kattintva:
    ![](../../assets/papers/editing/reset_judgment.png)

#### Önálló szerkeszthetőségek kiosztása

Ha egy szerkesztéskezelő engedélyezte a szerkeszthetőségek önkiosztásának lehetőségét, akkor a szerkeszthetőségek listája felett megjelenik egy gomb, amely a következő feliratot tartalmazza: _Következő dolgozat_, _Következő diák_ vagy _Következő poszter_ attól függően, hogy éppen melyik szerkeszthető típust nézi. A gombra kattintva egy párbeszédablak jelenik meg a szerkeszthető elemek listájával. Ezt a listát használhatja a szerkeszthetőségek keresésére és hozzárendelésére.

![](../../assets/papers/editing/get_next_slides.png)
![](../../assets/papers/editing/assign_self.png)

A szerkeszthető idővonalban a _Assign myself_ (magam hozzárendelése) vagy a _Unassign_ (magam hozzárendelése megszüntetése) gombra kattintva szintén lehetőség van a szerkeszthető idővonalban lévő szerkeszthetőkhöz hozzárendelni és feloldani a hozzárendelést:

![](../../assets/papers/editing/assign_self_timeline.png)
