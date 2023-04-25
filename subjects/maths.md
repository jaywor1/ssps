# Maths 🧮

## Kombinatorika - Faktoriál

#### Definice
$$ n! = n * (n-1) * (n-2) ... 3 * 2 * 1 $$
$$ n \in Z^+ $$
$$ 0! = 1 $$

#### Úpravy
$$ {11! \over 9!} = {11\*10\*9! \over 9!} = 11 * 10 = 110 $$

#### Příklady
Vypočítej $4!$:

$$ 4! = 4 * 3 * 2 * 1 $$

### Uprav + podm.:

$$ {(n+3)! \over (n+1)!} $$

#### Řešení

$$ n \ge -1  ; n \in Z $$

$$ {(n+3)! \over (n+1)!} = {(n+1)! * (n+2) * (n+3) \over (n+1)!} = (n+2)(n+3) = n^2 + 5n + 6 $$

### Uprav + podm.:

$$ {1 \over n!} - {1 \over (n+1)!} $$

#### Řešení

$$ n \ge 0 ; n \in Z $$

$$ {1 \over n!} - {1 \over (n+1)!} = {n+1-1 \over n!(n+1)} = {n \over (n+1)!} = {1 \over (n-1)(n+1)} = {1 \over n^2 - 1} $$

### Uprav + podm.:

$$ {(n-2)! \over (n-4)!} $$

#### Řešení

$$ n \ge 2 ; n \in Z $$

$$ {(n-2)! \over (n-4)!} =  {(n-2)(n-3)(n-4)! \over (n-4)!} = (n-2)(n-3) = n^2 -5n + 6 $$

### Odstraň faktoriály + podm.:

$$ {(n-6)! \over (n-5)!} - {(n+7)! \over (n+5)!} $$

#### Řešení

$$ n \ge 6 ; n \in Z  $$

$$ {(n-6)! \over (n-5)!} - {(n+7)! \over (n+5)!} = {(n-6)! \over (n-5)(n-6)!} - {(n+7)(n+6)(n+5)! \over (n+5)!} = {1 \over (n-5)} - {(n+7)(n+6)}$$

### Uprav + podm.:
$$ {n! \over (n-3)!} + {(n+1)! \over (n-2)!} + {(n+2)! \over (n-1)!} - (n^2 + 4) $$

#### Řešení

$$ n \ge 3 ; n \in Z $$

$$ {n! \over (n-3)!} + {(n+1)! \over (n-2)!} + {(n+2)! \over (n-1)!} - (n^2 + 4) = n(n-1)(n-2) + n(n+1)(n-1) + n(n+2)(n+1) - n^2 -4 = 3n^3 - n^2 + 3n - 4 $$

## Kombinatorika - Rovnice s faktoriály

### Příklady

#### Vyřeš rovnici

Podmínka:

$$ n \ge 5;n \in Z $$

Řešení rovnice:

$$ {(n+6)! \over (n+4)!} - n * {(n-4)! \over (n-5)!} = 5n + 80 $$

$$ (n+6)(n+5) - n(n-4) = 5n + 80 $$

$$ n^2 + 11n + 30 - n^2 + 4n = 5n + 80 $$

$$ 15n + 30 = 5n + 80 $$

$$ 10n = 50 $$

$$ n = 5 $$

Vyřeš rovnici:

$$ (n+2)! * n! = 24(n+1)!(n-1)! $$

$$ {(n+2)! * n! \over (n+1)! (n-1)!} = 24 $$

$$ n^2 +2n = 24 $$

$$ n^2 + 2n - 24 = 0 $$

Řešení kvadratické rovnice:

$$ D = b^2 - 4ac = 4 + 96 = 100 $$

$$ n_1,n_2 = { -2 \pm \sqrt{4+96} \over 2} = {-2 \pm 10 \over 2} $$

$$ n_1 = -6 $$
$$ n_2 = 4 $$

Podmínka rovnice:

$$ n \ge 1;n \in Z $$

Řešení rovnice:

$$ K = \lbrace 4 \rbrace  $$

## Kombinatorika - Kombinační číslo

$$ {\binom{n}{k}} = {n! \over k!(n-k)!}$$

"n nad k"

$$ {n,k \in N_0};{n \ge k} $$

$$ {\binom{n}{n}} = 1 $$

$$ {\binom{n}{0}} = 1 $$

$$ {\binom{n}{n-1}} = n $$

$$ {\binom{n}{1}} = n $$

$$ {\binom{n}{n-k}} = {n! \over (n-k)!(k)!} = {\binom{n}{k}} $$
