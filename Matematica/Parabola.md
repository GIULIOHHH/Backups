---
tags: matematica, geometria_analitica, funzione
---
# Definizione parabola
La parabola è il luogo geometrico dei punti equidistanti da
- [[fuoco]]:
![[fuoco]]
$$
(- \frac{b}{2a}\;\; \frac{{1-\Delta}}{4a})
$$
- e [[direttrice]]:
![[direttrice]]

$$
y= -(\frac{{1+\Delta}}{4a})
$$
Invece __L'ASSE DI SIMMETRIA__ è la retta parallela alle y che passa per il [[fuoco]], [[perpendicolare]] alla [[direttrice]].
$$
x=- \frac{b}{2a}
$$
Il __VERTICE__ è il punto in cui la parabola interseca __L'ASSE DI SIMMETRIA__.
$$
(- \frac{b}{2a} \;\;- \frac{\Delta}{4a})
$$

![[Pasted image 20230920201054.png]]

$$
y=ax^2+bx+c
$$
- Se b e c =0 vertice nell'origine
- Se a=0 la parabola diventa una [[Retta]] degenere.

a:
- a >0 concavità verso l'alto
- a<0 verso il basso

b:
aumentando b la parabola si sposta verso sinistra

c:
c sposta il punto d'intersezione con l'asse y

## Asse parallelo alle x
Sono scambiati X e Y
Verso destra a positiva, verso sinistra a negativa.
![[Pasted image 20230920212538.png]]

>Ogni parabola parallela all'asse y è simmetrica rispetto alla [[bisettrice]] del primo e terzo quadrante di una parabola parallela all'asse x

![[Pasted image 20230920212645.png]]

# Parabola e retta
Mettiamo a sistema [[Retta]] e Parabola:
$$

\begin{cases} 
y=ax^2+bx+c  \\
y=mx+q
\end{cases}
$$
se:
- Δ<0 retta esterna
- Δ=0 [[Retta Tangente]]  alla parabola.
- Δ>0 [[Retta Secante]] alla parabola

# Parabola e [[punto]] 
Se un [[punto]]:
- è sulla parabola esiste solo una [[Retta Tangente]] 
- è esterno esistono 2 [[Retta Tangente|Rette Tangenti]] 
- è interno non esistono  [[Retta Tangente|Rette Tangenti]] 

Per trovarli serve la [[Condizione di tangenza]] 
![[Condizione di tangenza]]
## Sulla parabola
possiamo usare la formula di sdoppiamento
$$
\frac{(y+y_{0)}}{2}=ax_{0}x+b \frac{x+x_0}{2}+c
$$
Praticamente:
$$
y\; -> \frac {(y+y_0)}{2}
$$
$$
x\; -> \frac {(x+x_0)}{2}
$$
$$
x^2\; -> x_0x
$$
a, b, c sono i valori della parabola 
x0 e y0 sono le coordinate del [[punto]] 

## [[punto]] esterno
1. metto a sistema la parabola e l'[[equazione]] del fascio di [[Retta|Rette]] che passano per il punto.
$$

\begin{cases} 
y=ax^2+bx+c  \\
y-y_0=m(x-x_0)
\end{cases}
$$
2. Sostituisco la y della [[Parabola]]
3. Impongo la [[Condizione di tangenza]] 
![[Condizione di tangenza]]
4. Mi trovo m tramite la [[Condizione di tangenza]], facendo un altro Δ

Se la parabola ha asse parallelo alle x la [[Retta Tangente]] parallela all'asse y non si può trovare
![[Drawing 2023-09-20 21.51.25.excalidraw|300]]

# Area del [[segmento]] parabolico
Il segmento parabolico è parte di piano tra una Parabola e una [[Retta Secante]].
![[Pasted image 20230920215405.png]]
Archimede ha dimostrato che l'area del segmento parabolico è uguale a 2/3 del rettangolo ABA'B'
$$
segmento\;parabolico=\frac{2}{3}\;rettangolo\;ABA_1B_1
$$
## Retta parallela all'asse x
![[Drawing 2023-09-20 21.56.40.excalidraw]]
1. Metto a sistema [[Retta Secante]] e parabola e trovo i punti di intersezione (A e B).
2. Trovo gli altri due punti usando la y del vertice e la x dei punti trovati A1= (Ax, Vy) B1=(Bx, Vy), 
3. Applico la formula di archimede.
## Retta non parallela

1. 1. Metto a sistema [[Retta Secante]] e parabola e trovo i punti di intersezione (A e B).
2. Dato che cerchiamo un rettangolo le sue basi devono essere parallele, quindi calcolo m della retta data.
3. L'altra retta deve essere [[Retta Tangente|Tangente]] e deve avere la stessa m, quindi le metto a sistema $$

\begin{cases} 
y=ax^2+bx+c  \\
y=mx+q
\end{cases}

$$
4. Per trovare le dimensioni della base calcolo la distanza tra due punti
5. Per trovare le dimensioni dell'[[altezza]] uso la [[Retta#Distanza punto -retta|Distanza punto retta]] tra la [[Retta Tangente]] e uno dei punti di intersezione.