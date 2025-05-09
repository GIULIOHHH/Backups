---
tags: fisica
---
# [[Atomo]] 
Un atomo è composto da un nucleo formato da protoni, con carica $+e$ e neutroni, senza carica, circondato da una nube di particelle che gli orbitano intorno, dette elettroni, con carica $-e$.

Gli atomi sono composti da un numero uguale di protoni ed elettroni, inoltre la carica di un protone è esattamente uguale a quella di un elettrone, quindi gli atomi sono neutri (la carica totale è nulla).

# Carica elettrica
L'unità di misura della carica elettrica nel SI è il Couloumb $C$.
$$
e=1.6*10^{-19}C
$$
>Il simbolo $e$ rappresenta solo il valore, non il segno positivo o negativo della carica.

$e$ è la carica minima libera, tutte le altre cariche sono suoi multipli:
$$
q=n*e
$$
dove $q$ è la carica, ed $n$ è il numero di elettroni.

>Tecnicamente i quark hanno carica pari a +- e/2, però non possono esistere isolatamente, quindi non li contiamo 

Gli elettroni possono essere trasferiti da un corpo all'altro. 
- I corpi che guadagnano elettroni ottengono una carica negativa.
- I corpi che perdono elettroni ottengono una carica positiva.
Durante qualsiasi processo la carica elettrica totale di un sistema isolato rimane costante.
>La somma degli elettroni rimane uguale, non viene distrutto o creato nulla.

>Quando gli elettroni vengono trasferiti nel secondo corpo, si respingono a vicenda e si spargono sulla superficie.

Due oggetti carichi esercitano una forza reciproca tra loro. 
- Cariche uguali si respingono.
- Cariche opposte si attraggono.
>Le due forze sono di uguali intensità e direzione, ma di verso opposto.
# Elettrizzazione

La carica elettrica può muoversi attraverso gli oggetti. 
Distinguiamo:
- Conduttori elettrici
	- Terra, Metalli (oro, argento)
	- Sono conduttori perchè alcuni elettroni di valenza (da 1 a 3 per Atomo) si separano e si disperdono nel materiale. Questi elettroni poi determinano la propagazione della carica 
>All'interno di un conduttore carico in equilibrio elettrostatico il campo elettrico è nullo. Per questo funziona la gabbia di Faraday.
- Isolanti elettrici
	- Tipo legno o plastica
	- Ogni elettrone rimane vincolato al proprio atomo, quindi c'è un piccolo passaggio di carica.
Di solito i conduttori termici sono anche conduttori elettrici. (Stessa cosa gli isolanti)
>L'acqua distillata è un buon isolante, sono i sali nell'acqua a renderla un conduttore
## Elettrizzazione per contatto
Caricare un oggetto neutro, tramite contatto con un oggetto carico.
## Elettrizzazione per induzione
Caricare un oggetto neutro, tramite un oggetto carico, senza contatto.

Quando una bacchetta carica negativamente viene avvicinata ad una sfera **metallica** neutra, gli elettroni liberi vicino alla bacchetta vengono allontanati, quindi la parte vicino alla bacchetta risulta positiva.
>queste regioni vengono _indotte_ (costrette) a formarsi.
![[Pasted image 20240114181915.png]]
Una volta allontanata la bacchetta gli elettroni ritornano alla loro posizione originale.

Se colleghiamo la sfera (tramite conduttore) al terreno, alcuni elettroni liberi lasciano la sfera. Se togliamo il collegamento al terreno e dopo rimuoviamo la bacchetta, la sfera rimane carica positivamente.
>La stessa cosa si può fare per caricarla negativamente.
### Polarizzazione
Se invece la sfera fosse fatta di un isolante non sarebbe possibile caricarla per induzione. Nonostante questo la bacchetta avrebbe comunque respinto le cariche negative, determinando una leggera separazione tra cariche negative e positive nelle molecole. La superficie vicino alla bacchetta avrebbe ottenuto una leggera attrazione alla bacchetta e carica positiva.
# Legge di Coulomb
La forza elettrostatica che una carica [[puntiforme]] esercita su un altra è determinata da:
$$
F=k*\frac{|q_1|*|q_2|}{r^2}
$$
$k$ è la costante di Coulomb e nel vuoto:
$$
k=8.99*10^9\;\;\;\;\;\;\;\;\;[\frac{N*m^2}{C^2}]
$$
$$
k=\frac{1}{4*\pi*ε_0}
$$
$ε_0$ è la [[Costante dielettrica|Costante dielettrica nel vuoto]] e
$$
ε_0=8.85*10^{-12}
$$
![[Pasted image 20240114183303.png]]
La forza elettrostatica tra due cariche puntiformi è diretta lungo la retta che le unisce.

