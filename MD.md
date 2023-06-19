### Zadanie: Dla dowolnej liczby całkowietej $n \ge 1$ podzielna przez 3 jest liczba

    a. [TAK] 7^n - 1
    b. [NIE] 8^{3n} + 1
    c. [TAK] 2^{2^n} - 1

### Komentarz:
$7^n \mod 3 = 1^n \mod 3$

$8^{3n} \mod 3 = 2^{3n} \mod 3 = 2^{n} \mod 3$
= 2, 1, 2, 1, ....

$2^{2^n} \mod 3 = 4^{2^{n-1}} \mod 3 = 1^{2^{n-1}} \mod 3$

### Zadanie: Jeżeli $A(x) = \frac{1}{1-x}$, a $B(x)$ jest funkcją tworzącą ciągu $\langle b_n \rangle$ określonego wzorem $b_n = n + 1$, to $C(x) = A(x)B(x)$ jest funkcją tworzącą ciągu określonego wzorem:

    a. [TAK] (n+1)^2 - n(n+1)/2 
    b. [TAK] (n+1) + \sum_{i=0}^{n} i
    c. [NIE] [(n+1)^2 + 1] / 2

### Komentarz:
Funkcja $A$ odpowiada ciągowi $\langle 1 \rangle$, splot z funkcją A odpowiada ciągowi $\langle \sum_{k=0}^n b_k \rangle_n$ dla każdego ciągu $b_n$.

Możemy wyliczyć wyrazy ciągu c i porównać.

### Zadanie: Każdy graf nieplanarny o $n$ wierzchołkach:

    a. [NIE] zawiera podgraf K_{3, 3} lub K_5
    b. [NIE] ma co najmniej 3n-5 krawędzi
    c. [NIE] ma liczbę chromatyczną niemiejszą niż 5

### Komentarz:
a: Nie musi zawierać, wystarczy żeby zawierał podgraf homeomorficzny z jednym z nich. (Kryterium Kuratowskiego).

b: Kryterium Eulera mówi, że jeśli graf jest planarny, to $|E| \le 3|V| - 6$. Nie mówi to nam nic o przypadku, kiedy jest nieplanarny.

c: Kontrprzykład: Graf Petersena o liczbie chromatycznej 3.

### Zadanie: Ciąg określony zbiorem $a_n = |\{ (A, x): A \subset \{1, 2, \dots, n \}, x \in A \}|$, spełnia warunek:

    a. [NIE] lim_{n \to \infty} a_{n+1} / a_n = \infty
    b. [TAK] a_n jest parzyste dla n >= 2
    c. [NIE] a_n = n * n! dla n >= 0

### Komentarz:

Łatwo zauważyć, że:

$$a_n = \sum_{k=1}^n \binom{n}{k}k$$

Ale $\binom{n}{k} = \frac{n}{k} \binom{n - 1}{k - 1}$

Więc $a_n = n \sum_{k=1}^n \binom{n - 1}{k - 1} = n \sum_{k=0}^{n-1} \binom{n}{k}$

Ale $sum_{k} \binom{n}{k} = 2^n$

Więc otzymujemy $a_n = n2^{n-1}$


### Zadanie: G jest grafem o $n \le 6$ wierzchołkach i m krawędziach. Wynika z tego:

    a. [TAK] co najmniej jeden z grafów G i \hat{G}(dopełnienie grafu G) jest planarny
    b. [NIE] jeśli m < 10, to G jest planarny
    c. [NIE] jeśli m > 10, to G jest nieplanarny

### Komentarz:

Kryterium eulera:

$G$ spójny planarny => $|E| \le 3|V| - 6$

a: 
Jeśli G nie jest spójny, to oczywiste.

Jeśli G jest spójny, to może mieć maksymalnie $\binom{6}{2}=15$ krawędzi. Z kryterium Kuratowskiego graj nie jest planarny, jeśli zawiera podgraf homeomorficzny do $K_5$ albo $K_{3, 3}$. Mniej krawędzi wymaga ten drugi, załóżmy, że $G$ zawiera podgraf homeomorficzny do $K_{3, 3}$. Wtedy $\hat{G}$ nie może zawierać żadnego homeomorficznego z nich, bo nie starczy krawędzi.

b: $K_{3, 3}
