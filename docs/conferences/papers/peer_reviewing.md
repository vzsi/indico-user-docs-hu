# Paper Peer Reviewing

### Bevezetés

Ez a rövid videó elmagyarázza a szakmai bírálati folyamatot, valamint a bíráló és a bíráló szerepét az Indicóban:

<iframe width="576" height="360" frameborder="0" src="https://cds.cern.ch/video/2728255?showTitle=true" allowfullscreen></iframe>

A szakértői értékelés modul lehetővé teszi, hogy

- Elfogadott [absztraktok] (../cfa.md) benyújtását,
- bíráló- és bírálócsoportok felállítását, valamint a dolgozatokhoz való hozzárendelésüket,
- a dolgozatok bírálatát és elbírálását, valamint
- az elfogadott dolgozatok közzétételét.

!!! Megjegyzés
    Ha nem biztos benne, hogy melyik modult kell használnia, nézze meg a [introduction](./introduction.md) a Peer Reviewing és Editing modulok magasabb szintű leírását.

Itt egy folyamatábra, amely a szakértői bírálati munkafolyamat áttekintését mutatja be:

![](../../assets/papers/peer_reviewing/review_diagram.png)

A következő szakaszok a Peer Reviewing modul használatát ismertetik a szervezők, a szerzők, a dolgozat bírálók és a bírálók szemszögéből.

### A szakértői bírálat beállítása konferenciamenedzserként/szervezőként

#### A modul engedélyezése

Ahhoz, hogy elkezdhesse használni a Peer Reviewing modult, először engedélyeznie kell azt.
Az eseménykezelő oldalon kattintson a bal oldali menüben a _Munkafolyamatok_ alatt található _Peer Reviewing_ fülre.
Végül kattintson a _Modul engedélyezése_ gombra a Peer Reviewing modul engedélyezéséhez.

![](../../assets/papers/peer_reviewing/reviewing_enable_module.png)

A modul bármikor letiltható a _Features_ fülön a _Advanced options_ alatt.

![](../../assets/papers/peer_reviewing/reviewing_disable_module.png)

Ha a modul engedélyezve van, a konferencia menüjében új lapok jelennek meg a váltáskor
a megjelenítési területre.

![](../../assets/papers/peer_reviewing/enabled_display_area.png)

#### Papírsablon feltöltése

Ha a konferenciája megköveteli, hogy a dolgozatoknak meghatározott stílusúak vagy elrendezésűek legyenek, akkor egy papírsablon feltöltésével segítheti a papírok szerzőit.
A szerzők ezt követően letölthetik ezt a sablont a konferencia _Paper Peer Reviewing_ lapjáról.

A sablon feltöltéséhez válassza a kezelési területen a _Peer Reviewing_ lapot. Ezután kattintson a _Papírsablonok_ mellett található _Manage_ gombra.
Itt feltöltheti a sablonját, nevet és opcionálisan leírást adhat neki. Ha szeretné, több sablont is feltölthet.

![](../../assets/papers/peer_reviewing/template_manage.png)

A sablon láthatóvá válik a konferencia megjelenítési területén:

![](../../assets/papers/peer_reviewing/template_uploaded.png)

#### Tartalom és elrendezés áttekintésének beállítása

A szakértői bírálat modul lehetővé teszi, hogy a bírálók külön-külön bírálják el a dolgozat tartalmát és elrendezését.
A _Paper Peer Reviewing_ fülön engedélyezheti az egyik vagy mindkét folyamatot. Alapértelmezés szerint csak a tartalmi bírálat
folyamat van engedélyezve.

![](../../assets/papers/peer_reviewing/reviewing_processes.png)

Ezen kívül lehetőség van a tartalmi és az elrendezési bírálatra is felülvizsgálati határidőt beállítani. Ha határidő van beállítva, akkor egy információs mező jelenik meg az átnézési területen
amely tájékoztatja a bírálókat a határidőről. A határidő érvényesíthető is, ami szintén megakadályozza a megadott dátum utáni felülvizsgálatot.

