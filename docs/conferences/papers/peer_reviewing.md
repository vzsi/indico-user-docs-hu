# Kéziratlektorálás

### Bevezetés

Ez a rövid videó bemutatja az Indico lektorálási folyamatát és a lektorok valamint bírák szerepét:

<iframe width="576" height="360" frameborder="0" src="https://cds.cern.ch/video/2728255?showTitle=true" allowfullscreen></iframe>

A Kéziratlektorálás modul lehetővé teszi, hogy

- cikkeket nyújts be elfogadott [absztraktokhoz](../cfa.md),
- lektorálói és bírálói csapatokat állíts fel és rendelj hozzájuk cikkeket,
- cikkeket lektorálj és bírálj, valamint
- közzé tedd az elfogadott cikkeket.

!!! megjegyzés
    Ha nem vagy biztos abban, melyik modult használd, nézd meg a [bevezetőt](./introduction.md) az átfogó leíráshoz a Kéziratlektorálás és Szerkesztés modulokról.

Íme egy ábra, amely áttekintést nyújt a kéziratlektorálás munkafolyamatáról:

![](../../assets/papers/peer_reviewing/review_diagram.png)

A következő szakaszokban azt magyarázzuk el, hogyan használható a Kéziratlektorálás modul a szervezők, szerzők, lektorok és bírák szemszögéből.

### A kéziratlektorálás beállítása konferencia menedzser/szervezőként

#### A modul engedélyezése

Ahhoz, hogy elkezdd használni a Kéziratlektorálás modult, először engedélyezned kell azt.
A rendezvény kezelési oldaláról kattints a bal menüben a _Kéziratlektorálás_ fülre a _Munkafolyamatok_ alatt.
Végül kattints a _Modul engedélyezése_ gombra a Kéziratlektorálás modul engedélyezéséhez.

![](../../assets/papers/peer_reviewing/reviewing_enable_module.png)

A modul bármikor kikapcsolható a _Funkciók_ fülön az _Haladó beállítások_ alatt.

![](../../assets/papers/peer_reviewing/reviewing_disable_module.png)

Amint a modul engedélyezve van, új fülek jelennek meg a konferencia menüjében, amikor átváltasz a megjelenítési területre.

![](../../assets/papers/peer_reviewing/enabled_display_area.png)

#### Cikk sablon feltöltése

Ha a konferenciád megköveteli, hogy a cikkeknek különleges stílusban vagy elrendezésben kell lenniük, segítheted a cikk szerzőit azzal, hogy feltöltesz egy cikk sablont.
A szerzők ekkor letölthetik ezt a sablont a konferencia _Kéziratlektorálás_ füléről.

Cikk sablon feltöltéséhez válaszd a _Kéziratlektorálás_ fület a kezelési területen. Ezután kattints a _Kezelés_ gombra a _Cikk sablonok_ mellett.
Itt feltöltheted a sablonodat, adhatsz neki nevet és opcionálisan egy leírást. Több sablont is feltölthetsz, ha szeretnéd.

![](../../assets/papers/peer_reviewing/template_manage.png)

A sablon láthatóvá válik a konferencia megjelenítési területén:

![](../../assets/papers/peer_reviewing/template_uploaded.png)

#### Tartalmi és elrendezési lektorálás beállítása

A kéziratlektorálás modul lehetővé teszi a lektorok számára, hogy külön értékeljék egy cikk tartalmát és elrendezését.
Ezeket a folyamatokat engedélyezheted a _Kéziratlektorálás_ fülön. Alapértelmezés szerint csak a tartalmi lektorálási
folyamat engedélyezett.

![](../../assets/papers/peer_reviewing/reviewing_processes.png)

Emellett lehetőség van lektorálási határidő beállítására is mind a tartalmi, mind az elrendezési lektoráláshoz. Ha határidő van megadva, egy információs doboz jelenik meg a lektorálási területen,
amely tájékoztatja a lektorokat a határidőről. A határidő érvényesíthető is, ami megakadályozza a lektorálást a megadott dátum után.

