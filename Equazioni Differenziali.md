# Definizione
>[!Done] Formula
>Un'**Equazione Differenziale** mette in relazione una funzione incognita $f(x)$, le sue derivate e $x$.
>L'**Ordine** di un **Equazione Differenziale** è dato dall'ordine massimo delle derivate.

La formula è $F(x;\;y;\;y^{`};\;...\;y^{(n)})=0$

>[!quote] Esempio
>Qual'è l'ordine di $y^{```}+y^{(7)}+y^{``}-4x=0$?
>è di settimo ordine per via di $y^{(7)}$.

L'[[Integrali Indefiniti|Integrale Generale]] di un **Equazione Differenziale** è l'insieme delle soluzioni.
Un [[Integrali Indefiniti|Integrale Generale]] di un **Equazione Differenziale** di **Ordine** $n$, ha $n$ parametri ($c_{1},c_{2},c_3...$)
>[!quote] Esempio
>Trova l'integrale generale di 
>$$y^{``}=2x$$
>Integro entrambi i lati.
>$$y^{`}=x^2+c_1$$
>Integro entrambi i lati.
>$$y=\frac{x^3}{3}+c_1*x+c_2$$

L'**Integrale Particolare** si ottiene imponendo $n$ condizioni in più.
## Problema di [[Teoremi Sulle Derivate#Teorema di Cauchy|Cauchy]]
Un sistema formato dall'**Equazione Differenziale** di **Ordine** $n$ e $n$ condizioni.
>chiamate condizioni iniziali.

# Equazioni A variabili Separabili
Un equazione del tipo:
$$y^{`}=h(x)*g(y)
$$
[[Derivata|Posso scrivere]] $y^{'}$ come $dy/dx$:
$$
\frac{dy}{dx}=h(x)*g(y)
$$
Porto tutte le $y$ a sinistra:
$$
\frac{dy}{g(y)}=h(x)*dx
$$
Integro:
$$\int{\frac{1}{g(y)}dy}=\int{h(x)}dx
$$
Poi si ricava $y$ in funzione di $x$.
>[!quote] Esempio:
$$y^{'}=2x*y^2$$
>$$\frac{dy}{dx}=2x*y^2$$
>$$\frac{dy}{y^2}=2x*dx$$
>$$\int{\frac{1}{y^2}}dy=\int{2x}dx$$
>$$-\frac{1}{y}=2x^2+c$$
>$$y=-\frac{1}{2x^2+c}$$
# Equazioni Lineari del primo ordine
Del tipo
$$
y^{`}=a(x)*y+b(x)
$$
>lineare perchè $y$ è di primo grado.

Se $b(x)=0$, l'equazione è **omogenea** e si ritorna al [[#Equazioni A variabili Separabili|Caso precedente]].
Altrimenti è **completa**.

Per trovare la soluzione definiamo $A(x)$:
$$
A(x)=\int{a(x)}
$$
Portiamo $a(x)$ a sinistra.
$$
y^{`}-a(x)*y=b(x)
$$
Moltiplichiamo tutto per $e^{-A(x)}$.
$$
y^{`}*e^{-A(x)}-y*a(x)*e^{-A(x)}=b(x)*e^{-A(x)}$$
Il primo membro è la derivata di $y*e^{-A(x)}$.

>$$D(y*e^{-A(x)})=y^{`}*e^{-A(x)}+y*[-a(x)]*e^{-A(x)}$$

$$
D(y*e^{-A(x)})=b(x)*e^{-A(x)}
$$
Integrando tutto:
$$
\int{D(y*e^{-A(x)})}=\int{b(x)*e^{-A(x)}}
$$
Per le [[Integrali Indefiniti#Integrazione|Proprietà degli integrali]]
$$
y*e^{-A(x)}=\int{b(x)*e^{-A(x)}}
$$
Quindi:
$$
y=\frac{\int{b(x)*e^{-A(x)}}}{e^{-A(x)}}
$$
Dato che:
$$
\frac{1}{e^{-A(x)}}=e^{-A(x)*(-1)}=e^{A(x)}
$$
>[!done] Formula
>$$y=e^{A(x)}=\int{b(x)*e^{-A(x)}} +c$$ 

>il $+c$ è li perchè abbiamo integrato prima.

# Secondo Ordine con i coefficienti costanti
Del tipo:
$$
y^{``}+by^`+cy=g(x)
$$
Sono **Omogenee** se $g(x)=0$, altrimenti sono **Complete**.
## Omogenee
L'[[Integrali Indefiniti|Integrale Generale]] è dato dalla funzione $e^{kx}$, dove $k$ è un numero da trovare.
Derivando:
$$
y=e^{kx}
$$
$$
y^`=k*e^{kx}
$$
$$
y^{``}=k^2*e^{kx}
$$
Sostituendo nell'equazione:
$$
k^2*e^{kx}+b*(k*e^{kx})+c*(e^{kx})=0
$$
Mettendo a fattor comune $e^{kx}$
$$
e^{kx}(k^2+bk+c)=0
$$
Dato che $e^{kx}$ non può mai essere $0$, le soluzioni sono date dall'**equazione caratteristica dell'equazione differenziale**.
$$
k^2+bk+c=0
$$

>Si trasforma $y^{``}$ in $k^2$, $by^`$ in $bk$ e $cy$ in $c$.

### Se $\Delta>0$ 
$$y=c_1*e^{k_1x}+c_2*e^{k_2x}$$
>dove $k_1$ e $k_2$ sono le soluzioni.
>
## Se $\Delta=0$
$$
y=e^{k_1x}*(c_1+c_2*x)
$$
## Se $\Delta<0$
Otteniamo un [[Numeri Complessi|Numero Complesso]]:
$$
k_{1-2}=\alpha\pm{i*\beta}
$$
quindi la soluzione è
$$
y=e^{\alpha{x}}[c_1*cos(\beta*x)+c_2*sin(\beta*x)]
$$
## Complete

>$$y^{``}+by^`+cy=g(x)$$

Alla soluzione delle [[#Omogenee]], aggiungiamo una soluzione particolare:
Devo trovare una $y_p$, che sostituita alle $y$ a sinistra sia uguale a $g(x)$.

Trovo $y_p$ in base a $g(x)$

| $g(x)$:                               | $y_p$ :                                                       |     |
| ------------------------------------- | ------------------------------------------------------------- | --- |
| $P_n(x)*e^{ax}$                       | $(A_0+A_1x+A_2x^2...A_nx^n)*e^{ax}$                           |     |
| $P_n(x)*e^{ax}*[sin(kx)\;o\;cos(kx)]$ | $(A_0+A_1x+A_2x^2...A_nx^n)*e^{ax}*[B_1*sin(kx)+B_2*cos(kx)]$ |     |
>$P_n(x)$ è un polinomio di grado $x$.

>Se $g(x)$ è una somma di moltiplicazioni sommo le soluzioni per $y_p$:
>$g(x)=P_f(x)*e^{ax}*sin(kx)+P_g(x)+e^{bx}+cos(jx)$
>$y_p=(...A_fx^f)*e^{ax}*[B_1*sin(kx)+B_2*cos(kx)]+(...C_gx^g)*e^{bx}*(D_1*sin(jx)+D_2*sin(jx))$

Se una parte della mia $y_p$ è uguale ad un termine della soluzione, devo moltiplicare la parte per $x$ finchè non lo è.

>[!quote] Esempio
>L'[[Integrali Indefiniti|Integrale Generale]] è:
>$$c_1*e^x+c_2*e^{2x}$$
>La mia $y_p$ è $y_p=A*e^{2x}$.
>La devo moltiplicare per $x$.
>$$y_p=A*x*e^{2x}$$

Ora devo sostituire $y_p$ alle $y$ a sinistra, quindi faccio la derivata prima e la derivata seconda.
Scrivo entrambi i membri come polinomi. 
>tutti i termini che moltiplicano $x^n$ + tutti i termini che moltiplicano $x^{n-1}$ + ...

Dato che due polinomi sono uguali se lo sono i loro coefficienti, li metto tutti a [[Come trasformare una frazione in somma di frazioni#Come Trovare $A$ e $B$.|sistema]].

Sostituendo le incognite alla mia $y_p$, trovo una soluzione particolare.

>[!Quote] Esempio
>Risolvi:
>$$y^{``}-4y^`-12y=2x^3-x+3$$
>Troviamo la soluzione [[#Omogenee|Omogenea]].
>L'**equazione caratteristica dell'equazione differenziale** è:
>$$y^2-4y-12=0$$
>Facciamo il $\Delta/4$
>$$\frac{\Delta}{4}=4+12=4^2$$
>[[#Se $ Delta>0$|Caso]] $\Delta>0$:
>$$k=2\pm4$$
>$$k_1=6\;\;\;\;\;k_2=-2$$
>$$c_1e^{6x}+c_2e^{-2x}$$
>Questo è '[[Integrali Indefiniti|Integrale Generale]]. 
>
>---
>Ora dobbiamo aggiungere una soluzione particolare.
>$$g(x)=2x^3-x+3$$
>è un polinomio di terzo grado.
>$$y_p=A_0+A_1x+A_2x^2+A_3x^3$$
>$y_p$ non compare a sinistra, quindi non devo moltiplicare per $x$.
>Devo sostituire $y_p$ ad $y$.
>$$y_p^{``}-4y_p^`-12y_p=2x^3-x+3$$
>Derivando $y_p$:
>$$y_p^{`}=A_1+A_2x+A_3x^2$$
>$$y_p^{``}=A_2+A_3x$$
>Sostituendo:
>$$[A_2+A_3x]-4[A_1+A_2x+A_3x^2]-12[A_0+A_1x+A_2x^2+A_3x^3]=2x^3-x+3$$
>Risolvendo:
>$$A_2+A_3x-4A_1-4A_2x-4A_3x^2-12A_0-12A_1x-12A_2x^2-12A_3x^3=2x^3-x+3$$
>Metto a fattor comune i membri di $x^0$, $x^1$, $x^2$ e $x^3$.
>$$(-12A_3)x^3+(-12A_2-4A_3)x^2+(-12A_1-4A_2+A_3)x+(-12A_0-4A_1+A_2)=(2)x^3+(0)x^2+(-1)x+(3)$$
>Dato che entrambi i lati sono uguali, posso fare un sistema:
>$$
\begin{cases}  -12A_3=2\\-12A_2-4A_3=0\\-12A_1-4A_2+A_3=-1\\-12A_0-4A_1+A_2=3\end{cases}$$
>$$\begin{cases}  A_3=-\frac{1}{6}\\A_2=\frac{1}{6}\\A_1=-\frac{1}{9}\\A_0=-\frac{5}{27}\end{cases}$$
>La soluzione particolare è quindi:
>$$-\frac{1}{6}x^3+\frac{1}{6}x^2+\frac{1}{9}x-\frac{5}{27}$$
>Aggiungendola alla soluzione generale ottengo:
>$$[c_1e^{6x}+c_2e^{-2x}]+[-\frac{1}{6}x^3+\frac{1}{6}x^2-\frac{1}{9}x-\frac{5}{27}]$$

 





