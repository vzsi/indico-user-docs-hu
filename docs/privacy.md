# Privacy

Az Indico számos adatvédelmi funkciót tartalmaz, amelyek segítenek a résztvevők regisztrációs adatainak kezelésében, és tájékoztatják a résztvevőket személyes adataik kezeléséről.

### Az esemény adatvédelmi beállításainak kezelése
Az esemény adatvédelmi beállításai a kezelési területről egy külön fülön, a _Privátus_ nevű lapon érhetők el.
Innen kezelheti az eseménye összes adatvédelmi vonatkozású beállítását.

![Adatvédelmi műszerfal](assets/privacy/privacy_dashboard.png)

#### Adatkezelő
Az adatvédelmi műszerfal első szakasza az _Adatok vezérlőjét_ határozza meg.

Ha az Ön rendezvényén személyes adatokat gyűjt, és a GDPR vagy egy hasonló adatvédelmi jogszabály hatálya alá tartozik,
megadhatja a nevet és az elérhetőséget
kijelölt adatkezelőjének adatait itt.

![Adatkezelő](assets/privacy/data_controller.png)

#### Adatvédelmi tájékoztató
A következő szakaszban beállíthatja az eseményére vonatkozó adatvédelmi nyilatkozatot.
Választhat, hogy az adatvédelmi nyilatkozatot tartalmazó külső oldalra hivatkozik-e, vagy
vagy beírja az adatvédelmi nyilatkozatot a szövegmezőbe.

Szükség esetén többszörös
külső értesítést a *Add* gombra kattintva, és hozzáadva a címet és a külső url-t.

![Adatvédelmi közlemény](assets/privacy/privacy_notice.png)

Az adatvédelmi tájékoztató mind az értekezletek, mind a konferenciák résztvevői számára elérhető.
Az értekezletek esetében az adatvédelmi információk az esemény fejlécének jobb felső sarkában található felugró ablakból érhetők el, míg a konferenciák esetében egy új menüpont külön oldalt tartalmaz.

![Adatvédelmi tájékoztató értekezletek](assets/privacy/privacy_meeting.png)
![Adatvédelmi tájékoztató konferenciák](assets/privacy/privacy_conference.png)

### Résztvevők láthatósága
Az Indico alapértelmezés szerint az esemény oldalán az összes regisztrált résztvevőt megjeleníti.
Néhány résztvevő azonban jobban szeretné, ha ez az információ nem lenne mindenki számára látható.

Ebből a célból az Indico lehetővé teszi, hogy az esemény minden egyes regisztrációs űrlapjánál beállítsa a résztvevők láthatóságának beállításait.
A láthatósági beállításokat külön-külön lehet beállítani a regisztrált résztvevők és a nagyközönség számára.

A láthatósági beállítások a következők:

- Rejtett

- Látható, ha a résztvevő beleegyezését adja

- Mindig látható a hozzájárulástól függetlenül

A regisztráció során a résztvevőknek lehetőségük van arra, hogy hozzájáruljanak ahhoz, hogy a résztvevők listáján megjelenjenek. Ez a fenti listából a második lehetőségnek felel meg.

Az utolsó lehetőség, amely a résztvevőt mindig láthatóvá teszi, nem javasolt, és nem szabad használni, kivéve, ha jogos érdeke fűződik a résztvevők listájának láthatóságához. Ráadásul ez az opció csak addig választható, amíg nincsenek regisztrált résztvevők.

Az adatvédelmi műszerfal utolsó szakasza az adott esemény összes regisztrációs űrlapjának aktuális láthatósági beállításait mutatja.

![Adatkezelő](assets/privacy/participant_visibility.png)

A láthatósági beállítások a regisztrációs űrlaphoz tartozó fogaskerék ikonra kattintva kezelhetők.
amelyet frissíteni kíván. Ez megnyitja a regisztráció adatvédelmi beállításait, amelyek szintén elérhetők a regisztrációs űrlap beállításai és a _Adatvédelmi beállítások_ menüpont kiválasztásával.

![Adatkezelő](assets/privacy/privacy_settings.png)

Ezen az oldalon módosíthatja a résztvevők láthatóságának beállításait és a láthatóság időtartamát, amely beállítása esetén
a résztvevők listáját egy megadott számú hónap után automatikusan elrejti. 

![Adatkezelő](assets/privacy/visibility_settings.png)


### Adatmegőrzési időtartam
Az Indico lehetővé teszi a regisztrációs adatok automatikus törlését egy meghatározott idő elteltével a megőrzési időszak beállításával.

A megőrzési időszak beállítható a regisztráció egészére vonatkozóan, ami az egész regisztrációs űrlapra vonatkozik. Ha ez az időszak lejár, 
az összes regisztráció automatikusan törlődik az adatokkal együtt, beleértve a résztvevők listáját is.

Ezzel együtt az egyes regisztrációs mezőkre is beállítható megőrzési időszak. Ez a részletesség hasznos abban az esetben, ha egyes mezőket meg kell tartani, míg másokat törölni lehet. A megőrzési időszak lejárta után csak annak a mezőnek az adatai törlődnek, ahol a megőrzési időszakot beállítottuk.

A megőrzési időszakot az esemény befejezési dátumához viszonyítva kell számolni.

A regisztráció egészére vonatkozó megőrzési időszakot a regisztráció adatvédelmi beállítások oldalán lehet beállítani, közvetlenül a láthatósági beállítások alatt:

![Adatkezelő](assets/privacy/visibility_settings_retention.png)

A regisztrációs mezőn való megőrzési időszak beállításához először nyissa meg a regisztrációs űrlap tervezőjét a _Regisztráció_ -> _Kezelés_ -> _Regisztrációs űrlap_ menüpontban.

![Adatkezelő](assets/privacy/regform_designer.png)

Ezután nyissa meg a mező beállításait a szerkeszteni kívánt mező melletti fogaskerék ikonra kattintva.

![Adatkezelő](assets/privacy/retention_period_field.png)

A megőrzési időszakot a beállítások párbeszédpanel alján állíthatja be:

![Data controller](assets/privacy/retention_period_settings.png)

Ezenkívül a megőrzési időszakkal rendelkező mezők neve mellett egy óra ikon jelenik meg.

![Data controller](assets/privacy/retention_period_icon.png)