Lektorálási határidő beállításához kattints a _Határidő_ gombra a megfelelő lektorálási folyamat mellett, amelyhez be szeretnéd állítani a határidőt:

![](../../assets/papers/peer_reviewing/reviewing_deadline_set.png)

Így néz ki a határidő a lektorok számára, amikor be van állítva:

![](../../assets/papers/peer_reviewing/reviewing_deadline_display.png)

A lektorok számára egyedi kérdéseket is megjeleníthetsz, amikor egy cikkről véleményt írnak.
Ez akkor lehet hasznos, ha a szerző elfogadásán/elutasításán kívül további információra van szükség a lektortól.
Háromféle kérdéstípus használható:

- Értékelés
- Igen/nem kérdés
- Szabad szöveg

Minden kérdésnek van neve, leírása és típustól függően további beállításai. Minden kérdést kötelezőként is be lehet állítani,
ami azt jelenti, hogy a lektor válaszolnia kell a kérdésre, mielőtt a lektorálást befejezné.

Lektorálási kérdések hozzáadásához kattints a megfelelő lektorálási folyamat melletti _Kérdések_ gombra.

![](../../assets/papers/peer_reviewing/questions.png)

Így néznek ki a különböző kérdések a lektor szemszögéből:

![](../../assets/papers/peer_reviewing/questions_display.png)

Az értékelési kérdések skálája (a minimum és maximum érték) minden kérdés esetében azonos, és a lektorálási beállításokban konfigurálható:

![](../../assets/papers/peer_reviewing/rating_scale.png)
![](../../assets/papers/peer_reviewing/rating_scale_set.png)

!!! megjegyzés
    Az értékelési skála minimum és maximum értékének megváltoztatása arányosan átskálázza az összes meglévő választ.

#### Cikkek bírálatának beállítása

A bírák számára az egyetlen kifejezetten elérhető beállítás a bírálati határidő, amely ugyanúgy működik, mint a korábban ismertetett lektorálási határidők.
Ha a határidő be van állítva, egy információs doboz jelenik meg a konferencia bírálati területén. Ha a határidő érvényesítve van, a bírák a határidő után nem bírálhatják el
a cikkeket.

![](../../assets/papers/peer_reviewing/judge_deadline_set.png)
![](../../assets/papers/peer_reviewing/judge_deadline_display.png)

#### Lektorálási beállítások

A lektorálási beállítások lehetővé teszik, hogy konfigurálj egy bejelentést, beállítsd az értékelési kérdések skáláját (az előző szakaszokban ismertetve) és kezeld az e-mail értesítéseket.
A bejelentést arra lehet használni, hogy egy üzenetet jeleníts meg a lektorálási oldalon a lektorok számára.

Az e-mail értesítések lehetővé teszik, hogy konfiguráld, ki és milyen körülmények között
kapjon e-mailt — például, akkor szeretnél-e egy bírót értesíteni, ha egy cikket lektoráltak. A leggyakoribb értesítések alapértelmezés szerint be vannak kapcsolva, de finomhangolhatod őket, ahogy szükséges. A lektorok és bírák kijelölését és hozzárendelését a cikkekhez a következő szakaszokban tárgyaljuk.

A lektorálási beállítások megnyitásához kattints a _Beállítások_ gombra a _Lektorálási beállítások_ mellett.

![](../../assets/papers/peer_reviewing/settings.png)

!!! megjegyzés
    A tartalmi és elrendezési lektorok oszlopai az e-mail értesítési beállításokban csak akkor láthatók, ha a megfelelő folyamat engedélyezve van.

Íme egy képernyőkép arról, hogy nézhet ki egy bejelentés.
A bejelentés szerkesztője támogatja az alapvető stílusokat Markdown segítségével. Képeket is beágyazhatsz egy link használatával.

![](../../assets/papers/peer_reviewing/announcement.png)

