# A mesterséges intelligencia alapjai – 3. beadandó

## Készítette

- Mikulás Marcell
- Kozma Zsófia

Budapesti Corvinus Egyetem  
A mesterséges intelligencia alapjai  
2026

---

# Projekt leírása

A projekt célja egy Amazon filmes adatbázis elemzése és különböző statisztikai, valamint gépi tanulási módszerek alkalmazása az adatok vizsgálatára.

A beadandó során adatfeldolgozást, statisztikai elemzéseket, vizualizációkat és modellezési feladatokat végeztünk Python és Jupyter Notebook környezetben.

A projekt GitHub repository-ban készült, ahol mindkét csapattag aktívan részt vett a fejlesztésben és külön commitokkal járult hozzá a megoldáshoz.

---

# Felhasznált technológiák

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- GitHub

---

# Projekt struktúra

```text
data/
notebooks/
images/
README.md
requirements.txt
```

---

# Megvalósított feladatok

## Adatfeldolgozás

- CSV adatbázis beolvasása
- Hiányzó adatok kezelése
- Adattisztítás
- Rendezők és színészek feldolgozása
- Adatok előkészítése modellezéshez

## Elemzés

Megvizsgáltuk többek között:

- Hány különböző rendező található az adatbázisban
- Átlagosan hány filmet rendeztek
- A rendezők medián és szórás értékeit
- Hány különböző színész szerepel az adatok között
- Melyik színész szerepel a legtöbb filmben
- A filmek átlagos értékelését
- Az értékelések szórását

## Modellezés

A projekt során egyszerű regressziós modelleket is alkalmaztunk annak vizsgálatára, hogy:

> Prediktálja-e az értékelések száma magát az értékelést.

---

# Vizualizációk

A projekt során több grafikon és statisztikai ábra is készült, például:

- hisztogramok
- oszlopdiagramok
- eloszlásvizsgálatok
- scatter plotok

---

# Eredmények

Az elemzések alapján megállapítható, hogy:

- a legtöbb rendező csak kevés filmmel szerepel az adatbázisban,
- néhány rendező és színész jelentősen kiemelkedik,
- a filmek értékelései viszonylag kis szórást mutatnak,
- az értékelések száma és a filmek értékelése között bizonyos kapcsolat megfigyelhető.

---

# Repository használata

## Projekt klónozása

```bash
git clone <repository_link>
```

## Könyvtárak telepítése

```bash
pip install -r requirements.txt
```

## Notebook futtatása

```bash
jupyter notebook
```

---

# Megjegyzés

A projekt oktatási célból készült a Budapesti Corvinus Egyetem  
„A mesterséges intelligencia alapjai” tantárgyának keretében.
