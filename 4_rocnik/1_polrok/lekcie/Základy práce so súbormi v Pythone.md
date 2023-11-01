# Obsah

1. Základy práce so súbormi v Pythone
  - Otvorenie súboru (funkcia open)
  - Čítanie zo súboru
  - Zápis do súboru
  - Zatvorenie súboru (kontextový manažér with)

2. Práca so súbormi rôznych formátov
  - Textové súbory
  - CSV súbory
  - Binárne súbory

3. Manipulácia s dátami
  - Rozdelenie a spojenie reťazcov
  - Spracovanie a konverzia dát
4. Pokročilé techniky zapisovania a čítania dát
  - Použitie regulárnych výrazov
  - Parsovanie štruktúrovaných dát
5. Projekt: Analýza a transformácia dát bez použitia knižníc
  - Načítanie dát zo súboru
  - Transformácia dát
  - Uloženie dát do nového súboru
6. Pokročilý projekt: Vytvorenie vlastného formátu súboru
  - Definovanie vlastného formátu súboru
  - Zápis a čítanie dát v tomto formáte

## Príklad: Parsovanie štruktúrovaných dát

Predpokladajme, že máte súbor s dátami vo formáte CSV a chcete ich spracovať bez knižnice csv.

### Načítanie CSV súboru a parsovanie dát

``` python
with open('data.csv', 'r') as file:
 riadky = file.readlines()
 hlavicka = riadky[0].strip().split(',')
 data = [riadok.strip().split(',') for riadok in riadky[1:]]
```

### Vypísanie hlavičky a niekoľkých riadkov dát

``` python
print(hlavicka)
print(data[:5])
```

## Príklad 3: Vytvorenie vlastného formátu súboru

Predpokladajme, že chcete vytvoriť vlastný formát súboru pre ukladanie dát. Tu vytvoríme jednoduchý
formát pre uloženie zoznamu osôb s menom a vekom.

### Vytvorenie vlastného formátu súboru

``` python
osoby = [
 {'Meno': 'John', 'Vek': 25},
 {'Meno': 'Alice', 'Vek': 30},
 {'Meno': 'Bob', 'Vek': 22},
]
with open('osoby.txt', 'w') as file:
 for osoba in osoby:
 file.write(f"Meno: {osoba['Meno']}, Vek: {osoba['Vek']}\n")
```

### Čítanie vlastného formátu súboru

``` python
nove_osoby = []
with open('osoby.txt', 'r') as file:
 for riadok in file:
 if 'Meno:' in riadok and 'Vek:' in riadok:
 meno = riadok.split('Meno: ')[1].split(', Vek:')[0]
 vek = int(riadok.split('Vek: ')[1])
 nove_osoby.append({'Meno': meno, 'Vek': vek})
print(nove_osoby)
Príklad: Ukladanie a čítanie dát vo formáte CSV
# Údaje na ukladanie vo formáte CSV
data = [
 ["Meno", "Vek", "Mesto"],
 ["John", "30", "New York"],
 ["Alice", "25", "Los Angeles"],
 ["Bob", "35", "Chicago"]
]
```

### Uložíme dáta vo formáte CSV do súboru

``` python
with open('data.csv', 'w') as csv_file:
 for riadok in data:
 csv_file.write(",".join(riadok) + "\n")
```

### Čítanie dát zo súboru vo formáte CSV

``` python
nacitane_data = []
with open('data.csv', 'r') as csv_file:
 for riadok in csv_file:
 nacitane_data.append(riadok.strip().split(','))
print(nacitane_data)
```

## Príklad: Ukladanie a čítanie dát vo formáte TSV

### Údaje na ukladanie vo formáte TSV

``` python
data = [
 ["Meno", "Vek", "Mesto"],
 ["John", "30", "New York"],
 ["Alice", "25", "Los Angeles"],
 ["Bob", "35", "Chicago"]
]
```

### Uložíme dáta vo formáte TSV do súboru

``` python
with open('data.tsv', 'w') as tsv_file:
 for riadok in data:
 tsv_file.write("\t".join(riadok) + "\n")
```

### Čítanie dát zo súboru vo formáte TSV

``` python
nacitane_data = []
with open('data.tsv', 'r') as tsv_file:
 for riadok in tsv_file:
 nacitane_data.append(riadok.strip().split('\t'))
print(nacitane_data)
```

## Príklad 1: Analýza frekvencie slov v texte s použitím Pandas

Teória: Analýza frekvencie slov je dôležitou súčasťou spracovania textových dát. Pomáha identifikovať
najčastejšie používané slová v texte.

``` python
import pandas as pd
from collections import Counter
import matplotlib.pyplot as plt
```

### Príklad textu

``` python
text = "Toto je príklad textu. Text môže obsahovať slová. Príklad textu."
```

### Rozdelenie textu na slová

``` python
slova = text.split()
```

### Počítanie frekvencie slov

``` python
frekvencia_slov = Counter(slova)
```

### Konverzia frekvencie slov na DataFrame

``` python
df = pd.DataFrame.from_dict(frekvencia_slov, orient='index', columns=['Frekvencia'])
```

### Zoradenie podľa frekvencie

``` python
df = df.sort_values(by='Frekvencia', ascending=False)
```

### Vizualizácia

``` python
df.plot(kind='bar')
plt.title('Frekvencia slov v texte')
plt.xlabel('Slovo')
plt.ylabel('Frekvencia')
plt.show()
```