#### Lektorálói csapatok beállítása

Mielőtt cikkeket rendelnél lektorokhoz és bírákhoz, szükséges lektorálói csapatokat beállítani.
Ezek jelölik ki, kinek van joga lektorálni és/vagy bírálni egy cikket.

A kezdetekhez kattints a _Csapatok_ gombra a _Lektorálói csapatok_ mellett.

![](../../assets/papers/peer_reviewing/teams.png)

A megjelenő párbeszédablakból hozzáadhatsz cikkmenedzsereket, bírákat és tartalmi valamint elrendezési lektorokat. A cikkmenedzsereknek joga van kezelni a Kéziratlektorálás modul beállításait.
A cikkmenedzsereket az esemény _Védelem_ füléről is kezelheted, hozzáadva a _Cikkmenedzser_ engedélyt.

![](../../assets/papers/peer_reviewing/teams_setup.png)
![](../../assets/papers/peer_reviewing/paper_manager.png)

Miután beállítottad a csapatokat, hasznos lehet _kompetenciákat_ adni a lektoraidhoz és bíráidhoz.
A kompetenciák kulcsszavak, amelyek leírják a személy szakmai tudását.
Ezek a kulcsszavak segíthetnek a cikkmenedzsereknek a megfelelő lektor és/vagy bíró kiválasztásában egy cikkhez.

A kompetenciák kezeléséhez kattints a _Kompetenciák_ gombra a _Lektorálói csapatok_ mellett.

![](../../assets/papers/peer_reviewing/competences.png)
![](../../assets/papers/peer_reviewing/competences_add.png)

A lektorálói csapatok hasznosak lehetnek a lektoraid és bíráid e-mailben történő eléréséhez is.
Egyszerűen kattints a _Kapcsolat_ gombra és válaszd ki a kívánt címzetteket.

![](../../assets/papers/peer_reviewing/contact.png)

A _Levelek küldése_ gombra kattintva egy párbeszédablak nyílik meg, ahol megírhatod az e-mailedet.

#### Cikkek felhívásának engedélyezése

Ha eddig követted a dokumentációt, akkor most már készen állsz arra, hogy megnyisd a cikkek felhívását.
Azaz, lehetővé tedd a szerzők számára, hogy cikkeket nyújtsanak be lektorálásra.

A cikkek felhívásának megnyitásához vagy kattints a _Most indít_ gombra, ami azonnal megnyitja a felhívást, vagy kattints a _Ütemezés_ gombra,
és válaszd ki a felhívás kezdő- és záró dátumát.

![](../../assets/papers/peer_reviewing/cfp_open.png)

Amint a cikkek felhívása megnyílt, lehetőséged lesz arra is, hogy lezárd vagy újraütemezd azt ugyanott.

#### Cikkek hozzárendelése

A cikkek felhívásának megnyitásával és a cikkek beküldésével a cikkmenedzser feladata, hogy lektorokat és bírákat rendeljen a beküldött cikkekhez.
A lektorok és bírák csak azokon a cikkeken dolgozhatnak, amelyeket kifejezetten hozzájuk rendeltek.

A cikkek hozzárendelési oldalának megnyitásához kattints az _Cikkek hozzárendelése_ gombra a _Cikk hozzárendelés_ mellett.

![](../../assets/papers/peer_reviewing/assign.png)
![](../../assets/papers/peer_reviewing/list_of_papers.png)

Ez az oldal áttekintést nyújt az összes beküldött cikk állapotáról. Egy személy hozzárendeléséhez először válaszd ki a cikket, és kattints az
_Hozzárendel_ gombra a felső menüben. Válaszd ki a kívánt szerepet a legördülő menüből, és a megnyíló párbeszédablakban válaszd ki azokat a személyeket, akiket erre a szerepre hozzá kívánsz rendelni. Itt láthatod az egyes
személyek korábban megadott kompetenciáit is.

![](../../assets/papers/peer_reviewing/assign_judges.png)

