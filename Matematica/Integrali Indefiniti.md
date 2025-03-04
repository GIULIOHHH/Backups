
# Primitiva
Una funzione $F(x)$ *(derivabile in $[a,b]$)* è la primitiva di un'altra funzione $f(x)$ *(definita in $[a,b]$)* se:
$$
F^{'}(x)=f(x)
$$
>Quindi data una funzione $y=2x$, le primitive sono $F_1=x^2$, $F_2=x^2+1$... 

Se $F(x)$ è una primitiva di $f(x)$, le funzioni $F(x)+c$ sono le uniche primitive di $f(x)$.
Dove $c$ è un numero reale qualsiasi.
>Dato che la derivata di una costante è $0$, esistono infinite funzioni che se derivate danno lo stesso risultato. (che si differiscono solo per una costante.)
# Integrazione
L'integrale indefinito di una funzione $f(x)$ è l'insieme di tutte le primitive di $f(x)$.

>Una funzione che ha una primitiva è integrabile.

**L'integrazione è l'operazione inversa della derivazione.**

Si indica con:
$$
\int f(x) dx
$$
>- $f(x)$ è la funzione integranda
>- $x$ è la variabile di integrazione
La primitiva che si ottiene se $c=0$ (ovvero $F(x)$) è detta primitiva fondamentale.

>Quindi $$D[\int f(x)dx]=f(x)$$

**Qualsiasi funzione continua è integrabile.**
Esistono funzioni integrabili ma non continue.
![[Pasted image 20250217225140.png]]

>[!example] Come provare a memorizzare:
>Abbiamo $\int f(x)$. L'integrale è la funzione che se derivata è uguale a $f(x).$ 
>
>---
>Ad esempio, qual'è l'integrale di $\int f^{'}(x)*sin[f(x)]dx$?
>Quale funzione se derivata dà $f^{'}(x)*sin(f(x))$?
>$-cos[f(x)]$, quindi la soluzione è $-cos[f(x)]+c$.
# Proprietà degli Integrali

$$
\int (f(x)+g(x)) dx=\int f(x)dx+g(x)dx
$$
$$
\int k*f(x)dx=k*\int f(x) dx
$$
>- Si dice che l'integrale è un operatore lineare.
>- Non esistono proprietà per la divisione o moltiplicazione.
# Integrali immediati
>[!info] 
>La dimostrazione si ottiene derivando il risultato dell'integrale.

>$dx$ e $+c$ sono stati omessi.

Integrali da Sapere
---

## **SE** $a\neq -1 \;\;\int x^a=\frac{x^{a+1}}{a+1}$ 
>Se $a=-1$ il denominatore sarebbe $0$.
## **SE** $a=-1 \;\;\int \frac{1}{x}=ln|x|$ 
>Usiamo il valore assoluto perchè così possiamo passare nel logaritmo anche valori negativi.
## $\int \frac{1}{1+x^2}=arctan(x)$
## $\int \frac{1}{\sqrt{1-x^2}}=arcsin(x)$

Integrali Ricavabili
---
## $\int e^x=e^x$
## $\int a^x=\frac{1}{lna}*a^x$

## $\int sin=-cos$
## $\int cos=sin$
## $\int \frac{1}{cos^2}=tan$
## $\int\frac{1}{sin^2}=-cot$

>[!info] Se c'è il seno c'è il meno.

# Integrali Composti

>[!example] Se abbiamo un integrale immediato moltiplicato per $f^{'}(x)$ e dove tutte le $x$ sono sostituite con $f(x)$, il risultato è quello dell'integrale immediato ma sostituendo $x$ con $f(x)$.

>[!Quote]
>Esempi:
>---
>**SE** $a\neq -1\;\;\int [f(x)]^a*f^{'}(x)=\frac{f(x)^{a+1}}{a+1}+c$ 
>---
>$\int \frac{f^{'}x}{f(x)}=ln|f(x)|+c$
>---


# Integrazione di Funzioni **Razionali** Fratte
Denominatore e numeratore sono polinomi.
Il grado del numeratore è minore. Perchè?

Il denominatore è uguale al resto più quoziente per numeratore.
$D=R+Q*N$
Sostituendo nella frazione:
$$
\frac{D}{N}=\frac{R+Q*N}{N}=Q+\frac{R}{N}
$$
Il resto ha sempre grado minore del denominatore.

# Denominatore di **Secondo Grado**:
>La funzione è del tipo:
>$$
\int\frac{px+q}{ax^2+bx+c}dx
$$
Il numeratore è $px+q$ perchè deve essere di grado minore del denominatore.
Tutto può essere $=0$ tranne $a$.

## $\Delta >0$
- Scomponiamo il denominatore in $a(x-x_1)(x-x_2)$
- [[Come trasformare una frazione in somma di frazioni|Scriviamo la frazione come somma di due funzioni.]]
$$
\frac{px+q}{ax^2+bx+c}=\frac{A}{a(x-x_1)}+\frac{B}{(x-x_2)}$$
- [[Come trasformare una frazione in somma di frazioni#Come Trovare $A$ e $B$.|Troviamo]] $A$ e $B$.
- Risolviamo
$$
\int[\frac{A}{a(x-x_1)}+\frac{B}{(x-x_2)}]dx$$
## $\Delta =0$
>In questo caso possiamo sempre scrivere il denominatore come un quadrato:
>$ax^2+bx+c=a(x-x_1)^2$
>Dove $x_1=-b/2a$
### $p=0$ (Numeratore di grado $0$)
$$
\int{\frac{{q}}{a(x-x_1)^{2}}dx} 
$$
Questa funzione è integrabile.
$$
-\frac{q*(x-x_1)^{-1}}{a}+c
$$
$$
-\frac{q}{a(x-x_1)}+c
$$
### $p\neq0$
>[!info] Uguale a $\Delta>0$ ma con la scomposizione diversa.
- Scomponiamo il denominatore in $a(x-x_1)^2$
- [[Come trasformare una frazione in somma di frazioni|Scriviamo la frazione come somma di due funzioni.]]
$$
\frac{px+q}{ax^2+bx+c}=\frac{A}{a(x-x_1)}+\frac{B}{(x-x_1)^2}$$
- [[Come trasformare una frazione in somma di frazioni#Come Trovare $A$ e $B$.|Troviamo]] $A$ e $B$.
- Risolviamo
$$
\int[\frac{A}{a(x-x_1)}+\frac{B}{(x-x_1)^2}]dx$$
## $\Delta <0$
### $p=0$
- Trasformiamo la funzione in:
$$
\frac{1}{ax^2+bx+c}
$$
>Se c'è $p$ sopra dividiamo tutto per $p$.
- Usiamo il [[Metodo del completamento del Quadrato]] per scrivere il denominatore come $[f(x)]^2+1$
	- Se il denominatore viene $[f(x)]^2+k$ basta mettere a fattor comune $k$:   $k([f(x)]^2/k+1)$
- Trasformiamo il denominatore in $f^{'}(x)$
- Risolviamo [[#Integrali Composti|l'integrale composto]] [[#$ int frac{1}{1+x 2}=arctan(x)$|con l'arcotangente]].
### $p\neq0$
- Si rende il numeratore la derivata del denominatore.
	- Se per farlo devo aggiungere qualcosa, creo un altra frazione con lo stesso denominatore dove lo sottraggo.
- Si calcolano i due integrali separatamente.
# Denominatore di grado superiore al secondo
- [[Come trasformare una frazione in somma di frazioni|Si trasforma la frazione in somma di frazioni]]
- Si integrano separatamente.
>[!info] Stesso metodo di $\Delta=0 \land p\neq0$ e $\Delta >0$

