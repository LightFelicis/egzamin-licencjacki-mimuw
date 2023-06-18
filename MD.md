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