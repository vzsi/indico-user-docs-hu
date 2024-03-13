# Eseménysorozat

Az Indico lehetővé teszi több esemény összekapcsolását egy _Event series_ (eseménysorozat) formájában. A sorozatba tartozó események megjeleníthetik a sorozatba tartozó más eseményekre mutató linkeket a főoldalukon:

![](assets/event_series/event-series.png)

### Eseménysorozat létrehozása

Az előadássorozatokat közvetlenül a létrehozási párbeszédpanelben egy [_esemény_](../előadások/alkotás) hozzáadásával lehet létrehozni, de lehetőség van eseménysorozatot létrehozni **minden** eseményből.

Ha meglévő eseményekből szeretne sorozatot létrehozni, válassza ki az egyik eseményt, és navigáljon a kezelési területre. A jobb felső sarokban található eseményműveletek közül válassza a _Sorozat létrehozása_ lehetőséget.

![](assets/event_series/create-button.png)

Ekkor megnyílik egy párbeszédpanel, ahol megkeresheti a sorozatához hozzáadandó eseményeket:

![](assets/event_series/create.png)

### Sorozat szerkesztése

Egy meglévő sorozat módosításához egyszerűen nyissa meg újra a párbeszédpanelt, végezze el a módosításokat, és erősítse meg a _Edit series_ (Sorozat szerkesztése) gombra kattintva. Ugyanebben a párbeszédpanelben magát a sorozatot is törölheti, ami az összes benne lévő eseményt feloldja. Ezzel az eseményoldalon lévő más eseményekre mutató hivatkozások is törlődnek.

![](assets/event_series/edit.png)

### Események klónozása egy sorozatban

Az események klónozása ismeri az eseménysorozatokat, és automatikusan hozzáadja a klónozott eseményeket az eseménysorozathoz. Lehetőség van a beállítások oldalon egy _Event title pattern_ (eseménycímminta) beállítására is, amely alapján a klónozott esemény esemény címe generálásra kerül. A címnek egy `{n}` helyőrzőt kell használnia, amely az esemény sorozatban elfoglalt pozícióját helyettesíti. Például, ha a címminta `Havi találkozó {n}`, a cím _Havi találkozó 3_ lesz, ha a klónozott esemény a sorozat harmadik eseménye (a klónozott események a sorozat végére kerülnek).

![](assets/event_series/title-pattern.png)

### Sorozat exportálása naptárba

Az Indico már lehetővé teszi az események és kategóriák szinkronizálását külső naptáralkalmazásokkal.
Ha ehelyett egy eseménysorozat összes eseményét szeretné szinkronizálni, először navigáljon a szinkronizálni kívánt eseménysorozat bármelyik eseményére.
Kattintson a bal felső sarokban az _Exportálás_ gombra, és a felugró ablakban engedélyezze az _Exportálási lehetőségek_ alatt az _Előrehaladási sorozat összes eseményének exportálása_ opciót. Mostantól mind az URL, mind a letöltött ical fájl tartalmazni fogja a sorozat összes eseményét. Ha az URL-t használja, a sorozathoz hozzáadott új események automatikusan hozzáadódnak a naptárához.

![](assets/event_series/ical-export.png)
