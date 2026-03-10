---
layout: bare
title: IPA Reader bővítmény - Felhasználói útmutató
lang: hu
---

# IPA Reader - Felhasználói útmutató

> Verzió: v1.2.1

## Bevezetés

Az IPA Reader egy böngészőbővítmény angol tanulóknak készítve. IPA (Nemzetközi Fonetikai Ábécé) kiejtési megjegyzéseket ad hozzá az angol szavakhoz a weboldalakon, amerikai és brit angol akcentussal, segítve könnyebben megtanulni az angol kiejtést.

---

## Főbb funkciók

- **Szövegkijelöléses megjegyzés** — Jelöljön ki angol szöveget weboldalakon az IPA és beszédgombok automatikus megjelenítéséhez
- **Teljes oldal IPA mód** — Egy kattintással IPA megjegyzéseket adhat minden angol szóhoz az oldalon, színkódolt IPA szimbólumokkal (magánhangzók, mássalhangzók, hangsúlyjelek) a könnyű olvashatóság érdekében
- **Amerikai és brit akcentus** — Válthat amerikai angol (en-US) és brit angol (en-GB) IPA között
- **Text-to-Speech** — Kattintson a hangszóró gombra a kiválasztott akcentusnak megfelelő kiejtés meghallgatásához
- **Kijelölés beszéd** — Jelöljön ki bármilyen angol szöveget, kattintson a lebegő gombra vagy jobb klikk „Speak Selection” a felolvasáshoz
- **Hover tooltipek** — Vigye az egeret a megjegyzett szavak fölé az IPA és kiejtésgombok megtekintéséhez
- **Gyenge/erős alakok** — Funkciószavak (pl. the, to, can) gyenge és erős kiejtési változatainak automatikus megjelenítése a természetes összefüggő beszéd elsajátításához
- **Homográfok felismerése** — Több kiejtéssel rendelkező szavak (pl. read, live) automatikus azonosítása és a helyes kiejtés kiválasztása a szövegkörnyezet alapján
- **Többnyelvű felület** — 38 felületi nyelvet támogat

---

## Használat

### 1. lépés: Bővítmény telepítése

Telepítse az **IPA Reader**-t a [Chrome Web Store](https://chromewebstore.google.com/) oldalról, vagy töltse be helyileg fejlesztői módban.

### 2. lépés: Tetszőleges weboldal megnyitása

Látogasson el bármely angol tartalmú weboldalra.

### 3. lépés: Szöveg kijelölése vagy lebegő gomb használata

Jelöljön ki angol szöveget a megjegyzéshez, vagy kattintson a jobb alsó sarokban lévő lebegő gombra a teljes oldal IPA módhoz.

### 4. lépés: IPA megtekintése

Vigye az egeret a szavak fölé az IPA tooltipek megtekintéséhez, kattintson a hangszóró ikonra a kiejtés meghallgatásához.

### 5. lépés: Kijelölt szöveg felolvasása

Jelöljön ki bármilyen angol szöveget az egérrel, kattintson a lebegő 🔊 hangszóró gombra; vagy jobb klikk és válassza a „Speak Selection” opciót.

> **Tipp:** Kattintson a bővítmény ikonjára a böngésző eszköztárán a beállítások panel megnyitásához az akcentus típus, beszédsebesség és egyéb beállítások módosításához.

---

## Kijelölés beszéd

A kijelölés beszéd funkció lehetővé teszi bármilyen angol szöveg kijelölését és egy kattintással felolvasását — tökéletes a mondatkiejtés és olvasási gyakorlat tanulásához.

**1. módszer: Lebegő gomb**  
Jelöljön ki angol szöveget az egérrel, egy hangszóró gomb jelenik meg a kijelölés jobb felső sarkában — kattintson a beszédhez.

**2. módszer: Jobb kattintás menü**  
Angol szöveg kijelölése után jobb klikk és válassza a „Speak Selection” opciót a menüből.

> **Tipp:** A kijelölés beszéd a beállításokban megadott mondat beszédsebességet használja. Az egyéni szó kiejtés az alapértelmezett sebességet használja. A TTS hang az Ön által kiválasztott akcentus típusnak (amerikai vagy brit) felel meg.

---

## Beállítások útmutató

| Beállítás | Leírás |
|---------|-------------|
| **IPA engedélyezése** | Főkapcsoló az IPA megjegyzés funkció be- vagy kikapcsolásához |
| **Teljes oldal IPA** | Engedélyezve az IPA megjelenik minden angol szónál (befolyásolhatja az oldal elrendezését) |
| **Akcentus típus** | Válasszon amerikai és brit angol IPA és kiejtés között |
| **Mondat beszédsebesség** | A mondat felolvasás sebességének beállítása (az egyéni szó beszéd nem érintett) |
| **Gyenge/erős alakok** | Funkciószavak gyenge és erős kiejtési változatainak megjelenítése |
| **Hover tooltipek** | IPA tooltip megjelenítése egér hover esetén |

---

## GYIK

**K: Miért nem működik egyes oldalakon?**  
V: Biztonsági okokból a böngészőbővítmények nem futtathatók speciális oldalakon, mint a `chrome://`, böngésző beállítások vagy a Chrome Web Store.

**K: Mi van, ha hiányzik az IPA néhány szóhoz?**  
V: Az IPA szótár a gyakori angol szavakat fedi le. A szótárban nem szereplő szavakhoz a bővítmény közelítő IPA-t generál lemmatizálással és G2P-vel, ≈ vagy ~ jelöléssel az eszköztippben.

**K: Nincs hang a text-to-speech-től?**  
V: Kérjük, ellenőrizze a rendszer hangerő beállításait és győződjön meg róla, hogy angol hangcsomagok telepítve vannak. A beszéd támogatás böngészők és operációs rendszerek között változik.

**K: A teljes oldal mód befolyásolja az elrendezést?**  
V: Az IPA megjegyzések extra helyet igényelnek, ami befolyásolhatja az eredeti oldalelrendezést. Ha befolyásolja az olvasást, kapcsolja ki a teljes oldal módot és használja helyette a hover tooltipeket.


**K: Mit jelentenek a ~ és ≈ szimbólumok az eszköztippekben?**  
V: ~ azt jelenti, hogy az IPA szabályokkal (G2P) lett generálva, az ≈ pedig, hogy egy kapcsolódó alapszóból származtatták. Ezek kevésbé pontosak lehetnek a szótári bejegyzéseknél.

---

## Kapcsolódó linkek

- [Adatvédelmi irányelvek](../privacy-policy)
- [Támogatás és visszajelzés](../support)

---
