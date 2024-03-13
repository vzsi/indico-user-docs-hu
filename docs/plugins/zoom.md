# Zoom integráció

!!!! figyelmeztetés
    Ez a funkció csak azokon a szervereken érhető el, ahol a
    [Zoom Plugin](https://pypi.org/project/indico-plugin-vc-zoom/) telepítve van.

Az Indico lehetővé teszi a találkozószervezők számára, hogy létrehozzanak egy Zoom találkozót, és azt közvetlenül a kezelőterületükről kezeljék a
eseményükből. A létrehozás után a Zoom megbeszélés kapcsolati információi megjelennek a megbeszélés résztvevői számára,
és további gombok kerülnek a felületre, amelyek segítségével a résztvevők könnyen csatlakozhatnak a Zoom-értekezlethez, és
a szervezők a fizikai tárgyalótermüket a Zoom-értekezlethez csatlakoztatni.

## Zoom értekezletek kezelése

Indico eseményének kezelési oldalán kattintson a _Videokonferencia_ gombra a bal oldali banner _Szolgáltatások_ fülén.

![](../assets/plugins/zoom/videoconf_menu.png)

Itt **elkészíthet** egy új Zoom megbeszélést, vagy **adhat** egy már meglévőt az eseményéhez.

![](../assets/plugins/zoom/videoconf_list.png)

Egyszerűen kattintson az egyik lehetőségre, majd válassza ki a Zoom videokonferencia szolgáltatást.

![](../assets/plugins/zoom/videoconf_choice.png)

### Meglévő Zoom megbeszélés hozzáadása

Ha csak **Egy meglévő terem hozzáadására** van szüksége, kezdje el begépelni a megbeszélés nevét. A meglévő Zoom értekezletek listája
listája fog megjelenni. **Válassza ki** a kívántat, és kattintson a **Mentés** gombra. Felhívjuk figyelmét, hogy csak a Zoom-értekezleteket hozhatja létre
Indico-kiszolgálón létrehozott találkozókat fog javasolni.

Ha visszatér az _Esemény megjelenítése nézetre_, látni fogja, hogy az értekezlet most már az eseményéhez van csatolva.

Lehetősége van arra, hogy a Zoom megbeszélést csak az esemény egy *részéhez* rendelje hozzá, azáltal, hogy összekapcsolja azt bizonyos
hozzászólásokhoz vagy ülésekhez.

### Új Zoom megbeszélés létrehozása

Ha a **Új terem létrehozása** lehetőséget választja, látni fogja, hogy az esemény neve alapértelmezés szerint átmásolódik a Zoom értekezlet nevébe.
nevébe. Ha szeretné, megváltoztathatja azt valami általánosabbra, például a jövőbeni újrafelhasználás érdekében.

A többi mezőt úgy hagyhatja, ahogy van, de néhányat érdemes lehet beállítani:

* A **Description** mezőbe írhat valami hasznosat a felhasználók számára, akik csatlakozni fognak az értekezlethez.
   a jövőben csatlakozni fognak;

* A Zoom megbeszélés alapértelmezett **Host**-ja Ön, de **választhat** valaki mást is, aki a megbeszélés házigazdája lesz.
  a találkozó házigazdája lesz.

!!!! figyelmeztetés
    Kérjük, ne feledje, hogy a Zoomban ugyanaz a házigazda nem indíthat több értekezletet párhuzamosan!

* Ha kívánja, **Passcode**-t is rendelhet az értekezlethez. Csak azok a személyek, akik rendelkeznek a jelszavával, lesznek képesek
  csatlakozhatnak a megbeszéléshez. Ön döntheti el, hogy a jelszó **tisztán** jelenjen-e meg az Indico oldalon.
  mindenki számára, vagy csak a **bejelentkezett felhasználók számára (ajánlott)**, vagy **egyáltalán senki számára** (pl. elküldi a
  jelszót e-mailben).

* A **Hosszabb beállítások** segítségével kiválaszthatja, hogy a Zoom megbeszélés megjelenjen-e az eseményoldalon, valamint hogy
  különböző **némítási** beállításokat, amelyek akkor lesznek alkalmazva, ha valaki csatlakozik hozzá.

Kattintson a **Mentés** gombra.

![](../assets/plugins/zoom/create_room_modal.png)

Ellenőrizze a videokonferenciaterem listáját, és nézze meg, hogyan tudja **szerkeszteni** a termet, **leválasztani** az eseményről vagy **csatlakozni**.
egyetlen kattintással:

![](../assets/plugins/zoom/videoconf_list_final.png)

Kattintson a **Join** gombra, és a Zoom megbeszélés oldalára kerül. Ezután választhat, hogy a csatlakozást a
asztali Zoom klienssel vagy annak webes verziójával csatlakozhat.

### Saját magunk hozzáadása alternatív házigazdaként

Ha Ön egy Indico esemény vezetője, és jogosult a Zoom szolgáltatás használatára, lehetősége van arra, hogy hozzáadjon
magát alternatív házigazdaként az adott Indico eseményhez kapcsolódó bármely Zoom megbeszéléshez.

![](../assets/plugins/zoom/videoconf_alternative_host.png)
