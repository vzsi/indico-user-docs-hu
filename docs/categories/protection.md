# Védelem

A Kezelési területről megvédheti a kategóriáját a tekintetben, hogy ki láthatja, ki a kezelője, és ki hozhat létre eseményeket a kategóriában.

![](../assets/category_protection.png)

Felhasználók és csoportok adhatók hozzá egy kategóriához, hogy a Kezelési területhez hozzáférést biztosítsanak a módosításhoz. A kategória kezelői azok, akik a *Manage* jogosultsággal szerepelnek, az Indico adminisztrátorok és a kategória létrehozója.
A felhasználók és csoportok mellett lehetőség van egyéni szerepkörök hozzáadására is, az [Egyéni szerepkörök használata](../custom_roles.md) című fejezetben leírtak szerint.

![](../assets/category_protection_edit_permissions.png)

Egy felhasználó vagy csoport jogosultságainak szerkesztéséhez kattintson a ceruzára. A rendelkezésre álló jogosultságok lehetővé teszik:

- * Hozzáférés*: a kategóriához tartozó események megtekintése;
- *Manage*: a kezelési terület elérése, az összes beállítás módosítása és az esemény áthelyezési kérelmek moderálása.
- *Esemény létrehozása*: a kategóriába tartozó események létrehozása;
- *Esemény áthelyezésének kérése*: esemény áthelyezésének kérése a kategóriába.

Ezen túlmenően a *Manage* jogosultság megadja a *Event creation* és *Request event move* jogosultságokat a felhasználónak/csoportnak.

*Védelmi mód*: egy kategória lehet:

- *nyilvános*: bárki megtekintheti a benne lévő eseményeket, vagy
- *Öröklés*: a szülő kategória védelmi módja érvényes (lásd a morzsákat az oldal tetején lévő banner alatt), vagy
- *Védett*: csak a *Jogosultságok* listában szereplő felhasználók vagy az adminisztrátorok férhetnek hozzá a kategóriához.

Ha egy kategória _Öröklés_ vagy _Védett_ módban van, a kezelő(k) meghatározhatják a nem jogosult nézők számára megjelenítendő elérhetőségeket, hogy a hozzáféréssel nem rendelkező felhasználók tudják, kihez kell fordulniuk a hozzáférés kérése érdekében.

Fontos megjegyzés az _Öröklődő_ védelmi móddal kapcsolatban - a szülői védelem megváltoztatása az alkategóriák védelmét is megváltoztatja.

*Esemény láthatósága*: ez **nem** kapcsolódik a kategóriák megtekintési jogaihoz - azokat a fentebb ismertetett *Védelmi mód* szabályozza.  A felkínált választási lehetőség lehetővé teszi annak eldöntését, hogy az adott kategóriába tartozó események mindenhonnan vagy csak egyes szülő kategóriákból jelenjenek meg a *Napi események* és a *Naptár* között.

*Esemény létrehozási mód*: korlátozhatja, hogy ki adhat hozzá eseményeket a kategóriához. Ha így tesz, akkor a jogosultságok listájához hozzá kell adnia felhasználókat vagy csoportokat, hogy engedélyezze számukra az események létrehozását, illetve az események áthelyezési kérelmeinek moderálását.
