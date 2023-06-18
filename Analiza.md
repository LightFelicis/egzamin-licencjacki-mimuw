# Zadania z egzaminów licencjackich z analizy matematycznej

### ZADANIE: $\{S_n\}_{n>=1}$ jest ciągiem sum częściowych szeregu rozbieżnego. Wynika z tego, że ciąg $\{S_{n+1} - S_n\}_{n >= 1}$ jest

    a. [ NIE ] rozbieżny

    b. [ NIE ] nieograniczony

    c. [ NIE ] niezbieżny do 0

### Komentarz:

$\{S_{n+1} - S_n\}_{n >= 1}$ to element $a_{n+1}$ szeregu.
Warunkiem koniecznym (ale nie dostatecznym) na zbieżność szeregu jest $\texttt{lim}_{a_n -> \infty} = 0$.

Weźmy $a_n = \frac{1}{n}$, ten ciąg zbiega do $0$, ale suma takich składników jest rozbieżna.
Stąd szereg może być rozbieżny, a elementy zbieżne do 0 i ograniczone.


### ZADANIE: Funkcja $f : [0; 1] -> R$ jest różniczkowalna oraz $f(0) = 1$, $f(1) = 0$. Wynika z tego, że istnieje $x \in [0; 1]$, dla którego $f'(x)$ jest

    a. [ TAK ] mniejsze od 0

    b. [ TAK ] równe $-1$

    c. [ NIE ] większe bądź równe $1$

### Komentarz:

Funkcja jest różniczkowalna, czyli można skorzystać z twierdzenia o wartości średniej, które mówi, że na $(a, b)$ będzie taka wartość $c$, że

$$
f'(c) = \frac{f(b) - f(a)}{b - a}
$$

W tym przypadku to będzie $-1$.

#### ZADANIE: Ciąg funkcyjny $\{f_n\}_{n>=1}$ składa się z funkcji $f_n: R -> R$ zdefiniowanych jako $f_n(x) = x - \frac{1}{n}$ dla dowolnego rzeczywistego R. Ten ciąg jest

    a. [ ] zbieżny punktowo i jednostajnie

    b. [ ] niemal jednostajnie zbieżny

    c. [ ] zbieżny punktowo do funkcji ciągłej
