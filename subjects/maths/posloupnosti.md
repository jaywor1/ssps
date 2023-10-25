# Posloupnosti

Speciální příklad funkce jehož definiční obor jsou přirozená čísla

## Typy

### Geometrická posloupnost

#### Příklady

---

$ n_n = 3 * n_{n-1} $

$ 2 \dots 6 \dots 18 \dots 54 \dots $

---

$ n_n = 2 * n_{n-1} + 1 $

$ 2 \dots 5 \dots 11 \dots $

---

$ n_n = n_{n-1} + {1\over5} $

$ {1\over5} \dots {2\over5} \dots {3\over5} \dots $

---

$ n_n = 3 * n_{n-1} $

$ 3 \dots 9 \dots 27 \dots $

## Typy zadání

### Vzorcem pro n-tý člen

$$a_n = 3n - 1$$

### Výčtem prvků

```
-4;4;-4;4;-4;4;...
```

### Rekurentně

$$ a_1 = 1; a_{n+1} = 2a_n +1 $$

## Typy posloupností

### Aritmetická

$$a_n=a_1+(n-1) * d$$

$$a_r=a_s+(r-s) * d$$

$$s_n=\frac{n*(a_1+a_n)}{2}$$

### Geometrická

$$a_r=a_s * q^{r-s}$$

$$s_n=n*a_1 ; q = 1$$

$$s_n=a_1*\frac{q^n-1}{q-1} ; q \not= 1;0$$