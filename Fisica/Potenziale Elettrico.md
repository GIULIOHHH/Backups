---
tags: fisica
---
>L'energia totale di un oggetto si conserva quando su di esso agiscono solo forze conservative.
# Energia potenziale 
La forza elettrica (come quella gravitazionale) è una forza __conservativa__, quindi il [[Lavoro]] che compie su un oggetto non dipende dal cammino percorso, ma solo dalla posizione iniziale e quella finale. Quindi il [[Lavoro]] di un percorso chiuso è nullo. 


Dato che è una forza conservativa ha la propria energia potenziale.
La variazione di energia energia potenziale per una carica che si sposta da $A$ a $B$ equivale all'opposto del lavoro $L_{AB}$ della forza elettrica compiuto su essa.

$$
U=q*E*h
$$
>Generalmente $q$ equivale a $m$, $E$ equivale a $g$ e $k$ equivale a $G$.
>$$
F=G*\frac{m*M}{r^2}
$$
$$
F=k*\frac{q*Q}{r^2}
$$
![[Lavoro]]
### Energia potenziale di un sistema di cariche
Dato che $\overrightarrow{L}=\overrightarrow{F}*\overrightarrow{s}$, sostituendo la legge di Coulumb otteniamo
$$
U=k*\frac{q_1*q_2}{r}
$$
>$s$ e $r$ sono equivalenti quindi li semplifichiamo.

Per convenzione $U=0$ quando le masse sono a distanza infinita.
>La forza di gravità è solo attrattiva e compie sempre un lavoro negativo.

La forza elettrostatica invece può essere sia attrattiva $q_1*q_2<0$ ($U$ negativo) che repulsiva  $q_1*q_2>0$ ($U$ positivo).
>Per questo nella formula non c'è il valore assoluto.

Questa formula può essere interpretata come:
- Il lavoro che la forza elettrica compie quando il sistema viene separato e le cariche sono allontanate a distanza infinita
- Il lavoro che una forza esterna compie per assemblare il sistema, portando le cariche da distanza infinita (dove non hanno attrazione) fino alla loro posizione
# Potenziale elettrico
Il potenziale elettrico in un punto è il rapporto tra l'energia potenziale elettrica  $U$ di una carica in quel punto e la carica stessa $q_0$
$$
V=\frac{U}{q_0}
$$
Si misura in $J/C$, ovvero _Volt_ $[V]$
>è energia per unità di carica.

La differenza di potenziale per andare da A a B:
$$
\Delta V=\frac{\Delta U}{q_0}=-\frac{L_{AB}}{q_0}
$$
>Non è possibile misurare ne il valore di $V$ e nemmeno quello di $U$ in un punto in termini assoluti. Possiamo misurare solo le loro differenze, perchè esse sono legate al lavoro.

Per convenzione $V=0$ per i punti a distanza infinita dalle cariche che generano il potenziale.
Una carica positiva accellera da una regione con potenziale maggiore verso una con potenziale minore. 
Una carica negativa fà il contrario.

L'energia delle partielle si misura in elettronvolt $eV$, la variazione di energia potenziale $\Delta U$ subita da un elettrone quando si muove attraverso una differenza di potenziale $\Delta V=1V$.
$$
1eV=1.60*10^{-19}J
$$


Potenziale di una carica puntiforme:
$$
V=\frac{k*q}{r}
$$
>Se $q$ è positivo lo è anche $V$, quindi si innalza il potenziale.

Il potenziale in un sistema di cariche è dato dalla somma dei singoli potenziali.
# Dimostrazione
Una carica $q$ crea un potenziale. Una carica $+q_0$ si muove da $A$ a $B$.
Il lavoro della forza elettrica è
$$
L_{AB}=U_A-U_B
$$
$$
L_{AB}=k*\frac{q*q_0}{r_A}-k*\frac{q*q_0}{r_B}
$$
sostituendolo in $\Delta V$:
$$
V_B-V_A=\frac{k*q}{r_B}-\frac{k*q}{r_a}
$$
Quando $B$ tende all'infinito $V_B$ tende a 0, quindi si ottiene la formula di sopra.
# Superfici equipotenziali
In una __Superficie equipotenziale__ il potenziale è uniforme in ogni punto.
Punti equidistanti da una carica sono equipotenziali. Quindi data una carica esistono infinite superfici equipotenziali sferiche con la carica al centro.

__La forza elettrica non compie lavoro su una superficie equipotenziale__. 
>Perchè $\Delta V=0$ e $\Delta V=-L/q$.

In ciascun punto di una superficie equipotenziale il campo elettrico è [[perpendicolare]] alla superficie e punta verso l'esterno (potenziale decrescente perchè a distanza maggiore).

![[Pasted image 20240312161120.png|400]]
>Se il campo elettrico non fosse perpendicolare ci sarebbe una componente parallela che eserciterebbe una forza su una carica di prova, facendola muovere, quindi facendo compiere un lavoro alla forza elettrica. Questo è impossibile.

La superficie di un conduttore è equipotenziale (il campo elettrico è [[perpendicolare]] ad essa).
All'interno del conduttore il campo elettrico è nullo, quindi può essere considerato un volume equipotenziale.

Le linee di campo:
- Indicano la direzione in cui $V$ cambia più velocemente
- Sono più dense dove $V$ cambia più rapidamente.


