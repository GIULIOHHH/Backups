---
tags: fisica, Onde
---
>Forse non si devono studiare le dimostrazioni.
# Definizione 
L'effetto doppler è la variazione di frequenza del suono rilevato dal ricevitore, perchè la sorgente sonora e il ricevitore hanno velocità diverse rispetto al mezzo in cui il [[Suono]] si propaga. 
## Esempio
Un camion da fermo inizia a muoversi.
![[Pasted image 20231127123459.png]]
Dato che compressioni e rarefazioni sono simmetriche rispetto alla sorgente, SE IL CAMION è FERMO sia il ricevitore davanti che quello dietro ricevono lo stesso numero di compressioni al secondo, quindi percepiscono la stessa [[Frequenza]].

SE IL CAMION INIZIA A MUOVERSI le compressioni davanti risultano più vicine, perchè prima di provocare una nuova compressione il camion si muove verso quella precedente. Quindi l'osservatore davanti percepisce un numero maggiore di compressioni al secondo, quindi un [[Suono]] più acuto.

Le compressioni indietro invece risultano più lontane, perchè il camion si allontana dalla compressione precedente. L'osservatore dietro percepisce una [[Frequenza]] minore e un [[Suono]] più grave.

# Sorgente in movimento e ricevitore fermo
Se la sorgente è ferma e emette la prima compressione a $t=0$, la prossima la emetterà a $t=T$, dove la distanza tra le due compressioni è uguale a $\lambda$.
## verso il ricevitore
Se la sorgente si muove con velocità $v_s$ emette sempre le compressioni negli istanti $t=0$ e $t=T$, ma la loro distanza è minore di $\lambda$ ed è data da
$$
\lambda^`=\lambda-v_s*T
$$
Se la esprimiamo come frequenza percepita dal ricevitore $f_r$
$$
f_r=\frac{v}{\lambda^`}
$$
$$
f_r=\frac{v}{\lambda-v_s*T}
$$
Inoltre
$$
\lambda=\frac{v}{f_s}
$$
Dove $f_s$ è la frequenza emessa dalla sorgente e $v$ è la velocità del suono ($343 \frac{m}{s}$).

__QUINDI__ sostituendo:
$$
f_r=f_s*\frac{1}{1-\frac{v_s}{v}}
$$
## si allontana dal ricevitore 
La distanza tra due compressioni è maggiore di $\lambda$ ed è uguale a:
$$
\lambda^`=\lambda+v_s*T
$$
quindi 
$$
f_r=f_s*\frac{1}{1+\frac{v_s}{v}}
$$
# Sorgente ferma e ricevitore in movimento
In questo caso la lunghezza d'onda $\lambda$ non cambia, ma cambia il numero di compressioni al secondo incontrate.
## verso la sorgente
Quando il ricevitore si muove verso la sorgente, riceve:
- Le compressioni che avrebbe ricevuto anche da fermo
- Più un numero di compressioni dato dal rapporto $v_r*t$/$\lambda$, dove $v_r*t$ è lo spazio attraversato e $\lambda$ è la distanza tra due compressioni.
![[Pasted image 20231127125717.png]]
Il numero di compressioni in più in un secondo, dato che $t=1$ è 
$$
\frac{v_r}{\lambda}
$$
Quindi la frequenza percepita è maggiore.
$$
f_r=f_s+\frac{v_r}{\lambda}
$$
Possiamo scrivere
$$
f_r=f_s(1+\frac{v_r}{f_s*\lambda})
$$
e dato che $v=f_s*\lambda$
$$
f_r=f_s(1+\frac{v_r}{v})
$$
## si allontana dalla sorgente
Incontra un numero minore di compressioni
$$
f_r=f_s(1-\frac{v_r}{v})
$$
# Caso generale
Il numeratore è il ricevitore in movimento, il denominatore è la sorgente.

Se il ricevitore si avvicina si mette il +, se la sorgente si avvicina si mette il -.

Se il ricevitore si allontana si mette il -, se la sorgente si avvicina si mette il +.
$$
f_r=f_s*\frac{1±\frac{v_r}{v}}{1\mp\frac{v_s}{v}}
$$
![[Pasted image 20231127131033.png]]
# __BOOM SONICO__
L'effetto doppler è un fenomeno __Asimmetrico__, quindi varia se è la sorgente o il ricevitore a muoversi.
![[Pasted image 20231127132020.png]]
- La [[Retta]] in rosso è il ricevitore in movimento
- L'[[Iperbole#Iperbole Equilatera riferita agli assi di simmetria|arco di funzione omografica]] in blu è la sorgente in movimento.

Quando la sorgente si avvicina e la sua velocità tende a quella del suono il denominatore tende a 0, quindi il suono percepito dal ricevitore $f_r$ tende a $\infty$:
$$
\lim_{v_s->v}f_s*\frac{1}{1-1}=+\infty
$$
Questo fenomeno è detto __BOOM SONICO__.
>Quando partono gli arei supersonici la sovrapposizione degli strati d'aria forma una sorta di muro, che viene rotto se l'aereo supera la velocità del suono.