A felülvizsgálati határidő beállításához kattintson a _Határidő_ gombra azon felülvizsgálati folyamat mellett, amelyre vonatkozóan a határidőt be szeretné állítani:

![](../../assets/papers/peer_reviewing/reviewing_deadline_set.png)

Ezt látják a bírálók a határidő beállításakor:

![](../../assets/papers/peer_reviewing/reviewing_deadline_display.png)

A bírálóknak egyéni kérdéseket is megjeleníthetnek, amikor egy dolgozatról véleményt hagynak.
Ez akkor lehet hasznos, ha a dolgozat elfogadásán/elutasításán kívül további információkra is szükség van a bírálótól.
A kérdések három típusa használható:

- A minősítés
- Igen/nem kérdés
- Szabad szöveg

Minden kérdésnek van neve, leírása és további beállításai a kérdés típusától függően. Minden kérdés szükség szerint konfigurálható
ami azt jelenti, hogy a véleményezőnek válaszolnia kell a kérdésre, mielőtt véleményt hagyna.

A megfelelő értékelési folyamat melletti _Kérdések_ gombra kattintva adhat hozzá értékelő kérdéseket.

![](../../assets/papers/peer_reviewing/questions.png)

Így néznek ki a különböző kérdések a bíráló szemszögéből:

![](../../assets/papers/peer_reviewing/questions_display.png)

Az értékelő kérdések skálája (a minimális és maximális érték) minden kérdésnél ugyanaz, és az értékelő beállításoknál beállítható:

![](../../assets/papers/peer_reviewing/rating_scale.png)
![](../../assets/papers/peer_reviewing/rating_scale_set.png)

!!! megjegyzés
    A minősítések minimális és maximális értékének megváltoztatása arányosan skálázza az összes meglévő választ.

#### A dolgozatok bírálatának beállítása

Az egyetlen kifejezetten a bírálók számára elérhető beállítás a bírálati határidő, amely ugyanúgy működik, mint a korábban ismertetett bírálati határidők.
A határidő beállítása után egy információs doboz jelenik meg a konferencia bírálati területén. Ha a határidő érvényben van, a bírálók nem tudnak bírálni
dolgozatokat a határidő lejárta után.

![](../../assets/papers/peer_reviewing/judge_deadline_set.png)
![](../../assets/papers/peer_reviewing/judge_deadline_display.png)

#### Felülvizsgálati beállítások

A bírálati beállítások segítségével konfigurálhatja a bejelentést, beállíthatja a kérdések értékelésének skáláját (az előző szakaszokban ismertetve), és kezelheti az e-mailes értesítéseket.
A bejelentés segítségével egy üzenetet jeleníthet meg a bírálók számára a szakértői értékelés oldalon.

Az e-mail értesítésekkel beállíthatja, hogy ki és milyen körülmények között
kapjon e-mailt - például, hogy szeretné-e, ha egy bíráló értesítést kapna egy dolgozat bírálatáról. A leggyakoribb értesítések alapértelmezés szerint be vannak kapcsolva, de igény szerint finomhangolhatja őket. A bírálók és bírálók kijelölésével és a dolgozatokhoz való hozzárendelésükkel a következő szakaszokban foglalkozunk.

A bírálati beállítások megnyitásához kattintson a _Elbírálati beállítások_ mellett található _Settings_ gombra.

![](../../assets/papers/peer_reviewing/settings.png)

!!! Megjegyzés
    Az e-mailes értesítés beállításaiban a tartalmi és elrendezési bíráló oszlopok csak akkor láthatók, ha a megfelelő folyamat engedélyezve van.

Íme egy képernyőkép arról, hogyan nézhet ki egy bejelentés.
A bejelentésszerkesztő támogatja az alapvető stílusokat Markdownon keresztül. Képeket is beágyazhat link segítségével.

![](../../assets/papers/peer_reviewing/announcement.png)

#### Értékelő csoportok felállítása

Mielőtt a dolgozatokat kioszthatná a bírálókhoz és a bírálókhoz, szükséges a bírálócsoportok felállítása.
Ezek kijelölik, hogy ki jogosult egy dolgozatot bírálni és/vagy bírálni.