In un condensatore le superfici equipotenziali sono le armature e infiniti piani paralleli alle armature.
![[Pasted image 20240312162801.png|300]]
Il lavoro per andare dall'armatura positiva a quella negativa è
$$
L_{AB}=F*\Delta s
$$
$$
F=q_0*E
$$
$$
L=q_0*E*\Delta s
$$
Sostituendolo nel potenziale otteniamo
$$
\Delta V=-E*\Delta s
$$
Quindi
$$
E=-\frac{\Delta V}{\Delta s}
$$
$\Delta V/\Delta s$  è detto __Gradiente del potenziale__.
Se consideriamo un campo elettrico uniforme qualsiasi:
$$
\Delta V=-\overrightarrow{E}*\overrightarrow{\Delta s}
$$
Questa formula dà solo la componente del campo elettrico lungo lo spostamento e non quella [[perpendicolare]] ad esso. 

# Circuitazione del Campo elettrico
Prendiamo una curva chiusa. Scegliamo un verso di percorrenza e la dividiamo in porzioni così piccole che ciascuna di essa:
- è rettilinea (indicata da un vettore spostamento tra i suoi estremi)
- forma un angolo $\theta_k$ con il campo elettrico $E_k$.
La circuitazione è quindi
$$
\Gamma=\sum\limits_{k} \overrightarrow{E}_k*\overrightarrow{\Delta l_k}  
$$
$$
\Gamma=\sum\limits_{k} E_{k}*\Delta l_k*cos(\theta_k)
$$
$$
\Gamma=\sum\limits_k \Delta V_k
$$
La circuitazione avviene lungo una curva chiusa, e dato che il potenziale non dipende dal cammino percorso $V_i=V_f$, quindi 
__La circuitazione del Campo elettrico lungo una curva chiusa è sempre nulla.__
$$
\Gamma=0
$$
La circuitazione dimostra che la forza elettrostatica è conservativa e il campo elettrico è un campo conservativo.

La circuitazione è definita anche per un campo Vettoriale generico (oltre al campo elettrico) e riassume il suo comportamento in un percorso chiuso.
>Se il campo è uniforme la circuitazione è nulla.
Se il campo è parallelo la circuitazione non è nulla.
![[Pasted image 20240312181957.png|600]]
>Nel caso di un campo di forze la circuitazione è il lavoro lungo la curva chiusa.

# Capacità
Accumulare carica su un conduttore è ostacolato dal fatto che cariche di segno uguale si respingono.
Il problema si risolve se poniamo il conduttore a un potenziale di segno opposto rispetto alla carica.
La capacità rappresenta l'abilità di immagazzinare carica.
$$
C=\frac{q}{V} 
$$
>$V$ è il potenziale del conduttore rispetto a terra (quindi considerando nullo quello del terreno)

Si misura in farad $F$.
>I farad sono enormi quindi usiamo i sottomultipli

Sostituendo $V$ per cariche puntiformi nella formula otteniamo:
capacità di un conduttore sferico$$
C=\frac{R}{k}
$$
## Capacità con i condensatori 
Con $V$ di solito indichiamo anche la __differenza__ di potenziale tra le armature di un condensatore.
La carica su ogni armatura è
$$
q=C*V
$$
>è la formula inversa

Possiamo inserire un dielettrico (un isolante) tra le armature del condensatore.
Il campo elettrico determina uno spostamento di alcuni elettroni delle molecole del dielettrico, rendendole tutte polari.
Le estremità negative sono attratte dall'armatura positiva e viceversa, quindi le molecole si dispongono regolarmente con le estremità opposte a contatto.
Così la superficie del dielettrico vicino all'armatura positiva si carica negativamente e viceversa.
![[Pasted image 20240313160525.png]]
Non tutte le linee di forza attraversano il dielettrico, alcune terminano sulla superficie negativa e fuoriescono da quella positiva. Descriviamo la diminuizione del campo elettrico come la [[Costante dielettrica]] relativa:
$$
ε_r=\frac{E_0}{E}
$$

$ε_r$ è senza unità, inoltre è sempre maggiore di 1, dato che il campo elettrico nuovo $E$ diminuisce rispetto a quello senza dielettrico $E_0$.

$$
F=\frac{k}{ε_r}*\frac{q_1*q_2}{r^2}
$$

Dato che 
$$
E=\frac{q}{A*ε_0*ε_r}
$$
$$
E=\frac{V}{d}
$$
Uguagliandole
$$
\frac{q}{A*ε_0*ε_r}=\frac{V}{d}
$$
sostituiendo in $q=V*C$
$$
C=\frac{A*ε_0*ε_r}{d}
$$
Quindi la capacità deel condenstatore aumenta inserendo il dielettrico.

# Energia di un condensatore 
Caricando un condensatore, viene compiuto un lavoro per trasferira cariche da un armatura all'altra.
$$
L=q*\overline{V}
$$
Spostando una carica varia il potenziale, quindi è necessario un lavoro maggiore. Per questo usiamo la differenza di potenziale media, che è la metà del potenziale finale 
$$
L=\frac{1}{2}*q*V
$$
>Il lavoro può essere rappresentato anche come l'area sottesa dal grafico tra $q=0$ e il valore finale di carica.
>![[Pasted image 20240313155707.png|300]]
Questo lavoro si conserva come energia potenziale elettrica accumulata nel condensatore.

Dalla formula inversa di $V$:
$$
U=q*V
$$
quindi nel nostro caso
$$
U=q*\frac{V}{2}
$$
inoltre 
$$
q=C*V
$$
$$
U=\frac{1}{2}*C*V^2
$$
Sostituendo $V=E*d$ e $C=A*ε_0*ε_r/d$
$$
U=\frac{1}{2}d*A*E^2*ε_0*ε_r
$$
dato che $A*d$ è il volume tra le armature
$$
U=\frac{1}{2}*Vol*E^2*ε_0*ε_r
$$
Oppure la densità di energia 
$$
U_{Vol}=\frac{U}{Vol}
$$
$$
U_{Vol}=\frac{1}{2}*E^2*ε_0*ε_r
$$

![[Pasted image 20240313160311.png|300]]
![[Pasted image 20240313160321.png|300]]