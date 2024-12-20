---
tags: matematica
---

# Definizione                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              
Una matrice $m*n$ è formata da $m*n$ elementi con $m$ righe (x) e $n$ colonne (y). Le matrici si indicano con lettere maiuscole (di solito $A$)

Se $m=n$ la matrice è quadrata, altrimenti è rettangolare.

I numeri della matrice sono detti elementi e si indicano con $a_{y,x}$
$$
\begin{bmatrix}a_{1,1}\;\;a_{1,2}\;\;a_{1,3} \\ a_{2,1}\;\;a_{2,2}\;\;a_{2,3} \\ a_{3,1}\;\;a_{3,2}\;\;a_{3,3}\end{bmatrix}
$$
# Tipi di matrici
Due matrici sono __dello stesso tipo__ se sono delle stesse dimensioni (stesse righe stesse colonne).
Gli elementi di entrambi si dicono __Elementi corrispondenti__. 
- Se gli elementi corrispondenti sono uguali si hanno __Matrici uguali__
- Se gli elementi corrispondenti sono opposti si hanno __Matrici opposte__

	Una matrice formata da una sola riga è una __matrice riga__
	Una matrice formata da una sola colonna è una __matrice colonna__

Una matrice è nulla se tutti i suoi elementi sono 0, si indica con $O$ oppure $O_{mn}$

La matrice trasposta di $A$, $A^T$ si ottiene scambiando le righe con le colonne (ruotando la matrice)

$$
\begin{bmatrix}1\;\;2\;\;3 \\ 4\;\;5\;\;6\end{bmatrix}->\begin{bmatrix}1\;\;4 \\ 2\;\;5\\3\;\;6\end{bmatrix}
$$
## Matrici quadrate
L'ordine di una matrice quadrata è il numero di righe/colonne.

__La diagonale principale di una matrice quadrata va dall'angolo in alto a destra a quello in basso a sinistra__ (da $a_{1,1}$ a $a_{n,n}$)

$$
\begin{bmatrix}X\;\;a_{1,2}\;\;a_{1,3} \\ a_{2,1}\;\;X\;\;a_{2,3} \\ a_{3,1}\;\;a_{3,2}\;\;X\end{bmatrix}
$$
__La diagonale secondaria di una matrice quadrata va dall'angolo in basso a destra a quello in alto a sinistra__ (da $a_{n,1}$ a $a_{1,n}$)
$$
\begin{bmatrix}a_{1,1}\;\;a_{1,2}\;\;X \\ a_{2,1}\;\;X\;\;a_{2,3} \\ X\;\;a_{3,2}\;\;a_{3,3}\end{bmatrix}
$$

Una matrice quadrata è __diagonale__ se tutti gli elementi sono nulli tranne quelli della diagonale principale 