A kezdéshez kattintson a _Teams_ gombra a _Revíziós csapatok_ mellett.

![](../../assets/papers/peer_reviewing/teams.png)

A párbeszédablakban hozzáadhat dolgozatmenedzsereket, bírálókat, valamint tartalmi és elrendezési bírálókat. A lapmenedzserek rendelkeznek a Peer Reviewing modul beállításainak kezeléséhez szükséges jogokkal.
A papírmenedzsereket az esemény _Védelem_ lapjáról is kezelheti a _Papírmenedzser_ jogosultság hozzáadásával.

![](../../assets/papers/peer_reviewing/teams_setup.png)
![](../../assets/papers/peer_reviewing/paper_manager.png)

Ha a csapatok felállítása megtörtént, érdemes _kompetenciákat_ is hozzáadni a bírálókhoz és a bírálókhoz.
A kompetenciák olyan kulcsszavak, amelyeket hozzáadhatsz, és amelyek leírják az adott személy szakterületét.
Ezek a kulcsszavak segíthetnek a lapkezelőknek abban, hogy a megfelelő bírálót és/vagy bírót illesszék a laphoz.

A kompetenciákat a _Revíziós csoportok_ mellett található _Kompetenciák_ gombra kattintva tudja kezelni.

![](../../assets/papers/peer_reviewing/competences.png)
![](../../assets/papers/peer_reviewing/competences_add.png)

A bírálókkal és a bírálókkal való kapcsolatfelvételhez e-mailben is praktikusak a bírálók és a bírálók.
Egyszerűen kattintson a Kapcsolat_ gombra, és válassza ki a kívánt címzetteket.

![](../../assets/papers/peer_reviewing/contact.png)

Az _Emailek küldése_ gombra kattintva megnyílik egy párbeszédablak, ahol megírhatja az e-mailt.

#### A felhívás engedélyezése

Ha eddig a pontig követte a dokumentációt, akkor most már készen kell állnia a call for papers megnyitásához.
Azaz, engedélyezze a szerzők számára, hogy dolgozatokat nyújtsanak be bírálatra.

A felhívás megnyitásához vagy a _Start now_ gombra kattintva azonnal megnyitja a felhívást, vagy a _Schedul_ gombra kattintva.
és válassza ki a felhívás kezdő és befejező dátumát.

![](../../assets/papers/peer_reviewing/cfp_open.png)

Ha a pályázati felhívás nyitva van, ugyanitt lehetőség van annak lezárására vagy átütemezésére is.

#### Papírfeladat kiosztása

Miután a felhívás megnyílt és a dolgozatok benyújtásra kerültek, a lapkezelő feladata, hogy a benyújtott dolgozatokhoz bírálókat és bírálókat rendeljen.
A bírálók és bírálók csak olyan dolgozatokon dolgozhatnak, amelyeket kifejezetten hozzájuk rendeltek.

A dolgozatkiosztás oldal megnyitásához kattintson a _Papírok kiosztása_ mellett a _Papírkiosztás_ gombra.

![](../../assets/papers/peer_reviewing/assign.png)
![](../../assets/papers/peer_reviewing/list_of_papers.png)

Ez az oldal a beadott dolgozatok és azok állapotának áttekintésére szolgál. Ha egy személyt szeretne hozzárendelni egy dolgozathoz, először válassza ki a dolgozatot, és kattintson a
_Assign_ a felső menüben. Válassza ki a kívánt szerepet a legördülő menüből, majd a megnyíló párbeszédpanelen válassza ki azokat a személyeket, akiknek ezt a szerepet ki kell osztani. Itt láthatja az egyes személyek kompetenciáit is.
személy korábban megadott kompetenciáit.

![](../../assets/papers/peer_reviewing/assign_judges.png)

Lehetőség van arra is, hogy egyszerre több dolgozathoz is hozzárendeljünk személyeket. Ehhez egyszerűen válasszon ki több dolgozatot, és kövesse ugyanazt az eljárást.