Tento skript rozdelí text na slová, spočíta frekvenciu každého slova a potom vizualizuje najčastejšie
používané slová vo forme stĺpcového grafu.

## Príklad 2: Analýza sentimentu textu pomocou knižnice TextBlob a Pandas

Teória: Analýza sentimentu textu sa používa na určenie emocionálneho tónu v texte, či je pozitívny,
negatívny alebo neutrálny.

``` python
from textblob import TextBlob
import pandas as pd
```

### Príklad textu

``` python
text = "Toto je skvelý produkt. Som s ním veľmi spokojný."
```

### Analýza sentimentu

``` python
blob = TextBlob(text)
sentiment = blob.sentiment
```

### Vytvorenie DataFrame

``` python
df = pd.DataFrame({'Text': [text], 'Sentiment': [sentiment]})
```

### Výsledok analýzy sentimentu

``` python
print(df)
```

V tomto príklade používame knižnicu TextBlob na analýzu sentimentu textu. Výsledok analýzy
sentimentu (polarita a subjektivita) sa uloží do Pandas DataFrame.

## Príklad 3: Analýza entít (osôb, miest) v texte s využitím spaCy a Pandas
Teória: Analýza entít identifikuje dôležité entity v texte, ako sú mená osôb, miesta, dátumy a ďalšie.

``` python
import spacy
import pandas as pd
```

### Načítanie modelu jazyka

``` python
nlp = spacy.load("en_core_web_sm")
```

### Príklad textu

``` python
text = "Steve Jobs bol zakladateľom Apple. Apple sídli v Kalifornii."
```

### Spracovanie textu spaCy

``` python
doc = nlp(text)
```

### Extrahovanie entít

``` python
entity_list = [(ent.text, ent.label_) for ent in doc.ents]
```

### Vytvorenie DataFrame

``` python
df = pd.DataFrame(entity_list, columns=['Entita', 'Typ'])
``` 

### Výsledok analýzy entít

``` python
print(df)
```

V tomto príklade používame knižnicu spaCy na extrahovanie entít z textu. Výsledné entity a ich typy sa
ukladajú do Pandas DataFrame.

Tieto príklady demonštrujú, ako môžete analyzovať textové dáta s využitím knižníc NumPy a Pandas na
rôzne účely, ako je analýza frekvencie slov, sentimentu textu a identifikácia entít

November:
Lineárna regresia je štatistická metóda, ktorá sa používa na modelovanie vzťahu medzi nezávislou
premennou (X) a závislou premennou (Y). Týmto modelovaním sa snažíme nájsť lineárnu funkciu, ktorá
čo najlepšie popisuje túto závislosť. Model lineárnej regresie je v tvare Y = aX + b, kde "a" je sklon
(koeficient regresie) a "b" je konštanta (posun). Cieľom lineárnej regresie je nájsť optimálne hodnoty pre
"a" a "b", ktoré minimalizujú chyby medzi skutočnými a predpovedanými hodnotami Y.
Teraz vytvoríme skript v Pythone na vygenerovanie náhodných dát, vytvorenie lineárneho modelu
regresie a vizualizáciu výsledkov.

``` python
import numpy as np
import matplotlib.pyplot as plt
from sklearn.linear_model import LinearRegression
```

### Vygenerovanie náhodných dát

``` python
np.random.seed(0)
X = 2 * np.random.rand(100, 1) # Nezávislá premenná X
Y = 4 + 3 * X + np.random.randn(100, 1) # Závislá premenná Y s pridaným šumom
```

### Vizualizácia dát

``` python
plt.scatter(X, Y, c='b', label='Skutočné dáta')
plt.xlabel('Nezávislá premenná (X)')
plt.ylabel('Závislá premenná (Y)')
```

### Vytvorenie a trénovanie modelu lineárnej regresie

``` python
regressor = LinearRegression()
regressor.fit(X, Y)
```

### Predpovedanie hodnôt

``` python
X_nove = np.array([[0], [2]])
Y_predikcia = regressor.predict(X_nove)
```

### Vizualizácia regresného modelu

``` python
plt.plot(X_nove, Y_predikcia, c='r', label='Regresný model')
plt.legend()
plt.show()
```

1. Importujeme potrebné knižnice, ako numpy na generovanie náhodných dát, matplotlib na
vizualizáciu a scikit-learn na modelovanie regresie.
2. Generujeme náhodné dáta pre nezávislú premennú (X) a závislú premennú (Y). Závislá
premenná obsahuje aj náhodný šum, aby bola situácia reálnejšia.
3. Vizualizujeme skutočné dáta pomocou rozptylového grafu.
4. Vytvoríme inštanciu modelu lineárnej regresie z knižnice scikit-learn.
5. Trénujeme model na trénovacích dátach (X, Y) pomocou metódy fit().
6. Vytvoríme nové hodnoty pre nezávislú premennú (X_nove), pre ktoré chceme predpovedať
hodnoty Y (Y_predikcia) pomocou modelu.
7. Vizualizujeme regresný model (červená čiara) spolu so skutočnými dátami (modré body).

Model lineárnej regresie vytvoril lineárnu funkciu, ktorá sa čo najlepšie prispôsobila skutočným
dátam. Táto funkcia umožňuje predpovedať hodnoty Y pre zadané hodnoty X.
