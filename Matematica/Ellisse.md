---
tags: matematica, geometria_analitica, funzione
---
# Definizione
Luogo geometrico dei punti tali che sia costante la somma delle distanze tra un [[punto]] e i due [[fuoco|fuochi]] F1 e F2
![[Drawing 2023-09-20 22.26.47.excalidraw]]

$$
PF1+PF2=costante
$$
- Il [[punto medio]] tra i due [[fuoco|fuochi]] è il centro dell'Ellisse
- 2c è la distanza focale, la distanza tra F1 e F2
- 2a è la somma delle distanze punto-fuoco (anche l'asse maggiore)
- 2b è l'asse minore
- a è il semiasse maggiore e b il semiasse minore

Se i fuochi sono sull'asse x l'asse maggiore è orizzontale
se sono sull'asse y è verticale.

## a>c e a>b
- c è sempre minore di a perchè in ogni [[triangolo]] un lato è minore della somma degli altri 2.
- a è maggiore di b perchè [[ipotenusa]].
![[Drawing 2023-09-20 22.32.35.excalidraw]]

## Coordinate fuochi
![[Drawing 2023-09-20 22.32.35.excalidraw 1]]
Per [[Pitagora]]:
$$
c=\sqrt{a^2-b^2}
$$
quindi
$$
F1=(-\sqrt{a^{2}-b^{2}}\;\;0)
$$
$$
F2=(\sqrt{a^{2}-b^{2}}\;\;0)
$$
(se i fuochi sono sull'asse x è al contrario)

## [[equazione]] canonica
L'equazione canonica è di un ellisse con centro in (0 0) e fuochi sull'asse x.
2a è la somma delle distanze, quindi
$$
\sqrt{{(x+c)^2+y^2}}+\sqrt{{(x-c)^2+y^2}}=2a
$$
Usando [[Pitagora]]:
$$
a^2=c^2+b^2
$$
Risolvendo si ottiene
$$
\frac{x^2}{a^2}+\frac{y^2}{b^2}=1
$$

Una [[Circonferenza_old]] con centro in (0,0) e r=a
$$
x^2+y^2=a^2
$$
$$

\frac{x^2}{a^2}+\frac{y^2}{a^2}=1

$$
Quindi la [[Circonferenza_old]] è un ellisse con assi di lunghezza uguale dove i fuochi coincidono.

- a = b [[Circonferenza_old]] 
- a > b fuochi asse x
- a < b fuochi asse y

## Eccentricità
L'eccentricità determina lo schiacciamento dell'ellisse.
Per l'ellisse:
$$
0\le e \le1
$$
$$
e=\frac{distanza \; focale}{lunghezza \;asse\;maggiore}
$$
quindi se fuochi sull'asse x
$$
e=\frac{c}{a}
$$

- Se e=0 [[Circonferenza_old]] degenere.
- Se e=1 [[segmento]] degenere.
- e non può essere maggiore di 1 perchè altrimenti i fuochi sarebbero esterni all'ellisse.
![[Drawing 2023-09-20 22.47.16.excalidraw]]


![[Coniche#Condizione di realtà dell' Ellisse]]