Egy személy eltávolítása egy dolgozatból,
válassza ki a dolgozatot, majd kattintson a felső menüben a _Unassign_ (Hozzárendelés megszüntetése) gombra, és válassza ki az eltávolítandó szerepet a legördülő menüből. Az újonnan megnyíló párbeszédpanelen válassza ki az eltávolítandó személyt, és erősítse meg a választást a _Unassign_ (Hozzárendelés megszüntetése) gombra kattintva.

![](../../assets/papers/peer_reviewing/unassign_judges.png)

#### Jogosultságok

A szakértői bírálat modul új szerepköröket hoz létre, amelyekkel az Indico felhasználói rendelkezhetnek. Itt adunk egy listát arról, hogy milyen jogosultságok szükségesek ahhoz, hogy elvégezhessék
a Peer Reviewing modulhoz kapcsolódó leggyakoribb műveletek elvégzéséhez.

| Művelet | Szükséges engedélyek |
| --------------------------------- | -------------------------------------------------------------------- |
| Dolgozat beküldése | Absztrakt vagy hozzászólás beküldői |
| Dolgozat bírálata | Dolgozat bírálók és eseménykezelők (a bírálókat ki kell jelölni) |
| Dolgozat elbírálása | Dolgozatbírálók és rendezvénymenedzserek (a bírálókat ki kell jelölni) |
| Dolgozatok hozzárendelése és beállítások kezelése | Dolgozat- és rendezvénymenedzserek |

### Előadás szerzőjeként történő bírálat

Egy tipikus konferencia munkafolyamatában a dolgozat feltöltése előtt az első teendő az absztrakt beküldése. Amint az absztraktot a szervezők elfogadják, automatikusan létrejön egy új hozzászólás. Az összes hozzászólását a _My contributions_ oldalon láthatja.

![](../../assets/papers/peer_reviewing/contributions.png)

Amint az absztraktot elfogadták, beadhat egy dolgozatot, feltéve, hogy a pályázati felhívás nyitva van. A dolgozatot a _Paper Peer reviewing_ oldalon a _Submit paper_ gombra kattintva küldheti be. Ha több olyan hozzászólása is van, amelyhez papírt nyújthat be, akkor megkérjük, hogy válasszon egyet.

![](../../assets/papers/peer_reviewing/submit.png)
![](../../assets/papers/peer_reviewing/submit_select.png)

Közvetlenül a hozzájárulási oldalról is beküldhet egy dolgozatot.

![](../../assets/papers/peer_reviewing/submit_from_contrib.png)

Miután beküldte a dolgozatát, a _Paper Peer reviewing_ oldalon, a _My papers_ alatt nyomon követheti annak előrehaladását.

![](../../assets/papers/peer_reviewing/my_papers.png)

Ezen a ponton a bírálók véleményt hagyhatnak a dolgozatáról javaslatokkal, és javaslatot tehetnek a dolgozat elfogadására, elutasítására vagy javítására. Szerzőként Önt e-mailben értesítjük minden Önt érintő tevékenységről. A dolgozat bírálója kérheti a dolgozatának javítását is, ebben az esetben Ön feltöltheti dolgozatának új változatát.

![](../../assets/papers/peer_reviewing/review.png)

Amint a dolgozatot elfogadták, az a megfelelő hozzájárulásban fog megjelenni.

![](../../assets/papers/peer_reviewing/accepted_papers.png)

### Szakmai bírálat bírálóként

Bírálóként az Ön feladata, hogy átnézze a benyújtott dolgozatokat, és javaslatot tegyen egy intézkedésre - a dolgozat _elfogadására_, _elutasítására_ vagy _javítására_. A dolgozatok bírálói figyelembe veszik az Ön visszajelzéseit, amikor arról döntenek, hogy mit tegyenek.

Csak olyan dolgozatokat bírálhat el, amelyeket kifejezetten Önhöz rendeltek.
Ezeket a dolgozatokat az esemény _Kritika területén_ a _Kritizálandó dolgozatok_ alatt láthatja. Az Ön által már felülvizsgált dolgozatok a _Reviewed papers_ alatt jelennek meg.

