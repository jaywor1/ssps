# Maths 🧮

## Kombinatorika

### Faktoriál

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

$$ {n \ge -1  \cap n \in Z} $$

$$ {(n+3)! \over (n+1)!} = {(n+1)! * (n+2) * (n+3) \over (n+1)!} = (n+2)(n+3) = n^2 + 5n + 6 $$

### Uprav + podm.:

$$ {1 \over n!} - {1 \over (n+1)!} $$

#### Řešení

$$ n \ge 0 \cap n \in Z $$

$$ {1 \over n!} - {1 \over (n+1)!} = {n+1-1 \over n!(n+1)} = {n \over (n+1)!} = {1 \over (n-1)(n+1)} = {1 \over n^2 - 1} $$

### Uprav + podm.:

$$ {(n-2)! \over (n-4)!} $$

#### Řešení

$$ n \ge 2 \cap n \in Z $$

$$ {(n-2)! \over (n-4)!} =  {(n-2)(n-3)(n-4)! \over (n-4)!} = (n-2)(n-3) = n^2 -5n + 6 $$

### Odstraň faktoriály + podm.:

$$ {(n-6)! \over (n-5)!} - {(n+7)! \over (n+5)!} $$

#### Řešení

$$ n \ge 6 \cap n \in Z  $$

$$ {(n-6)! \over (n-5)!} - {(n+7)! \over (n+5)!} = {(n-6)! \over (n-5)(n-6)!} - {(n+7)(n+6)(n+5)! \over (n+5)!} = {1 \over (n-5)} - {(n+7)(n+6)} = $$