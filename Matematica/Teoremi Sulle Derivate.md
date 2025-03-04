# Punti Non derivabili
Un punto non è derivabile se la derivata sinistra è diversa da quella destra, oppure la derivata è uguale a infinito.

- I flessi a tangente verticale sono punti dove le derivate sono infiniti di segno uguale.
- Le cuspidi sono punti dove le derivate sono infiniti di segni opposti.
- I punti angolosi sono punti dove una delle derivate è finita.

# Teoremi
I 3 teoremi si basano su 2 condizioni, una (o due) funzioni:
1. sono continue nell'intervallo chiuso e limitato $I=[a,b]$
2. sono derivabile nei punti interni
## Teorema di Rolle
**Terza condizione**:
3. $f(a)=f(b)$, 

Allora esiste un punto interno $c$ dove $f^{'}(c)=0$.


>In altre parole esiste un punto $c$ interno all'intervallo dove la derivata è $0$.
>$$\exists c \in ]a,b[:f^{'}(c)=0$$

>O la funzione è una retta, o se sale ci deve essere un punto in cui scende, dato che gli estremi sono uguali.
![[Pasted image 20241106181140.png|500]]


>Dimostrazione inutile:
>Per il teorema di Weierstrass ci sono un massimo e un minimo. 
>- Se sono uguali per definizione la derivata della funzione è 0.
>- Se sono diversi almeno uno dei 2 è interno (magari uno è agli estremi ma MAI entrambi).
>Se il minimo è interno, per ogni incremento:
>$f(c+h)\ge f(c)$
>$f(c+h)-f(c)\ge0$.
>Facendo i rapporti incrementali sia di sinistra che di destra:
>sinistra ($h<0$):
>$$\frac{f(c+h)-f(c)}{h}\le0 $$
>destra ($h>0$):
>$$\frac{f(c+h)-f(c)}{h}\ge0 $$
>Dato che la funzione è derivabile i due limiti devono coincidere e l'unico punto in comune è
>$$\frac{f(c+h)-f(c)}{h}=0 $$
## Teorema di Lagrange
Esiste almeno un punto $c$ interno all'intervallo dove:
$$
\frac{f(b)-f(a)}{b-a}=f^`(c)
$$
ovvero
$$
\frac{\Delta y}{\Delta x}=f^`(c)
$$
>dove $\frac{\Delta y}{\Delta x}$ è il coefficiente angolare della secante tra $b$ e $a$.
![[Pasted image 20241110201632.png]]
Esiste almeno una retta tangente parallela alla secante tra i due estremi.
### Conseguenze
>Anche per le conseguenze valgono le 2 condizioni.

- Se in una funzione $f^`(x)$ è nullo in ogni punto, la funzione è constante in $I$.
- Se due funzioni hanno la stessa derivata in ogni punto, differiscono per una costante.
- Se la derivata di una funzione è maggiore di $0$ per ogni $x$ interna all'intervallo $I$, è crescente in $I$
	- Se è minore di $0$ per ogni $x$ è decrescente in $I$
	- Se $f(x)$ è crescente in $I$, la sua derivata sarà sempre maggiore di $0$.



### Teorema di Cauchy
Due funzioni $f(x)$ e $g(x)$.
**Terza condizione**:
3. $g^`(x) \neq 0$ per ogni $x$ interno ad $I$.
 Esiste un punto interno dove:
 $$ 
\frac{f(b)-f(a)}{g(b)-g(a)}=\frac{f^`(c)}{g^`(c)}
$$

>è come se facessimo il rapporto tra il teorema di lagrange di 2 funzioni e $b-a$ si semplificassero.
>$$\frac{\frac{f(b)-f(a)}{b-a}}{\frac{g(b)-g(a)}{b-a}}=\frac{f^`(c)}{g^`(c)}$$

Il rapporto tra gli incrementi delle funzioni è uguale al rapporto tra le derivate.
$$
\frac{\Delta y_f}{\Delta y_g}=\frac{f^`(c)}{g^`(c)}
$$

Data la funzione $h(x)=(g(x),f(x))$, esiste una retta tangente parallela alla retta secante per $h(b)$, $h(a)$, con coefficiente
$$\frac{f^`(c)}{g^`(c)}
$$
>$f(x)$ è sopra perchè è la $y$.
# Teorema di De l'Hospital
Condizioni:
1. Due funzioni $f(x)$ e $g(x)$ definite in $I$, intorno di $x_0$, ma non necessariamente in $x_0$.
	1. *Devono essere definite in ogni altro punto, ma non ci interessa se sono definite in $x_0$, quindi possono essere anche $\infty$.*
2. Derivabili in $I$ ma non necessariamente in $x_0$.
	1. _perchè facciamo il **limite** della derivata che tende a $x_0$_
3. $g^`(x) \neq 0$ in ogni punto in $I-\{x_0\}$. 
	1. _perchè facciamo il **limite** della derivata che tende a $x_0$_
4. Esiste $$\lim_{x->x_{0}} \frac{f^`(x_0)}{g^`(x_0)}$$
5. $lim_{x->x_{0}}\;f(x)=lim_{x->x_{0}}\;g(x)=$ ${0} / {\pm}\infty$
	1. Se entrambe le funzioni sono definite in $x_0$ possiamo scrivere che $f(x)=g(x)=0$.

>Se $I$ è un intorno sinistro, si considera il limite per $x->x_0^-$

>Il teorema funziona anche per $x->+\infty$. In questo caso le condizioni del teorema devono essere vere per un intorno di $+\infty$, quindi deve esistere un valore $M>0$ tale che le condizioni siano soddisfatte per qualunque $x>M$. 
>Al contrario si fa per $x<-M$.


Quindi
$$
\lim_{x->x_{0}} \frac{f(x)}{g(x)}=
\lim_{x->x_{0}} \frac{f^`(x)}{g^`(x)}
$$
Il teorema può essere usato per risolvere ogni forma indeterminata.

>Il teorema esprime una condizione sufficiente ma non necessaria, potrebbe non esistere il limite delle derivate ma esistere il limite normale.

>Date 2 funzioni uguali a $0$ in $x_0$, invece delle curve consideriamo le tangenti: $y=f^`(x_0)(x-x_0)$. (non c'è $f(x)$ perchè è uguale a $0$.
>Quindi
>$$\lim_{x->x_{0}} \frac{f(x)}{g(x)}=
\lim_{x->x_{0}} \frac{f^`(x_0)(x-x_0)}{g^`(x_0)(x-x_0)}$$
Semplificando otteniamo l'hopital.

>Dimostrazione inutile:
>Partendo da cauchy.
>Dato che $f(x)=g(x)=0$
>$\frac{f(x)}{g(x)}= \frac{f^`(c)}{g^`(c)}$
>Per $x->0$, anche $c->0$
>$\lim_{x->x_{0}} \frac{f(x)}{g(x)}=\lim_{c->x_{0}} \frac{f^`(x)}{g^`(c)}$
>Dato che sono uguali possiamo scrivere l'hospital


## Altre forme indeterminate
### $0*\infty$
Possiamo scrivere 
$$f(x)*g(x)=\frac{f(x)}{\frac{1}{g(x)}}$$
Oppure al contrario
### $+\infty-\infty$
Cerchiamo di scrivere la differenza come prodotto o quoziente di funzioni.
### $0^{0}$ $\infty^0$ $1^\infty$
Bisogna calcolare $$\lim_{x->x_{0}} f(x)^{g(x)}$$
Dato che $x=e^{lnx}$
$$[f(x)]^{g(x)}=e^{ln(f(x)^{g(x)})}$$
$$e^{ln(f(x))*g(x)}$$
Quindi il limite è uguale a
$$
e^{\lim_{x->x_{0}}[lnf(x)*g(x))]}
$$
Quindi basta calcolare
$$
\lim_{x->x_{0}}[lnf(x)*g(x))
$$
Che è nella forma $0*\infty$.


# Esercizi
## Trova per quali valori del parametro $a$ $f(x)$ è sempre crescente.
Dobbiamo porre $f(x)>0$, e determinare $a$ in modo tale che il risultato sia $\forall x \in R$.
- Se $f(x)$ è di secondo grado, dobbiamo imporre $\Delta<0$

## Studia la derivabilità di $f(x)$
1. Studiamo il dominio e la continuità.
	1. Non ci può essere derivabilità in un punto dove non è definita
	2. La continuità è una condizione necessaria per la derivabilità
2. Calcoliamo la derivata 
3. I punti di non derivabilità sono quelli non appartenenti al dominio della derivata
4. Se la funzione è a tratti, confrontiamo la derivata sinistra e la derivata destra in prossimità dei cambi di espressione analitica.

