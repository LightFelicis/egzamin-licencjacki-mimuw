### Zadanie: $A$ jest macierzą o 8 wierszach i 13 kolumnach, taką że $dim(ker(A)) = 5$. Wynika z tego, że:

    a. [NIE] rząd macierzy A jest równy 3
    b. [TAK] rząd macierzy A^T jest równy 8
    c. [NIE] dim(ker A^T) = 5

### Komentarz:

Rząd macierzy to jest liczba $rank A = dim(im A)$

Istnieje twierdzenie, że dla macierzy $X \in K^{m, n}$
$dim(ker X) + dim(im X) = n$

Dodatkowo $rank(A) = rank(A^T) = rank(A^H)$

### Zadanie: $X$ i $Y$ są przestrzeniami liniowymi nad ciałem $R$, $f: X \to Y$ jest przekształceniem liniowym i układ wektorów $x_1, x_2, \dots, x_{10} \in X$ jest bazą przestrzeni $X$. Wynika z tego, że:

    a. [NIE] układ f(x_1), f(x_2),... jest bazą przestrzeni Y
    b. [TAK] jeżeli układ f(x_1), f(x_2),... jest liniowo niezależny, to dim Y >= 10
    c. [TAK] jeżeli układ f(x_1), f(x_2),... jest liniowo niezależny, to przekształcenie f jest różnowartościowe

### Komentarz:
a: kontrprzykład funkcja stała równa 0
b: $dim A$ to liczba niezależnych wektorów rozpinających przestrzeń. Jest ich co najmniej 10.
c: Jeżeli układ f(x) jest niezależny, to $dim im f = dim X$, co jest równoważne, że f jest monomorfizmen aka różnowartościowa.

