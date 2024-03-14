# Védelem

A Kezelő Területen védelmet állíthatsz be a kategóriádra vonatkozóan azzal kapcsolatban, hogy ki láthatja, ki a menedzsere és ki hozhat létre eseményeket a kategóriában.

![](../assets/category_protection.png)

Felhasználókat és csoportokat adhatsz hozzá a kategóriához, hogy hozzáférjenek a Kezelő Területhez a módosítások elvégzéséhez. A kategória menedzserei azok, akik a *Kezel* engedéllyel vannak felsorolva, az Indico adminisztrátorai, és a kategória létrehozója.
A felhasználókon és csoportokon kívül lehetséges egyéni szerepköröket is hozzáadni, ahogy az a [Egyéni szerepkörök használata](../custom_roles.md) részben le van írva.

![](../assets/category_protection_edit_permissions.png)

Egy felhasználó vagy csoport engedélyeinek szerkesztéséhez kattints a ceruzára. Az elérhető engedélyek lehetővé teszik:

- *Hozzáférés*: a kategóriához tartozó események megtekintése;
- *Kezelés*: a kezelő terület elérése, az összes beállítás módosítása és az eseménymozgatási kérelmek moderálása.
- *Esemény létrehozása*: események létrehozása a kategóriában;
- *Esemény mozgatásának kérése*: egy esemény áthelyezésének kérése a kategóriába.

Ezenkívül a *Kezelés* engedély magában foglalja az *Esemény létrehozása* és *Esemény mozgatásának kérése* engedélyeket is a felhasználó/csoport számára.

*Védelmi mód*: egy kategória lehet:

- *Nyilvános*: bárki megtekintheti benne az eseményeket, vagy
- *Öröklődő*: az őskategória védelmi módja (lásd az oldal tetején lévő morzsamenüt) érvényes, vagy
- *Védett*: csak a *Jogosultságok* listáján szereplő felhasználók vagy az adminisztrátorok férhetnek hozzá a kategóriához.

Amikor egy Kategória _Öröklődő_ vagy _Védett_ módban van, a menedzser(ek) megadhatnak kapcsolati információkat, amelyek megjelennek a nem jogosult nézők számára, így azok, akiknek nincs hozzáférésük, tudni fogják, kit kell megkeresniük a hozzáférés kéréséhez.

Fontos megjegyzés az _Öröklődő_ védelmi módhoz - az szülőkategória védelmének megváltoztatása megváltoztatja az alárendelt kategóriák védelmét is.

*Esemény láthatósága*: ez **nem** kapcsolódik a kategória megtekintési jogaihoz - ezeket a fentebb magyarázott *Védelmi mód* szabályozza. A kínált választási lehetőségekkel eldöntheted, hogy az események megjelenjenek-e a *Mai események* és a *Naptár* részben mindenhol vagy csak néhány őskategóriában.

*Esemény létrehozási mód*: korlátozhatod, hogy ki
