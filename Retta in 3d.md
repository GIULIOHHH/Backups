
# Equazioni Cartesiane
## 2d
in due dimensioni, l'equazione di una retta dati due punti è
$$
\frac{y-y_1}{y_2-y_1}=\frac{x-x_1}{x_2-x_1}
$$
 $y_2-y_1$ e $x_2-x_1$ sono numeri, quindi possiamo scrivere
$$
\frac{y-y_1}{a}=\frac{x-x_1}{b}
$$
$a$ e $b$ formano un vettore che viene ripetuto per formare la retta.  $v=(a,b)$
![[Pasted image 20250604110726.png]]

>Quindi una retta può essere definita da un punto e un vettore.

## 3d
In tre dimensioni
$$
\frac{y-y_1}{y_2-y_1}=\frac{x-x_1}{x_2-x_1}=\frac{z-z_1}{z_2-z_1}
$$
$$
\frac{y-y_1}{a}=\frac{x-x_1}{b}=\frac{z-z_1}{c}
$$
# Equazioni parametriche
## 2d
Sappiamo che
$$
\frac{y-y_1}{a}=\frac{x-x_1}{b}
$$
Dato che hanno lo stesso valore:
$$
\frac{y-y_1}{a}=\frac{x-x_1}{b}=k
$$
>Dove $k$ può assumere qualsiasi valore

Quindi
$$
\begin{cases} \frac{y-y_1}{a}=k\\\frac{x-x_1}{b}=k\end{cases}$$
$$
\begin{cases} {y-y_1}=k*a\\{x-x_1}=k*b\end{cases}$$
$$\begin{cases} {y}=y_1+k*a\\{x}=x_1+k*b\end{cases}$$
## 3d
$$\frac{y-y_1}{a}=\frac{x-x_1}{b}=\frac{z-z_1}{c}=k$$
$$\begin{cases} {y}=y_1+k*a\\{x}=x_1+k*b\\z=z_1+k*c\end{cases}$$


# Retta come intersezione di piani
Sapendo che
$$\frac{y-y_1}{a}=\frac{x-x_1}{b}=\frac{z-z_1}{c}$$
Possiamo fare il sistema:
$$\begin{cases} \frac{y-y_1}{a}=\frac{z-z_1}{c}\\\frac{x-x_1}{b}=\frac{z-z_1}{c}\end{cases}$$
$$\begin{cases} c*({y-y_1})=a*({z-z_1})\\c*({x-x_1})=b*({z-z_1})\end{cases}$$

Questo è il sistema tra l'equazione di due piani. (che rappresenta una sola retta).
# Rette particolari
Due rette sono parallele quando sono paralleli i loro vettori.
$$
\frac{a_1}{a_2}=\frac{b_1}{b_2}=\frac{c_1}{c_2}
$$
Due rette sono perpendicolari quando sono perpendicolari i loro vettori.
$$
a_1*a_2+b_1*b_2+c_1*c_2=0
$$


Due rette sono sghembe se non sono parallele ma non si intersecano (sono su piani diversi).
1. Verifichiamo che le rette non sono parallele.
2. Facendo il sistema verifichiamo che non si intersecano (non ha soluzioni).


# Esercizi
- Per passare dalla Retta come intersezione di piani all'equazione parametrica basta imporra $x$, $y$ o $z$ come $=k$

## Distanza Punto Retta
1. Ottengo il vettore direzione della retta.
2. Nell'equazione del piano ($ax+by+cz+d=0$)
	1. Sostituisco $a$ $b$ e $c$ con i parametri del vettore direzione.
	2. Sostituisco $x$ $y$ e $z$ con le coordinate del punto.
		1. Mi trovo $d$.
	3. Rimetto $x$ $y$ e $z$
3. Mi trovo l'intersezione tra piano e retta.