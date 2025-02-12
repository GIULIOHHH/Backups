# Circuiti
>Un circuito elettrico collega attraverso un conduttore una sorgente di energia e un dispositivo che la utilizza.
     

Le cariche elettriche si muovono se esiste una differenza di potenziale ai suoi capi, ottenuta grazie al generatore di tensione.
>Tipo batteria

Ogni generatore ha due Estremità/morsetti/poli, uno positivo (potenziale maggiore) e uno negativo (potenziale minore).
La differenza di potenziale tende a diminuire, ma il generatore la mantiene costante, spostando cariche positive giunte sul polo negativo in quello positivo e viceversa. 
Per spostare questa carica è necessario un lavoro che vinca la forza elettromagnetica. 

$$
fem=\frac{L}{q} \;\;\;\;\;[V]
$$
La forza elettromotrice $fem$ è la massima differenza di potenziale di un generatore. è anche la differenza quando nel generatore non si muovono cariche.
>Quella reale è di solito minore.

# Corrente elettrica
>La batteria crea un campo elettrico dal polo positivo a quello negativo. Il campo elettrico esercita una forza sugli elettroni. Il flusso degli elettroni è detto corrente elettrica.
![[Pasted image 20240402130837.png]]
$$
I=\frac{\Delta q}{\Delta t}
$$
- $\Delta q$ è la carica che attraversa una sezione trasversale di un conduttore in tempo $\Delta t$.
si misura in Ampere $A$.
- Se le cariche si muovono sempre nello stesso verso la corrente è continua
- Se il verso cambia la corrente è alternata

$I>0$ la corrente scorre da sinistra verso destra.

>La lunghezza di una sezione può essere calcolata come 
>$$
d=v_{d*\Delta}t
$$
Il numero di cariche che attraversano è
$$
N=n*A*d
$$
dove $A$ è l'area della sezione e $n$ è la densità di cariche
$$
N=n*A*v_{d*\Delta}t
$$
Sostituendo otteniamo che 
$$
I=n*e*A*v_d
$$
$v_d=10^{-6}m/s$


Gli elettroni normalmente si muovono di moto browniano, urtando le particelle cariche che incontrano. Questo moto è senza trasporto di carica, perchè tanti elettroni si spostano in un verso quanti se ne spostano nel verso opposto.

Applicando un campo elettrico il moto rimane caotico, ma tutti gli elettroni risentono di una forza, che in media li spinge verso il potenziale maggiore, formando una corrente. La velocità del moto è detta velocità di deriva. 
>La corrente funziona anche se la velocità di deriva sia molto minore rispetto al moto browniano perchè si muovono tutti gli elettroni.

In passato si credeva che la corrente elettrica fosse un flusso di cariche positive, da potenziale maggiore a potenziale minore. Questa è detta corrente convenzionale ed ha verso opposto ma lo stesso effetto del flusso di elettroni. Si utilizza ancora la corrente convenzionale.
# Leggi di Ohm
## Prima legge
Mantenendo un conduttore a [[Temperatura]] costante:
$$
V=R*I
$$
- $V$ è la differenza di potenziale tra i due poli 
- $I$ è direttamente proporzionale a $V$ e inversamente proporzionale a $R$
- $R$ è la resistenza elettrica del conduttore, misurata in ohm $\Omega$. 
I conduttori che seguono la prima legge di ohm sono detti ohmici o __Resistori__. 

- I resistori sono rappresentati da una linea a zigzag
- I fili conduttori ideali con resistenza trascurabile sono rappresentati con una linea retta.
# Seconda legge
La resistenza di un filo conduttore di lunghezza $L$ e sezione $A$ è
$$
R=\rho*\frac{L}{A}
$$
dove $\rho$ è la resistività del materiale. 
- Gli isolanti hanno grandi valori di resistività 
- I conduttori hanno valori piccoli che aumentano con la [[Temperatura]]  
- I semiconduttori valori intermedi che diminuisce con la temperatura

$$
\rho=\rho_0[1+\alpha(T-T_0)]
$$
- $\rho_{0}$ è la resistività a $T_0$
- $\alpha$ è il coefficiente di [[Temperatura]] della resistività ed è positivo per i conduttori (metalli) e negativo per i semiconduttori.
Dato che $R=\rho*\frac{L}{A}$  moltiplicando tutto per $\frac{L}{A}$ otteniamo:
$$
R=R_0[1+\alpha(T-T_0)]
$$
# Superconduttori
Nei superconduttori la resistività tende a 0 al di sotto di una [[Temperatura]] critica $T_c$, di solito vicina allo [[Zero Assoluto]]. Dato che tede a 0, una corrente può scorrere indefinitamente senza il bisogno di una forza elettromotrice.

