---
tags: matematica, geometria_analitica, funzione
---
# Definizione
L'iperbole è il luogo dei punti tale che sia costante la differenza delle distanze tra i due [[fuoco|fuochi]] F1 e F2.

L'iperbole è formata da 2 rami distinti.
![[Pasted image 20230920225516.png]]
- Il [[punto medio]] è il centro dell'iperbole.
- 2c è la distanza focale, la distanza tra F1 e F2
- 2a è la differenza delle distanze punto-fuoco (anche l'asse trasverso)
-  Il [[segmento]] tra i due [[vertice|vertici]] è detto asse trasverso (2a). 
- 2b è l'asse non trasverso (tra B1 e B2, che sono [[vertice|vertici]] non reali).
- a < c (c è l'[[ipotenusa]])
- ![[Pasted image 20231120202742.png]]

# Equazione canonica dell'iperbole
L'equazione canonica è di un Iperbole con centro in (0 0) e fuochi sull'asse x.

2a è la differenza delle distanze, quindi: 
$$
|\sqrt{{(x+c)^2+y^2}}-\sqrt{{(x-c)^2+y^2}}|=2a
$$
Eliminando il valore assoluto e ponendo
$$
b^2=c^2-a^2
$$
Otteniamo risolvendo:
$$
\frac{x^2}{a^2}-\frac{y^2}{b^2}=1
$$
## Fuochi nell'asse y
$$
\frac{x^2}{a^2}-\frac{y^2}{b^2}=-1
$$

L'iperbole è simmetrica rispetto all'asse x, all'asse y e all'origine.

# [[Asintoto|Asintoti]] dell'iperbole
Un asintoto è:
![[Asintoto]]


![[Pasted image 20230921151604.png]]

$$
y=\frac{b}{a}x \;\;\;\;\;\;\;\; y=-\frac{b}{a}x
$$
# Coordinate fuochi 
Per [[Pitagora]]:
$$
c=\sqrt{a^2+b^2}
$$
quindi
$$
F1=(-\sqrt{a^{2}+b^{2}}\;\;0)
$$
$$
F2=(\sqrt{a^{2}+b^{2}}\;\;0)
$$
(se i fuochi sono sull'asse x è al contrario)

# Eccentricità
L'eccentricità determina l'apertura dei rami dell'iperbole.
$$
e>1
$$
$$
e=\frac{distanza \; focale}{lunghezza \;asse\;trasverso}
$$
quindi se fuochi sull'asse x
$$
e=\frac{c}{a}
$$

# Tipi Particolari
## Iperbole Traslata
Centro non nell'origine, ma assi paralleli agli assi cartesiani
$$
\frac{(x-p)^2}{a^2}-\frac{(y-q)^2}{b^2}=1
$$
![[Pasted image 20231011170829.png]]

## Iperbole Equilatera riferita agli assi di simmetria
se $$
a=b
$$
quindi se fuochi sull'asse x
$$
x^2-y^2=a^2
$$
se sull'asse y
$$
x^2-y^2=-a^2
$$
Con asintoti ([[perpendicolare|perpendicolari]]) 
$$
y=x \;\;\;\;\;y=-x
$$

$$
e=\sqrt2
$$
## Iperbole Equilatera riferita agli asintoti
Il grafico dell'iperbole equilatera ruotato per posizionare gli asintoti sugli assi.
$$
xy=k
$$
$$
k=\frac{a^2}2
$$
quindi x e y inversamente proporzionali.
![[Pasted image 20231011171457.png]]

Fuochi in
$$
c=2\sqrt{|k|}
$$
Vertici in
$$

\begin{cases} 
xy=k  \\
y=x

\end{cases}
$$
$$

\begin{cases} 
xy=k  \\
y=-x

\end{cases}
$$
## Funzione Omografica
Iperbole equilatera riferita agli asintoti traslata
$$
y= \frac{ax+b}{cx+d}
$$
Per non diventare una retta:
$$
c≠0\;\;\;\;\;ad-bc≠0
$$
Gli asintoti sono
$$
y=-\frac{d}{c} \;\;\;\;\;x=\frac{a}{c}
$$
Il centro è all'intersezione degli asintoti:
$$
C(-\frac{d}{c}, \frac{a}{c})
$$

Per capire il verso di rotazione vedo se il punto di intersezione con l'asse y è maggiore o minore dell'[[Asintoto]]:
![[WhatsApp Image 2023-10-11 at 17.23.26.jpeg]]
$$
k=\frac{bc-ad}{c^2}
$$
Fuochi 
$$
-\frac{d}{c}±\sqrt {2k},\;\;\frac{a}{c}±\sqrt {2k}
$$
Vertici
$$
-\frac{d}{c}±\sqrt k\;\;\frac{a}{c}±\sqrt {k}
$$

### Funzione Omografica dal Grafico 
dividiamo tutto per c
$$
y= \frac{\frac{a}{c}x+\frac{b}{c}}{x+\frac{d}{c}}
$$
Ora abbiamo 3 incognite e possiamo svolgere.