# Statistika 📊
Získávání, zpracovávání a vyhodnecení dat

## Teorie 😴

### Problémy statistiky
- nevalidní data
- klamání zobrazením dat

### Typy diagramů
- kruhový
- sloupcový
- historogram
- spojnicový

### Pojmy
- statistický soubor ... rozsah/počet ... $n$
- statistický znak ... match
    - kvantitativní
        - výška, věk, cena
    - kvalitativní
        - barva, jméno
- hodnota znaku ... $x_i$
    - $x$ - znak
    - $i$ - hodnota
- četnost
    - absolutní $\dots n_i \dots$ součet $= n$
    - relativní $\dots v_i = {n_i \over n} ( * 100 \%) \dots $ součet $= 1 = 100\%$
- tabulka rozdělení četností

| $x_i$   |      <      |  < |
|:-------:|:-----------:|:--:|
| $n_i$   |             |    |

- charakteristika
    - polohy - kde se nachází hodnoty?
    - variabilita - rozptyl

## Praxe 🥳

### Příklad prodané velikosti bot
zadání:

Velikosti bot:
`41,41,41,42,42,41,39,41,40,39,39,42,42,41,40,42,43,42,42,41,45,42,43,43`

#### Rozsah souboru
$n = 24$
#### Tabulka četností

| $x_i$   | 39 |  40 |  41 |  42 |  43 |  45 |
|:-------:|:--:|:--:|:--:|:--:|:--:|:--:|
| $n_i$   |  3 | 2   |  7  |   8 |  3  |  1  |

#### Relativní četnost

$v_{39} = {3\over24} = 12,50 \%$

$v_{40} = {2\over24} = 8,34 \%$

$v_{41} = {7\over24} = 29,17 \%$

$v_{42} = {8\over24} = 33,34 \%$

$v_{43} = {3\over24} = 12,50 \%$

$v_{45} = {1\over24} = 4,17 \%$

Chyba $0,02\%$

#### Vhodný diagram

Kruhový

![image](/images/maths/pie_chart.png)