Una matrice diagonale è __identica__ (o unitaria) se tutti gli elementi sono nulli, tranne quelli della diagonale principale che sono tutti 1. Si scrive con $I_n$ (n è l'ordine)


# Determinante

Associamo ad ogni matrice *QUADRATA* un numero intero detto __Determinante__.
Lo possiamo indicare scrivendo $det\: A$ oppure sostituendo le parentesi quadre con 2 linee.
$$
det\:A=\begin{bmatrix}a_{1,1}\;\;a_{1,2}\;\;a_{1,3} \\ a_{2,1}\;\;a_{2,2}\;\;a_{2,3} \\ a_{3,1}\;\;a_{3,2}\;\;a_{3,3}\end{bmatrix}
\;oppure\;\begin{vmatrix}a_{1,1}\;\;a_{1,2}\;\;a_{1,3} \\ a_{2,1}\;\;a_{2,2}\;\;a_{2,3} \\ a_{3,1}\;\;a_{3,2}\;\;a_{3,3}\end{vmatrix}$$

Il determinante di una matrice di primo ordine è il singolo elemento.
$$
det[a]=a
$$
Il determinante di una matrice di secondo ordine è il prodotto della diagonale principale meno il prodotto della diagonale secondaria.
$$
\begin{vmatrix}a\;\;b  \\ c\;\;d\end{vmatrix}=(a*d)-(b*c)
$$
Il determinante di una matrice di terzo ordine si può calcolare con la 
# Regola di Sarrus
>Valida solo per le matrici di terzo ordine.
$$
\begin{vmatrix}1\;\;2\;\;3 \\ 4\;\;5\;\;6 \\ 7\;\;8\;\;9\end{vmatrix}
$$

Ricopiamo a destra gli elementi delle prime 2 colonne.
$$
\begin{vmatrix}1\;\;2\;\;3\;|1\;\;2 \\ 4\;\;5\;\;6\;|4\;\;5 \\ 7\;\;8\;\;9\;| 7\;\;8 \\ \end{vmatrix}$$
Moltiplichiamo i termini lungo la diagonale principale e quelle parallele.
$$
\begin{vmatrix}X\;\;Y\;\;Z\;|1\;\;2 \\ 4\;\;X\;\;Y\;\:|Z\;\;5 \\ 7\;\;8\;\;X\;\;| Y\;\;Z \\ \end{vmatrix}$$
Ripetiamo il procedimento lungo la diagonale secondaria 
$$
\begin{vmatrix}1\;\;2\;\;Z\;|Y\;\;X \\ 4\;\;Z\;\;Y\;|X\;\;5 \\ Z\;\;Y\;\;X\;| 7\;\;8 \\ \end{vmatrix}$$
Il determinante è dato dal primo prodotto meno il secondo prodotto.

Il determinante delle matrici di terzo ordine si può ottenere anche con il 
# Complemento algebrico
Vale per qualsiasi ordine di matrice.

- Gli elementi la cui somma degli indici è un numero pari sono detti di __Classe pari__ ($a_{1,1}$, perchè $1+1=2$)
- Gli elementi la cui somma degli indici è un numero dispari sono detti di __Classe dispari__ ($a_{2,1}$, perchè $2+1=3$)

Il determinante di una matrice di ordine $n$ è dato dalla somma di ogni elemento di una riga o colonna moltiplicato per il suo complemento algebrico.

Il complemento algebrico di un elemento si ottiene rimuovendo la riga e la colonna a cui appartiene l'elemento e poi calcolando il determinante.
Se l'elemento è di classe pari aggiungiamo il segno +, Altrimenti se è di classe dispari il segno -.

### Ad esempio 
Scelgo la prima riga:
$$
\begin{vmatrix}1\;\;2\;\;3 \\ 4\;\;5\;\;6 \\ 7\;\;8\;\;9\end{vmatrix}
$$
$$
det\:A=a_{1,1}*A_{1,1}+a_{1,2}*A_{1,2}+a_{1,3}*A_{1,3}
$$

$$
A_{1,1}=
\begin{vmatrix}X\;\;X\;\;X \\X\;\;5\;\;6 \\ X\;\;8\;\;9\end{vmatrix}=\begin{vmatrix}5\;\;6 \\ 8\;\;9\end{vmatrix}

$$

$$
A_{1,2}=-\begin{vmatrix}X\;\;X\;\;X \\ 4\;\;X\;\;6 \\ 7\;\;X\;\;9\end{vmatrix}=\begin{vmatrix}4\;\;6 \\ 7\;\;9\end{vmatrix}
$$
# Matrice inversa
Una matrice inversa di una matrice quadrata $A$, $A^{-1}$ è tale che:
$$
A*A^{-1}=A^{-1}*A
$$
inoltre
$$
A^{-1}*A=I_n
$$
Per ammetere una matrice inversa, il determinante di una matrice deve essere $≠0$ Se la ammette è detta invertibile.

data una matrice di secondo ordine
$$
A^{-1}=\frac{1}{det\:A}*\begin{vmatrix}d\;\;-b  \\ -c\;\;a\end{vmatrix}
$$

Data una matrice di ordine $n$:
Sostituiamo ogni elemento col suo reciproco, ovvero il suo complemento algebrico, diviso il determinante di tutta la matrice.

Ad esempio il reciproco di $a_{1,1}$ è $\frac{A_{1,1}}{D}$