La forza totale che agisce su una carica elettrica è la risultante delle forze che ogni carica circostante esercita indipendentemente.
(Principio di Sovrapposizione)
>Date $q_1,q_2,q_3$: $F_1=F_{1-2}+F_{1-3}$ 

>La forza elettrostatica è simile a quella gravitazionale (entrambe sono lungo la retta e le formule sono simil)
>$$
F=G*\frac{m_1*m_2}{r^2}$$
Anche se la forza elettrostatica può essere sia repulsiva che attrattiva.
# Campo elettrico
Una carica elettrica genera un __Campo elettrico__ che modifica l'ambiente circostante.
Una carica $q_2$ sente una forza elettrostatica, che dipende dal fatto che $q_1$ ha modificato le proprietà dello spazio _In quel punto_.
>Questo, come il campo gravitazionale, permette interazioni a distanza.

Possiamo misurare il campo elettrico in un punto tramite una carica di prova $q_0$, (per convenzione con segno positivo), talmente piccola da non alterare le cariche circostanti.

$$
\overrightarrow{E}=\frac{\overrightarrow{F}}{q_0}\;\;\;\;\;\;\;\;\;\;\;\;[\frac{N}{C}]
$$
>$\overrightarrow{F}$ è la forza che $q_{0}$ subisce nel punto $P$.
Su ogni carica nel punto $P$ viene applicata una forza per coulomb uguale a $\overrightarrow{E}$.

$\overrightarrow{E}$  è un vettore quindi ha direzione e verso uguali a $\overrightarrow{F}$.

Il campo elettrico totale generato da due o più cariche è dato dalla somma vettoriale dei campi elettrici individuali.
## Carica [[puntiforme]] 
Il campo elettrico di una carica puntiforme è:
$$
E=\frac{k*|q|}{r^2}
$$
>$q_0$ non compare, quindi E non dipende da esso.

>Questa formula si ottiene sostituendo $F=k*\frac{|q_1|*|q_2|}{r^2}$ a $\overrightarrow{E}=\frac{\overrightarrow{F}}{q_0}$.

$|q|$ indica solo la grandezza ma non il segno; se è positivo $\overrightarrow{E}$ è uscente, altrimenti è entrante.
>Questo perchè per convenzione $q_{0}$ è positivo.
![[Pasted image 20240114190250.png]]

## Linee di Forza
Per visualizzare l'andamento del campo elettrico nello spazio usiamo le __Linee di forza del campo elettrico__. 
>Sono disegnate in 2d per convenzione.
- Partono da $q$ 
- Sono uscenti dalle cariche positive ed entranti in quelle negative.
- Il numero di __Linee di forza__ in un punto è proporzionale all'intensità del campo elettrico
	- Quando si è più vicini a $q$ la densità è maggiore.
- In ogni punto il vettore del campo elettrico $\overrightarrow{E}$ è tangente alla linea di forza (in quel punto).
- Nelle regioni in cui le linee sono parallele ed equidistanti il campo elettrico è uniforme 
	- In ogni punto ha lo stesso modulo, direzione e verso.
- Le linee di forza del campo elettrico partono sempre da, una carica positiva e terminano in una negativa.
- Il numero di linee di forza che escono o entrano è proporzionale alla grandezza della carica.
	- se da $q_1=4C$ escono $100$ linee, devono entrare $75$ in $q_2=-3C$ e $25$ in $q_3=-1C$
