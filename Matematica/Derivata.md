# Retta tangente a una curva.
La retta tangente a una curva in $P$,  è la retta a cui tendono le secanti $PQ$, al tendere di $Q$ a $P$, sia da sinistra che da destra.
![[WhatsApp Image 2024-10-09 at 16.37.35.jpeg]]
# Rapporto incrementale
Data una funzione definita in un intervallo $I$ e un punto $(c,\;f(c))$, possiamo incrementare $c$ di una quantità $h$ (se $c+h$ rimane interno ad $I$).
quindi $(c,\;f(c))$ diventa $(c+h,\;f(c+h))$.

Quindi 
$\Delta x=x_b-x_a$
$\Delta x=(c+h)-c$
$\Delta x=h$

$\Delta y=y_b-y_a$
$\Delta y=f(c+h)-f(x)$

Il rapporto incrementale è definito 
$$
\frac{\Delta y}{\Delta x}=\frac{f(c+h)-f(c)}{h}
$$
Il rapporto incrementale è il coefficente angolare della retta passante per i punti di coordinate $c$ e $c+h$.
![[Pasted image 20241009164459.png]]

# Derivata prima
Quando $h->0$, i due punti tendono a coincidere e la retta tende a diventare tangente. 
La derivata prima è il coefficiente angolare della retta tangente in $c$.

Data una funzione $f(x)$ e un punto $c$ appartenente al suo dominio:
la derivata prima di $f(x)$ nel punto $c$ è il limite per $h$ che tende a $0$ del rapporto incrementale di $f(x)$ in $c$.