Több személyt is hozzá lehet rendelni egyszerre több cikkhez. Ehhez egyszerűen válassz ki több cikket, és kövesd ugyanazt az eljárást.

Egy személy eltávolításához egy cikkről,
válaszd ki a cikket, és kattints az _Leválaszt_ gombra a felső menüben, majd válaszd ki a leválasztandó szerepet a legördülő menüből. A megnyíló párbeszédablakban válaszd ki az eltávolítandó személyt, és erősítsd meg a választásodat a _Leválaszt_ gombra kattintva.

![](../../assets/papers/peer_reviewing/unassign_judges.png)

#### Jogosultságok

A kéziratlektorálás modul új szerepeket vezet be az Indico felhasználói számára. Itt bemutatjuk, hogy milyen engedélyek szükségesek a Kéziratlektorálás modullal kapcsolatos leggyakoribb műveletek elvégzéséhez.

| Művelet                          | Szükséges engedélyek                                                 |
| -------------------------------- | -------------------------------------------------------------------- |
| Cikk beküldése                   | Absztrakt vagy hozzájárulás beküldői                                  |
| Cikk lektorálása                 | Cikklektorok és esemény menedzserek (a lektoroknak hozzá kell lenniük rendelve) |
| Cikk bírálata                    | Cikkbírák és esemény menedzserek (a bíráknak hozzá kell lenniük rendelve) |
| Cikkek hozzárendelése és beállítások kezelése | Cikk és esemény menedzserek                                         |

### Kéziratlektorálás cikk szerzőként

A tipikus konferencia munkafolyamatban az első lépés a cikk feltöltése előtt az absztrakt beküldése. Az absztrakt elfogadása után a szervezők automatikusan létrehoznak egy új hozzájárulást. Az összes hozzájárulásodat a _Saját hozzájárulások_ oldalon tekintheted meg.

![](../../assets/papers/peer_reviewing/contributions.png)

Amint az absztraktot elfogadták, beküldhetsz egy cikket, feltéve, hogy a cikkek felhívása nyitva van. Cikket a _Kéziratlektorálás_ oldalról nyújthatsz be, a _Cikk beküldése_ gombra kattintva. Ha több hozzájárulásod van, amelyhez cikket beküldhetsz, ki kell választanod egyet.

![](../../assets/papers/peer_reviewing/submit.png)
![](../../assets/papers/peer_reviewing/submit_select.png)

A cikket közvetlenül a hozzájárulás oldalról is beküldheted.

![](../../assets/papers/peer_reviewing/submit_from_contrib.png)

Miután beküldted a cikkedet, nyomon követheted annak előrehaladását a _Kéziratlektorálás_ oldalon a _Saját cikkeim_ alatt.

![](../../assets/papers/peer_reviewing/my_papers.png)

Ebben a szakaszban a lektorok véleményezhetik a cikkedet javaslatokkal és javasolhatják annak elfogadását, elutasítását vagy javítását. Mint szerző, minden rád vonatkozó tevékenységről e-mailben értesítést kapsz. Egy cikkbíró is kérhet javításokat a cikkeden, ebben az esetben feltölthetsz egy új verziót a cikkedből.

![](../../assets/papers/peer_reviewing/review.png)

Amint a cikket elfogadják, az a megfelelő hozzájárulásban lesz közzétéve.

![](../../assets/papers/peer_reviewing/accepted_papers.png)

### Kéziratlektorálás lektorként

Mint lektor, a feladatod a beküldött cikkek véleményezése és egy cselekvés javaslata - a cikk _elfogadása_, _elutasítása_ vagy _javításának_ kérése. A cikkbírák a visszajelzésed figyelembe veszik, amikor döntenek a cikkről.

Csak azokat a cikkeket véleményezheted, amelyeket kifejezetten hozzád rendeltek.
A véleményezendő cikkeket az esemény _Véleményezési területe_ alatt találod a _Véleményezésre váró cikkek_ alatt. A már áttekintett cikkek a _Véleményezett cikkek_ alatt jelennek meg.