# Potenza elettrica
>Collegando ogni morsetto di una batteria ad un morsetto di un dispositivo la batteria mantiene una differenza di potenziale tra i morsetti del dispositivo, così trasportando energia.

$$
P=\frac{\Delta U}{\Delta t}
$$
dato che $$
V=\frac{U}{q}
$$e
$$
I=\frac{\Delta q}{\Delta t}
$$
$$
P=\frac{\Delta q}{\Delta t}V
$$
$$
P=I*V
$$

>Quando la carica si muove attraverso un circuito perde energia potenziale elettrica. (sia per la resistenza che per il dispositivo che utilizza la carica). Quando ritorna alla batteria acquista energia potenziale a discapito dell'energia chimica immagazzinata.
## Effetto joule
Quando un resistore è attraversato da corrente si scalda, perchè gli elettroni di conduzione vengono accellerati dalla differenza di potenziale e trasferiscono energia cinetica attraverso urti.
La potenza dissipata si ottiene sostituendo la legge di ohm alla fornmula della potenza.
>$P=R*I^2$              $P=\frac{V^2}{R}$

# Resistenza equivalente
La resistenza equivalente è la resistenza di un singolo resistore che se sostituito all'insieme verrebbe attraversato dalla stessa corrente $I$ alla stessa differenza di potenziale $V$.

# Resistenza Interna
I generatori di tensione hanno una resistenza interna, dovuta alla dispersione di energia all'interno del dispositivo. 
$$
V_i=r*I
$$
- $V_i$ è la caduta di tensione
- $r$ è la resistenza interna
La differenza di potenziale ai poli è data da 
$$
V_{AB}=fem-V_i
$$
>Quindi la differenza di potenziale è uguale alla forza ellettromotrice quando la corrente è praticamente nulla.

# Leggi di Kirchhoff
## Prima 
Un nodo è un punto in cui confluiscono tre o più fili. 
La corrente ($I$) entrante in un nodo deve essere uguale alla corrente uscente dal nodo.
# Seconda 
Una maglia è un tratto chiuso di circuito. Può essere anche il circuito stesso. 
Lungo la maglia la somma algebrica delle differenze di potenziale è 0.

# Il galvanometro 
Misura piccoli valori di corrente con effetti magnetici. è usato nell'
- Amperometro
	- Misura $I$ essendo collegato in serie
- Voltmetro 
	- misura $V$  tra due punti essendo collegato in parallelo

# Resistori in serie
__STESSA CORRENTE ELETTRICA $I$__
>Si può dimostrare con la somma delle V

$$R_E=R_1+R_2+...$$
Perchè la differenza di potenziale è divisa tra i due resistori.

La potenza $P$ dissipata è uguale a quella dissipata dalla resistenza equivalente.
![[Pasted image 20240402154443.png|300]]
Se la corrente non attraversa un resistore non attraversa neppure l'altro.
# Resistori in parallelo
__STESSA DIFFERENZA DI POTENZIALE $V$__
>Si può dimostrare con la somma delle I
$$
\frac{1}{R_E}=\frac{1}{R_1}+\frac{1}{R_2}+...
$$
>Perchè V è uguale?

$R_E$ è sempre più piccola di tutte le resistenze individuali.
La potenza dissipata è uguale alla potenza fornita a un resistore equivalente.
![[Pasted image 20240402154756.png|300]]
Se la corrente si interrompe in un resistore non si bloccano gli altri.
>Il resistore con la resistenza minore ha il maggior contributo. Se una resistenza tende a zero cortocircuita le altre, perchè la corrente fluisce solo lungo il percorso di resistenza nulla.

# Condensatore equivalente 
Il condensatore equivalente immagazzina la stessa carica e la stessa energia data una differenza di potenziale.
# Condensatori in parallelo
__STESSA DIFFERENZA DI POTENZIALE $V$__
>Si può dimostrare con la somma delle $q$
$$
C_E=C_1+C_2+...
$$
La formula è così perchè la carica di un condensatore è direttamente proporzionale alla capacità, mentre la corrente di un resistore è inversamente proporzionale alla resistenza.

L'energia totale si può calcolare con la somma delle energie individuali.

La batteria sposta una carica per ciascun condensatore
# Condensatori in serie 
__Stessa carica $q$__
>Si può dimostrare con la somma delle V
$$
\frac{1}{C_E}=\frac{1}{C_1}+\frac{1}{C_2}
$$


La batteria sposta una carica sola $q$, che passa per induzione da un condensatore all'altro.
>La batteria fornisce una carica $q$, che arrivando al primo condensatore per repulsione spinge un altra carica $q$ e così via.

L'energia immagizzata è la somma delle energie immagizzinate da ogni singolo condensatore.