![](../../assets/papers/peer_reviewing/papers_to_review.png)

Felkérhetik, hogy hagyjon egy tartalmi, egy layout reviewt, vagy mindkettőt. Ezek pontos meghatározása az adott rendezvénytől és a szervezőktől függ, de általánosságban elmondható, hogy a tartalmi bírálat a szöveggel, annak helyességével és teljességével foglalkozik, míg az elrendezési bírálat a dolgozat stílusát és megjelenését értékeli, valamint azt, hogy az megfelel-e az adott konferencia irányelveinek.

Egy dolgozat véleményezéséhez először válasszon ki egy dolgozatot a dolgozatok listájából, hogy megnyissa a dolgozat idővonalát. Az idővonal oldal tetején, 
letöltheti a benyújtott dolgozat legfrissebb változatát. Ha elolvasta a dolgozatot, és készen áll a bírálat hozzáadására, kattintson a _Review_ gombra.

![](../../assets/papers/peer_reviewing/make_a_review.png)

Ha a tartalom és az elrendezés felülvizsgálatára is felkérték, akkor megjelenik egy legördülő ablak, ahol ki kell választania, hogy melyik típusú felülvizsgálatot szeretné hozzáadni.

![](../../assets/papers/peer_reviewing/choose_review_type.png)

A kiválasztás után ki kell választania a javasolt műveletet - a dolgozat _elfogadása_ vagy _elutasítása_, illetve _korrekciók kérése_.
Ha a szervező extra bírálati kérdéseket adott hozzá, előfordulhat, hogy a bírálat hozzáadásához meg kell válaszolnia ezeket.

![](../../assets/papers/peer_reviewing/propose_action.png)

A bírálatot később is szerkesztheti, amennyiben még nincs bírálat. Ezt az értékelésedben a szerkesztés ikonra kattintva teheted meg.

![](../../assets/papers/peer_reviewing/edit_review.png)

Egy dolgozathoz véleményezés nélkül is hozzá lehet szólni anélkül, hogy véleményt hagyna. A hozzászólás láthatóságát beállíthatja úgy, hogy az csak pl. a bírálók számára legyen látható. Ez hasznos, ha kényes témákat vitat meg anélkül, hogy a szerző látná.

![](../../assets/papers/peer_reviewing/comment.png)

Ha egy bíró javításokat kér, a bírálók megtekinthetik a javított dolgozatot.

### Bírálóként történő bírálat

A dolgozatbíráló munkafolyamata nagyban hasonlít a bírálókéhoz. A bírálók csak olyan dolgozatokat bírálhatnak el, amelyeket a dolgozatmenedzserek osztottak ki számukra.
A bírálható dolgozatok listája a _Bírálati terület_ alatt érhető el.

![](../../assets/papers/peer_reviewing/judging_area.png)

A dolgozatok bírálói mondják ki a végső szót, amikor egy dolgozat elfogadásáról van szó. Elfogadhatják vagy elutasíthatják a dolgozatot, illetve kérhetnek javításokat. Ha javításokat kérnek,
a dolgozat szerzője új változatot nyújthat be, amelyet újra bírálni kell.
Ne feledje, hogy egy dolgozatot csak egy bíráló bírálhat el.

A bírálat hozzáadása előtt győződjön meg arról, hogy a bírálóknak volt lehetőségük átnézni a dolgozatot. A kijelölt tartalmi és elrendezési bírálókat a _Bírálati terület_ alatt láthatja.

A bírálatok a bírálati mezőben található _Rezess judgment_ ikonra kattintva visszaállíthatók:

![](../../assets/papers/peer_reviewing/reset_judgment.png)

Bírálóként az ítélet hozzáadása előtt megjegyzéseket is hagyhat egy dolgozathoz.

!!! Megjegyzés
    Mind a bírálatnak, mind a bírálatnak lehet egy meghatározott határideje, amely után már nem lehet dolgozatokat bírálni vagy bírálni. Ha van határidő, akkor azt a bírálat és a bírálat területén láthatja.
    ![](../../assets/papers/peer_reviewing/reviewing_deadline_display.png)