![](../../assets/papers/peer_reviewing/papers_to_review.png)

Kérhetnek tőled tartalmi véleményezést, elrendezési véleményezést vagy mindkettőt. A pontos meghatározás az adott eseménytől és a szervezőktől függ, de általánosságban a tartalmi véleményezés a szöveggel, annak helyességével és teljességével foglalkozik, míg az elrendezési véleményezés a cikk stílusát és megjelenését ítéli meg, valamint hogy megfelel-e a konferencia irányelveinek.

Egy cikk véleményezéséhez először válassz ki egy cikket a listáról a cikk idővonalának megnyitásához. Az idővonal tetején letöltheted a cikk legújabb verzióját. Miután elolvastad a cikket és készen állsz a vélemény hozzáadására, kattints a _Véleményezés_ gombra.

![](../../assets/papers/peer_reviewing/make_a_review.png)

Ha tartalmi és elrendezési véleményt is kért tőled, egy legördülő menüt láthatsz, ahol ki kell választanod, melyik típusú véleményt szeretnéd hozzáadni.

![](../../assets/papers/peer_reviewing/choose_review_type.png)

Ezután ki kell választanod egy javasolt cselekvést - a cikk _elfogadása_ vagy _elutasítása_, vagy _javítás kérés_.
Ha a szervező extra véleményezési kérdéseket adott hozzá, meg kell válaszolnod őket ahhoz, hogy hozzáadhass egy véleményt.

![](../../assets/papers/peer_reviewing/propose_action.png)

A véleményedet később is szerkesztheted, amíg még nincs ítélet. Ezt a vélemény szerkesztés ikonjára kattintva teheted meg.

![](../../assets/papers/peer_reviewing/edit_review.png)

Megjegyzést is fűzhetsz egy cikkhez véleményezés nélkül. A megjegyzés láthatóságát úgy állíthatod be, hogy az például csak a bírák számára legyen látható. Ez hasznos lehet érzékeny témák megvitatásához anélkül, hogy a szerző látná.

![](../../assets/papers/peer_reviewing/comment.png)

Ha egy bíró javításokat kér, a lektorok véleményezhetik a javított cikket.

### Kéziratlektorálás bíróként

A bírók munkafolyamata nagymértékben hasonlít a lektorokéhoz. A bírák csak azokat a cikkeket bírálhatják el, amelyeket a cikkmenedzserek hozzájuk rendeltek.
A bírálandó cikkek listája a _Bírálati területen_ található.

![](../../assets/papers/peer_reviewing/judging_area.png)

A cikkbíráknak van végső szavuk abban, hogy egy cikk elfogadásra kerül-e. Elfogadhatják vagy elutasíthatják a cikket, vagy kérhetik annak javítását. Ha javítást kérnek,
a cikk szerzője beküldhet egy új verziót, amelyet ismét el kell bírálni.
Fontos megjegyezni, hogy egy cikket csak egy bíró ítélhet meg.

Mielőtt ítéletet hoznál, győződj meg róla, hogy a lektoroknak volt lehetőségük áttekinteni a cikket. A hozzárendelt tartalmi és elrendezési lektorokat a _Bírálati területen_ láthatod.

Az ítéleteket vissza lehet állítani az ítélet dobozban található _Ítélet visszaállítása_ ikonra kattintva:

![](../../assets/papers/peer_reviewing/reset_judgment.png)

Mint bíró, hozzászólhatsz is egy cikkhez ítélet hozzáadása előtt.

!!! megjegyzés
    Mind a véleményezés, mind a bírálat esetében határidőt állíthatnak be, amely után nem lehet cikkeket véleményezni vagy bírálni. Ha határidő van megadva, azt a Véleményezési és Bírálati területeken láthatod.
    ![](../../assets/papers/peer_reviewing/reviewing_deadline_display.png)