![[Pasted image 20240114190726.png|400]]
Un __Dipolo elettrico__ è formato da due cariche puntiformi uguali e opposte. Il campo elettrico $E$ è maggiore tra le cariche e nello spazio circostante.

Se abbiamo due acriche identiche invece Il campo elettrico $E$ è debole nella zona intermedia.
![[Pasted image 20240114191419.png]]
>Questo perchè la somma dei due vettori è uguale a 0


# Flusso elettrico
[[Vettore Area]]

Quando immergiamo una superficie $S$ in un campo elettrico, ogni punto è investito da un campo elettrico $\overrightarrow{E}$. 
Se il campo elettrico è uniforme definiamo __IL FLUSSO DI $\overrightarrow{E}$ ATTRAVERSO $S$__ come:
$$
\Phi_S( \overrightarrow{E})=\overrightarrow{E}\cdot\overrightarrow{A}=E*A*cos(\alpha)
$$
>Si ottiene tramite il prodotto scalare, quindi il flusso elettrico è uno scalare.

Si misura in 
$$
\frac{N}{C}*m^2
$$
>Lo possiamo pensare tipo un flusso d'acqua.

- Il flusso è positivo se $\alpha<90$
	- massimo se $\alpha=0$ (i 2 vettori sono paralleli)
- Il flusso è negativo se $\alpha>90$
	- massimo nella direzione opposta se $\alpha=180$
- Se $\alpha=90$ è nullo. (sono [[perpendicolare|perpendicolari]])
![[Pasted image 20240124163922.png]]

Data una superficie gaussiana (superficie irregolare) possiamo dividerla in piccole regioni, tali che:
- Ogni regione è piana
- In ogni regione il campo elettrico è uniforme.
>$$
\Phi_k( \overrightarrow{E})=\overrightarrow{E_k}\cdot\overrightarrow{A_k}
$$

Per calcolare il flusso elettrico totale attraverso la superficie sommiamo quelli di ogni regione.
$$
\Phi_S( \overrightarrow{E})=\sum\limits_k\overrightarrow{E_k}\cdot\overrightarrow{A_k}

$$

- Se il flusso è nullo i vettori del campo attraversano la superficie
- Se il flusso è positivo i vettori del campo sono disposti in modo da uscire dalla superifice
- Se il flussso è negativo i vettori sono disposti in modo da entrare nella superficie.

## Teorema di Gauss
$$
\Phi_S( \overrightarrow{E})=\frac{Q}{ε_0}
$$
>Il flusso non dipende dalla forma e dalle dimensioni della superficie.

Se abbiamo più cariche si fa la somma 
$$

\Phi_S( \overrightarrow{E})=\frac{\sum^n\limits_{i=1} Q}{ε_0}

$$
>Questa formula è equivalente alla legge di Coulomb.


### Dimostrazioni
- Abbiamo una carica $q$.
- Prendiamo tutti i punti a uguale carica elettrica.
- Otteniamo una forma sferica, dove il campo elettrico è sempre perpendicolare alla superficie $\alpha=0$

#### Dimostrazione della formula
$$
\Phi_S( \overrightarrow{E})=E*A
$$
$$
A=4*\pi*r^2
$$
$$
E=k*\frac{q}{r^2}
$$
$$
k=\frac{1}{4*\pi*ε_0}
$$
$$
\Phi_( \overrightarrow{E})=\frac{1}{4*\pi*ε_0}*\frac{q}{r^2}*4*\pi*r^2
$$
Semplificando otteniamo la formula.

#### Dimostrazione dell'equivalenza
$$
\Phi_S( \overrightarrow{E})=E*4*\pi*r^2
$$
$$
\Phi_S( \overrightarrow{E})=\frac{Q}{ε_0}
$$
$$
E*4*\pi*r^2=\frac{Q}{ε_0}
$$
$$
E=\frac{1}{4*\pi*ε_0}*\frac{q}{r^2}
$$
Una carica $q_1$ sente una forza pari a 
$$
E=\frac{1}{4*\pi*ε_0}*\frac{q*q_1}{r^2}
$$
(Questa è la legge di coulomb)