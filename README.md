# Angol CCM énekek szövegei magyarra fordítva

## Q&A

**Q: Miért?**<br>
**A**: Egyre több új ének jelenik meg a nemzetközi (főleg angol nyelvű) CCM (Contemporary Christian Music) terén - ezzel valószínűleg tisztában vagyunk, hiszen többségünk ezeket hallgatja utazás, tanulás, stb. közben. Viszont kedvenc énekeninket nem énekelhetjük magyar nyelvű gyülekezeteinkben, mivel a gyülekezet tagjainak nagyrésze nem értené őket, és a hivatalos fordításokra sokszor éveket kell várni. Ezt a problémát hivatott áthidalni ez a Repo: bárki hozzájárulhat az új énekek lefordításához. :-)

**Q: Hogyan?**<br>
**A**: A projekt a GitHub oldalon van tárolva, és a git-rendszerrel lehet módosítani. Azért ez a megoldás, hogy a verzióellenőrzés és a módosítási előzmények jobban és elegánsabban legyenek kezelve. Amennyiben ez kérdéseket vet fel, ajánlom a GitHub GUI alkalmazását letölteni - ez lényegesen megkönnyíti a dolgokat. Azon túl pedig ajánlott a Google használata is. :-)

**Q: Hogyan megy a rendszerezés?**<br>
**A**: A fő könyvtárban minden előadónak / zenekarnak van 1-1 mappa. Ezeken a mappákon belül minden számnak van 1-1 másik mappa, a szám angol címével. Minden szám mappájában ajánlott, hogy ott legyen az eredeti (angol) szöveg, ÉS a lefordított, magyar szöveg.
Így például a Rend Collective együttes Marching On c. számának a "fája" így néz ki:

```python
/Rend Collective/Marching On/

Ezen belül 2 fájl:
- angol.txt
- magyar.txt
```

```python
/ = root/gyökérkönyvtár - itt van az összes előadó mappája,
innen ágaznak ki az előadó-ágak.
Lényegében "ez egy fa"...
```

A fájlok kiterjesztéséhez a .TXT ajánlott, mivel ez nagyjából minden rendszerrel kompatibilis, és nem szükséges hozzá különleges szövegszerkesztő.

Minden angol szövegnél ajánlott egy egyszerű YouTube link beszúrása is, egy official / lyrics videóhoz. Továbbá, ha van acapella alap / szöveg nélküli változat, azt is be lehet linkelni.
<br><br>
Remélem hasznosnak bizonyul ez a kezdeményezés / projekt többek számára. :-D
# SDG!
