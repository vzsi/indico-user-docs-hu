# Adatvédelem

Az Indico számos adatvédelmi funkciót tartalmaz, amelyek segítenek kezelni a résztvevők regisztrációs adatait, és tájékoztatni a résztvevőket arról, hogyan kezeljük személyes adataikat.

### Az esemény adatvédelmi beállításainak kezelése
Az esemény adatvédelmi beállításai a menedzsment területen érhetők el, egy külön _Adatvédelem_ fülön.
Innen kezelhető az esemény összes adatvédelemmel kapcsolatos beállítása.

![Adatvédelmi irányítópult](assets/privacy/privacy_dashboard.png)

#### Adatkezelő
Az adatvédelmi irányítópult első szakasza az _Adatkezelőt_ határozza meg.

Ha az eseményed során személyes adatokat gyűjtesz és az GDPR vagy hasonló adatvédelmi törvény hatálya alá tartozol,
megadhatod itt a kijelölt Adatkezelő nevét és kapcsolattartási adatait.

![Adatkezelő](assets/privacy/data_controller.png)

#### Adatvédelmi tájékoztató
A következő szakaszban adhatod meg az esemény adatvédelmi tájékoztatóját.
Választhatsz, hogy egy külső oldalra mutató linket adsz meg, amely tartalmazza az adatvédelmi tájékoztatót, vagy
beírod a tájékoztató szövegét egy szövegmezőbe.

Szükség esetén több
külső tájékoztatót is megadhatsz a *Hozzáadás* gombra kattintva, címet és a külső URL-t hozzáadva.

![Adatvédelmi tájékoztató](assets/privacy/privacy_notice.png)

Az adatvédelmi információk elérhetők a résztvevők számára mind a találkozók, mind a konferenciák esetén.
A találkozóknál az adatvédelmi információk egy felugró ablakból érhetők el az esemény fejlécének jobb felső sarkában, míg a konferenciáknál egy új menüpontban, egy külön oldalon.

![Adatvédelmi tájékoztató találkozókhoz](assets/privacy/privacy_meeting.png)
![Adatvédelmi tájékoztató konferenciákhoz](assets/privacy/privacy_conference.png)

### A résztvevők láthatósága
Alapértelmezés szerint az Indico minden regisztrált résztvevőt megjelenít az esemény oldalán.
Azonban egyes résztvevők előnyben részesíthetik, ha ez az információ nem látható mindenki számára.

E célból az Indico lehetővé teszi, hogy beállíthasd a résztvevők láthatóságának beállításait minden regisztrációs űrlap esetén az eseményeden belül.
A láthatósági beállítások külön-külön állíthatók be a regisztrált résztvevők és az általános nyilvánosság számára.

A láthatósági opciók:

- Rejtett

- Látható, ha a résztvevő beleegyezését adja

- Mindig látható, beleegyezés függetlenül

A regisztráció során a résztvevők választhatják az opciót, hogy beleegyeznek-e a résztvevői listán való megjelenítésbe. Ez felel meg a fenti listán szereplő második opciónak.

Az utolsó opció, amely a résztvevőt mindig láthatóvá teszi, nem ajánlott, és csak akkor használható, ha jogos érdek fűződik a résztvevői lista láthatóságához. Ezenkívül, ezt az opciót csak akkor lehet kiválasztani, ha még nincs regisztrált résztvevő.

Az adatvédelmi irányítópult utolsó szakasza az adott esemény összes regisztrációs űrlapjának jelenlegi láthatósági beállításait mutatja.

![Adatkezelő](assets/privacy/participant_visibility.png)

A láthatósági beállítások kezelhetők az adott regisztrációs űrlaphoz tartozó fogaskerék ikonra kattintva
ezzel megnyílik a regisztrációs adatvédelmi beállítások ablak, amely a regisztrációs űrlap beállításaiból is elérhető, kiválasztva az _Adatvédelmi beállítások_ opciót.

![Adatkezelő](assets/privacy/privacy_settings.png)

Ezen az oldalon módosíthatod a résztvevők láthatósági beállításait és a láthatósági időtartamot, amely beállítás után
automatikusan elrejti a résztvevői listát egy adott hónapszám után.

![Adatkezelő](assets/privacy/visibility_settings.png)


### Adatmegőrzési időszak
Az Indico lehetővé teszi, hogy automatikusan törölj a regisztrációs adatokat egy meghatározott idő elteltével, adatmegőrzési időszak beállításával.

Az adatmegőőrzési időszak regisztrációs szinten állítható be, amely aztán az egész regisztrációs űrlapra vonatkozik. Amint ez az időszak lejár,
automatikusan töröljük az összes regisztrációt, beleértve az adatokat és a résztvevői listát is.

Ezzel együtt lehetőség van egyedi regisztrációs mezők adatmegőrzési időszakának beállítására is. Ez a részletesség akkor hasznos, ha néhány mezőt meg kell tartani, míg másokat törölni lehet. Amint az adatmegőrzési időszak lejár, csak azon mezők adatai törlődnek, amelyeknél beállították az adatmegőrzési időszakot.

Az adatmegőrzési időszak az esemény befejezési dátumához képest számított.

Az egész regisztrációra vonatkozó adatmegőrzési időszak beállítható a regisztrációs adatvédelmi beállítások oldalon, rögtön a láthatósági beállítások alatt:

![Adatkezelő](assets/privacy/visibility_settings_retention.png)

Egy regisztrációs mező adatmegőrzési időszakának beállításához először nyisd meg a regisztrációs űrlap tervezőjét a _Regisztráció_ -> _Kezelés_ -> _Regisztrációs Űrlap_ menüpont alatt.

![Adatkezelő](assets/privacy/regform_designer.png)

Ezután nyisd meg a mező beállításait a szerkeszteni kívánt mező melletti fogaskerék ikonra kattintva.

![Adatkezelő](assets/privacy/retention_period_field.png)

Az adatmegőrzési időszak a beállítások párbeszédablakának alján állítható be:

![Adatkezelő](assets/privacy/retention_period_settings.png)

Továbbá, az adatmegőrzési időszakkal rendelkező mezők mellett egy óra ikon jelenik meg.

![Adatkezelő](assets/privacy/retention_period_icon.png)

