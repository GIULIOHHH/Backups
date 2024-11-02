---
tags: matematica, geometria_analitica, funzione
---
# Definizione
Insieme di punti allineati dello spazio.

- Tutte le rette sono [[iniettiva|iniettive]], tranne quella costante. 

A ogni retta corrisponde un [[equazione]] lineare:

in forma implicita:
$$
ax+by+c=0
$$
in forma esplicita:
$$
y=-{\frac{a}{b}}x-{\frac{c}{b}}
$$
$$
-{\frac{a}{b}} =m
$$
$$
-{\frac{c}{b}}=q
$$
quindi:
$$
y=mx+q
$$
![[Pasted image 20230914174025.png|300]]

q è il punto d'intersezione con l'asse y.


m è il coefficiente angolare, determina la pendenza della retta ed è uguale alla [[Tangente]] dell'angolo:
- se m>0 retta crescente
- se m<0 retta decrescente
- se m=0 retta costante

# Se a=0 / m=0
![[Pasted image 20230914174126.png|300]]
$$
y=q
$$
si ha una retta parallela all'asse x, [[funzione]] non [[iniettiva]] .

# Se b=0 
![[Pasted image 20230914174302.png|300]]
$$
x=-{\frac{q}{m}}
$$
si ha una retta parallela all'asse y, Non è [[funzione]].

# Se c=0 (retta passante per l'origine)
![[Pasted image 20230914174419.png]]
$$
y=mx
$$

La retta passa per l'origine.
- se m >0 passerà per il 1 e il 3 quadrante
- se m<0 per il 2 e il 4

# Posizione reciproca
$$

\begin{cases} 
a_1x+b_1y+c_1=0 \\
a_2x+b_2y+c_2=0
\end{cases}
$$
Se questo sistema:
- è determinato le rette sono incidenti (le soluzioni sono le coordinate)
- è impossibile le rette sono parallele
- è indeterminato le rette sono coincidenti.

Rette parallele:
$$
m_1=m_2
$$
Rette incidenti:
$$
m_1≠m_2
$$
Rette coincidenti:
$$
y_1=y_2
$$
Rette [[perpendicolare|perpendicolari]] ([[antireciproco|antireciproche]]):
$$
m_1=-\frac{1}{m_{2}}
$$


# Fascio di Rette
2 tipi di fasci:
- Proprio se tutte le rette si incontrano in un [[punto]] P detto __Centro Del fascio__
	- Se x1 e y1 sono il centro del fascio:$$
y-y_1=m(x-x_{1)}\;\;\;V\;\;\;x=x_1
$$
Quest'equazione rappresenta il fascio. (x=x1 è per la retta verticale che non si può rappresentare normalmente)
![[Pasted image 20230920193656.png]]
- Improprio se sono tutte parallele
![[Pasted image 20230920193644.png|300]]

## Fasci generati da due rette
I fasci possono essere generati da 2 rette, __R__ e __S__.
Per scrivere questi fasci dobbiamo usare una [[combinazione lineare]].
(__P__ e __Q__ si chiamano [[parametri]])
$$
p(a_1x+b_1y+c_1)+q(a_2x+b_2y+c_2)
$$
possiamo porre
$$
k=\frac{p}{q}
$$
quindi 
$$
a_1x+b_1y+c_{1}+k(a_2x+b_2y+c_2)
$$
La prima è la retta se k=0 (__S__), la seconda è la retta all'infinito.

L'unica retta che questo non rappresenta è __Q__.
Se dividiamo tutto per k
$$
\frac{1}{k}(a_1x+b_1y+c_{1})+a_2x+b_2y+c_2
$$
K non può essere 0 ma più si avvicina più ci avviciniamo a __Q__
QUINDI:
>Per K tendente all'infinito 1/K tende a 0

$$
k-->\infty \;\;\;\;\;\;\frac{1}{k}-->0
$$



Per controllare se un fascio di rette generato da 2 rette è proprio o improprio; basta vedere se sono parallele.


# Formule retta
## 1 punto, m = equazione retta

$$
y-y1=m(x-x1)
$$
## 2 punti = equazione retta
$$
\frac{{y-y1}}{{y2-y1}}=\frac{{x-x1}}{{x2-x1}}
$$
## 2 punti = m
$$
m= \frac{{yb-ya}}{{xb-xa}}
$$
## Distanza [[punto]]-retta
$$
d= \frac{|ax+by+c|}{\sqrt{a^2+b^{2}}}
$$
- x e y sono le coordinate del [[punto]] 
- a, b, c sono la [[Retta]] 
- la distanza non può essere negativa, per questo il [[Valori assoluti|Valore assoluto]] 
- La distanza [[punto]]-retta minore è sempre un [[segmento]] [[perpendicolare]].