$$f^{'}(x_0)=\lim_{h->0} \frac{f(c+h)-f(c)}{h}$$
- Il limite del rapporto incrementale deve essere un numero finito.
- Il limite destro del rapporto incrementale deve essere uguale a quello sinistro.

>$f(x)$ è derivabile in $[a,b]$ se è derivabile in ogni punto dell'intervallo.

La derivata prima sinistra è il limite per $h->0^-$.


Possiamo calcolare la derivata di una funzione in un punto generico $x$. In questo caso otteniamo una funzione derivata $f^{'}(x)$.


### Derivabilità
Se una funzione è derivabile in $c$ è anche continua in $c$.
>Una funzione è continua se $\lim_{h->0} f(c+h)=f(c)$

Le funzioni derivabili sono un sottoinsieme delle [[Funzioni Continue]].


# Operazioni Tra derivate 

# $D[k*f(x)]=k*D[f(x)]$
>Perchè:
$$\lim_{h->0} \frac{k*f(c+h)-k*f(c)}{h}=\lim_{h->0} k*\frac{f(c+h)-f(c)}{h}$$

# $D[f(x)+g(x)]=D[f(x)]+D[g(x)]$
>Perchè il limite di una somma è uguale alla somma dei limiti.

# $D[f(x)*g(x)]=D[f(x)]*g(x)+f(x)*D[g(x)]$
# $$D[\frac{f(x)}{g(x)}]=\frac{D[f(x)]*g(x)-f(x)*D[g(x)]}{g(x)^2}$$
# $D[f(g(x))]=f^{'}[g(x)]*D[g(x)]$
>Ad esempio 

# $D[f(x)^a]=D[f(x)]*a*f(x)^{a-1}$

# $D[f(x)^{g(x)}]=f(x)^{g(x)}*(D[g(x)]*ln[f(x)]+\frac{D[f(x)]}{f(x)}*g(x))$
Oppure scritto in maniera più semplice:
$$
f^g=f^g*(g^{'}*ln(f)+\frac{f^{'}}{f}*g)
$$

Dimostrazione:
$$y=f(x)^{g(x)}$$
Prendo il [[Logaritmo Naturale|Logaritmo Neperiano]] di entrambi.
$$
ln(y)=ln[f(x)^{g(x)}]
$$
Per le proprietà dei [[Logaritmo|Logaritmi]]:
$$
ln(y)=ln[f(x)]*g(x)
$$
Ora derivo tramite le [[#Derivate fondamentali]]:
$$
D(y)*\frac{1}{y}=D[g(x)]*ln[f(x)]+D[ln[f(x)]]*g(x)
$$
Per definizione $y=f(x)^{g(x)}$

$$
D(y)=y*[\;D[g(x])*ln[f(x)]+D[f(x)]*\frac{1}{f(x)}*g(x)\;]
$$
E da qui si ottiene quella sopra.

# Derivate fondamentali
# 1. $D[k]=0$
Dimostrazione:
$f(c)=f(c+h)=k$
quindi 
$$
\lim_{h->0} \frac{k-k}{h}=0
$$
# 2. $D[x]=1$
Dimostrazione:
$f(x)=x$
$f(x+h)=x+h$
$$
\lim_{h->0} \frac{x+h-x}{h}=\frac{h}{h}=1
$$
# 3. $D[x^a]=a*x^{a-1}$
Dimostrazione:
$$
\lim_{h->0} \frac{(x+h)^a-x^a}{h}
$$
Esco fuori dalle parentesi $x$
$$
\lim_{h->0} \frac{x^a(1+\frac{h}{x})^a-x^a}{h}
$$

Metto a fattor comune $x^a$
$$
\lim_{h->0} x^a\frac{(1+\frac{h}{x})^a-1}{h}
$$
$x^a=\frac{x^{a-1}}{\frac{1}{x}}$
$$
\lim_{h->0} x^{a-1}\frac{(1+\frac{h}{x})^a-1}{\frac{h}{x}}
$$

$$
\frac{(1+x)^a-1}x
$$ tende ad $a$.

# 4. $D[sin(x)]=cos(x)$
Dimostrazione:
$sin(c+h)=cos(c)*sin(h)+cos(h)*sin(c)$
$$\lim_{h->0} \frac{cos(c)*sin(h)+cos(h)*sin(c)-sin(c)}{h}$$
Mettiamo a fattor comune $sin(c)$
$$\lim_{h->0} \frac{cos(c)*sin(h)+sin(c)*(cos(h)-1)}{h}$$
$$\lim_{h->0} sin(c)*\frac{cos(h)-1}{h}*cos(c)*\frac{sin(h)}{h}$$
$\frac{cos(x)-1}{x}$ tende a $0$, invece $\frac{sin(x)}x$ tende a $1$.

# 5. $D[cos(x)]=-sin(x)$

# 6. $D[a^x]=a^x*ln(a)$#
Dimostrazione:
$$\lim_{h->0} \frac{a^{x+h}-a^x}{h}$$

$$\lim_{h->0} \frac{a^x*(a^{h}-1)}{h}$$
$\frac{a^x-1}{x}$ tende a $ln(x)$

# 7. $D[log_a(x)]=\frac{log_a(e)}{x}$
Dimostrazione:
$$\lim_{h->0} \frac{log_a(x+h)-log_a(x)}{h}$$
$$\lim_{h->0} \frac{log_a(\frac{x+h}{x})}{h}$$
$$\lim_{h->0} \frac{log_a(1+\frac{h}{x})}{h}$$
Dividiamo tutto per $x$
$$\lim_{h->0}\frac{1}x* \frac{log_a(1+\frac{h}{x})}{\frac{h}x}$$
$\frac{log_a(1+x)}{x}$ tende a $log_a(e)$


# Esercizi
## Equazione della retta tangente in $c$.
Si calcola $m$ tramite la derivata.
All'equazione $y-y_0=m(x-x_0)$ si sostituiscono  $x=c$, $y=f(c)$, $m=f^{'}(c)$ 

## Rette tangenti condotte da un punto esterno $(x_0,y_0)$.
Data una funzione $f(x)$ e un generico punto $c$ risolviamo l'equazione:
$$y-f(c)=f^{'}(c)*(x-c)$$
Imponiamo il passaggio per $(x_0,y_0)$ e troviamo $c$. Poi lo sostituiamo nell'equazione originale.

## Grafici Tangenti.
Dati $f(x)$ e $g(x)$, determina se c'è un punto dove sono tangenti.
Deve esserci un punto dove:
- Si incontrano
- Hanno lo stesso coefficiente angolare
Quindi poniamo il sistema:

$$

\begin{cases} 
f(x)=g(x) \\
f^{'}(x)=g^{'}(x)

\end{cases}$$$$