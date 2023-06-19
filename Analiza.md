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

### Zadanie: Szereg $\sum_{n \ge 1}10^{-n!}$

    a. [TAK] jest zbieżny
    b. [TAK] ma sumę mniejszą od 1/9
    c. [NIE] ma sumę wymierną

### Komentarz:

a i b:
Wzór na szereg geometryczny $\sum_{k \ge 0}x^k = \frac{1}{1-x}$

Wiemy, że $\sum_{n \ge 1}10^{-n!} \le \sum_{n \ge 1}10^{-n}$, więc z kryterium porównawczego zbieżność większego szeregu determinuje zbieżność szeregu w zadaniu.

Ze wzoru na szereg geometryczny:
$\sum_{n \ge 1}10^{-n} = \frac{1}{1-\frac{1}{10}} - 1 = \frac{9}{10}$

c:
Jeśli suma byłaby wymierna, to by miała okresowe rozwinięcie dziesiętne np. 0.(3), 0.1(0).

### Zadanie: Funkcja $f: [0,1] \to R$ jest rosnąca. Wynika z tego, że:

    a. [TAK] zbiór punktów ciągłości funkcji f jest nieprzeliczalny
    b. [NIE] funkcja f jest ciągła poza pewnym zbiorem skończonym
    c. [TAK] funkcja f jest różnowartościowa

### Komentarz:
c: Przyjmujemy, że rosnąca = ściśle rosnąca tzn. $y > x => f(y) > f(x)$.
a i b: Funkcja Cantora nie działa(!)
Jest ważne twierdzenie mówiące, że funkcja monotoniczna na R może mieć co najwyżej skończenie wiele punktów nieciągłości.
https://en.wikipedia.org/wiki/Discontinuities_of_monotone_functions

Skoro dziedzina jest nieprzeliczalna, a zbiór pinktów nieciągłości jest przeliczalny, to musi być nieprzeliczalnie wiele punktów ciągłości.

### Zadanie: Ciąg wielomianów $P_n: R \to R, n=1,2,\dots$ jest zbieżny do funkcji $f: R \to R$ jednostajnie na każdym przedziale $[a, b] \subset R$. Wynika z tego, że funkcja $f$:

    a. [NIE] jest wielomianem
    b. [NIE] jest nieograniczona na R
    c. [NIE] jest różniczkowalna w pewnym punkcie

### Komentarz:
Zbieżność jednostajna na każdym przedziale jest słabszym założeniem niż zbieżność jednostajna na R(!).

Inaczej nazywa to się zbieżność niemal jednostajna.

a: konktrprzykład $\sin x$

c: kontprzykład funkcja weiestrassa (funcja ciągła wszędzie, ale nigdzie nie 
różniczkowalna)

b: To co w a

### Zadanie: Nieskończony ciąg $(a_n)$ liczb rzeczywistych dodatnich jest monotoniczny i ograniczony. Wynika z tego, że

    a. [NIE] ciąg sin(a_n) jest monotoniczny
    b. [TAK] ciąg cos(a_n) jest zbieżny
    c. [NIE] ciąg log(a_n) jest ograniczony

### Komentarz:

a: jaki sinus jest każdy widzi

b: $|\cos a_n| \le a_n$ => jest zbieżny

c: ciąg $\frac{1}{n}$

### Zadanie: Funkcja $f: R \to R$ jest różniczkowalna i $f'(0) = 0$. Wynika z tego, że:

    a. [NIE] f ma w punkcie x = 0 ekstremum lokalne
    b. [TAK] jeśli f'(x) < 0 dla wszystkich x != 0, to f jest malejąca na R
    c. [TAK] f jest ciągła w punkcie x = 2019

### Komentarz:

a: Może mieć punkt przegięcia (musi mieć???)

c: Różniczkowalność implikuje ciągłość

### Zadanie: Szereg $S(x) = \sum_{n \ge 2} a_nx^n$ jest zbieżny dla wszystkich $x \in (-1, 1)$ oraz rozbieżny dla -1. Wynika z tego, że:

    a. [NIE] Szereg S(x) jest rozbieżny dla x = 1
    b. [TAK] Szereg S(x) jest rozbieżny dla x = 2
    c. [TAK] funkcja x -> S(x) jest różniczkowalna na przedziale (-1, 1) oraz S'(0) = 0

### Komentarz:

Słowo klucz promień zbieżności.

c: Szereg potęgowy jest trywialnie różniczkowalny, zauważmy że po zróżniczkowaniu każdy wyraz będzie zawierał x, więc x=0 zeruje.