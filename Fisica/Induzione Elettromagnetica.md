---
tags: fisica
---
# Induzione 
Un campo magnetico può generare corrente:
In una bobina si genera corrente quando c'è un moto relativo tra la bobina e un magnete.
>Si avvicina il magnete aumenta l'intensità del campo magnetico. 
>Si allontana il magnete diminuisce l'intensità.

![[Pasted image 20241010183659.png]]
Il campo magnetico variabile fa si che la bobina si comporti come una sorgente di [[Circuiti Elettrici#Circuiti]|fem]], chiamata __fem indotta__.
la **fem indotta** genera una **corrente indotta** nella bobina.
Questo fenomeno è detto induzione elettromagnetica.
>Si può determinare anche cambiando l'area di un circuito che si trova in un campo magnetico costante.
>
![[Pasted image 20241010184122.png|200]]

Quando una sbarretta conduttrice si muove a velocità $v$ in un campo magnetico, al suo interno si genera una fem indotta detta **fem cinetica** a causa della [[Magneti#Forza di Lorentz|Forza di Lorentz]].
![[Pasted image 20241010184331.png|300]]
Ogni carica si muove con una velocità uguale e le cariche negative si separano da quelle positive. 
>Questo lo capiamo tramite la [[Magneti#Forza di Lorentz|Prima regola della mano destra]],

Le cariche si muovono finchè non si eguagliano la forza elettrostatica e la [[Magneti#Forza di Lorentz|Forza di Lorentz]].\
$$
\mathcal{E}=\frac{L}{q}
$$
$$
\mathcal{E}=\frac{F*s}{q}
$$

$$
\frac{F}{q}=E
$$
$$
\mathcal{E}=E*s
$$
($s$ si può anche scrivere come $L$)
$$
E=\frac{\mathcal{E}}{s}
$$
Uguagliando La forza elettrostatica con quella di lorentz:
$$F_E=E*q$$
$$F_E=\frac{\mathcal{E}}{L}*q$$
$$
F_B=q*v*B
$$
Uguagliando le due forze:
$$
\frac{\mathcal{E}}{L}=v*B
$$
quindi, **QUANDO $\overrightarrow v$, $\overrightarrow B$ e $\overrightarrow L$ SONO PERPENDICOLARI**
$$
\mathcal{E}=v*B*L
$$
# Legge di Faraday-Neumann-Lenz

In un tempo $\Delta t$, la barretta ha una velocità uguale a $\frac{\Delta s}{\Delta t}$. 
Sostituendo:
$$
\mathcal{E}=\frac{\Delta s}{\Delta t}*B*L
$$
$\Delta s * L$ (spostamento orizzontale per altezza della barretta) è uguale alla variazione dell'area $\Delta A$.
$$
\mathcal{E}=\frac{\Delta A*B}{\Delta t}
$$
$\Delta A*B$ è uguale alla variazione del [[Magneti#Teorema di Gauss|Flusso del campo magnetico]].
$$
\mathcal{E_{media}}=-\frac{\Delta \Phi(\overrightarrow B)}{\Delta t}
$$
>Il segno meno è spiegato dalla [[#Legge di Lenz]].

Quella calcolata è la **fem cinetica** _media_. Quella _istantanea_ può essere calcolata con la [[Derivata]].
$$
\mathcal{E}=-\frac{d  \Phi(\overrightarrow B)}{d t}
$$
### Legge di Lenz
Ogni volta che la fem genera una corrente, [[Magneti#**CAMPO MAGNETICO** di un Filo percorso da corrente (non immerso)|viene generato]] un **campo magnetico indotto**.
Il verso della [[Magneti#Forza di Lorentz|forza magnetica]] è opposto a quello della velocità, quindi per mantenere la sbarretta in moto è necessaria un'altra forza costante parallela alla velocità.

La corrente indotta dalla **fem cinetica** ha un verso tale da [[Magneti#**CAMPO MAGNETICO** di un Filo percorso da corrente (non immerso)|Generare un campo magnetico indotto]] che si oppone alla variazione del flusso magnetico ($\Delta \Phi$) che l'ha generata. 

>[!info] Il campo magnetico indotto cerca di far ritornare $\Delta \Phi$ a $0$.

Oppure può essere anche la corrente stessa ciò che si oppone alla variazione che del flusso magnetico che l'ha generata.

La corrente crea un **campo magnetico indotto** che:
- è opposto al campo magnetico esterno se $\Delta \Phi >0$
	- Il campo magnetico esterno avvicinandosi aumenta $\Delta \Phi$, quindi opponendosi all'avvicinamento lo porta verso $0$.
- ha lo stesso verso del campo magnetico esterno se $\Delta \Phi <0$
	- Il campo magnetico allontanandosi diminuisce  $\Delta \Phi$, quindi opponendosi all'allontanamento lo porta verso $0$.

>1. Un magnete si avvicina ad una spira.
>2. la variazione del flusso è positiva, perchè più si avvicina il magnete più aumenta.
>3. Per opporsi all'aumento del flusso, il verso del campo magnetico indotto deve essere opposto a quello del magnete.
>4. Per generare questo campo la corrente deve essere in senso antiorario. (secondo la [[Magneti#Seconda regola della mano destra|Seconda regola della mano destra]].)
>
![[Pasted image 20241010191348.png|300]]

Se la legge di Lenz non valesse, non ci sarebbe conservazione dell'energia:
1.  $\Delta \Phi$ genererebbe fem indotta ($\mathcal{E}$).
 2. La fem indotta $\mathcal{E}$ genererebbe corrente indotta.
 3. La corrente indotta genererebbe un campo con lo stesso segno di  $\Delta \Phi$.
4. Il ciclo si ripeterebbe all'infinito generando energia infinita.

# Alternatori
Un alternatore produce energia elettrica partendo da energia meccanica.
- è formato da una [[Magneti#Spira percorsa da corrente in un campo magnetico|Spira che ruota in un campo magnetico]].
- Ciascun estremo della spira termina con un anello metallico che striscia contro una spazzola di carbone, a cui è connesso il circuito esterno.

L'angolo dell'alternatore varia:
$$
\theta=\omega*t
$$
Il flusso in un certo istante è
$$
\Phi(\overrightarrow E)=B*A*cos(\theta)
$$
$$
\Phi(\overrightarrow E)=B*A*cos(\omega*t)
$$
In un certo istante, la [[#Legge di Faraday-Neumann-Lenz|fem cinetica istantanea]] è:
$$
\mathcal{E}=-\frac{d \Phi(\overrightarrow B)}{d t}
$$
$$
\mathcal{E}=-\frac{d(B*A*cos(\omega*t))}{dt}
$$
Secondo la [[Derivata#Derivate fondamentali|Derivata fondamentale del coseno]] e la [[Derivata#$D[f(g(x))]=f {'}[g(x)]*D[g(x)]$|formula per la derivata di una funzione composta]], risolvendo usando la $t$ come $x$:
$$
dt=1
$$
$$
d(\omega*t)=\omega
$$
$$
d(cos(\omega*t))=-sin(\omega*t)*\omega
$$
$$
\mathcal{E}=B*A*sin(\omega*t)*\omega
$$
Con $\mathcal{E}_0$ indichiamo il valore massimo della **fem indotta**.
$$
\mathcal{E}_0=B*A*\omega
$$
$$
\mathcal{E}=\mathcal{E}_0*sin(\omega*t)
$$
## Corrente Alternata
Nel circuito connesso all'alternatore scorre una corrente alternata:
$$
I=I_0*sin(\omega*t)
$$
### Nei circuiti [[#Circuito resistivo|Resistivi]]:
Secondo la [[Circuiti Elettrici#Legge di Ohm|Legge di Ohm]]:
$$
I_0=\frac{\mathcal{E}_0}{R}
$$
La [[Circuiti Elettrici|Potenza]] si calcola con:
$$
P=I*\mathcal{E}
$$
oppure
$$
P=I_0*\mathcal{E}_0*sin^2(w*t)
$$
La potenza massima è
$$
P_0=I_0*\mathcal{E}_0
$$
La potenza media è metà della potenza massima 
$$
\overline P=\frac{P_0}{2}
$$
La potenza media si può calcolare anche col prodotto tra _corrente efficace_ e _fem efficace_:
$$
\overline P=\frac{I_0}{\sqrt 2}*\frac{\mathcal{E}_0}{\sqrt 2}
$$
>In Italia la fem efficace è di $230 V$.

# Corrente di Foucault
In un blocco metallico (conduttore) in cui c'è una variazione di flusso magnetico, si generano correnti indotte, o parassite, perchè la resistenza interna è molto piccola. 
>Se non si vogliono (pk disperdono energia e riscaldano) si possono inserire superfici isolanti per aumentare la resistenza.

>Oppure può essere usata per frenare i treni.
# Mutua induzione/Autoinduzione
Una bobina (primaria) è collegata a un generatore di corrente alternata, quindi genera (un flusso magnetico e) una fem.
- Se è in un altra bobina (secodnaria), si ha **mutua induzione**.
- Se è nella stessa bobina si ha **autoinduzione**.
	- Un circuito che attraversato da corrente autoinduce un campo magnetico si chiama *induttore*.
![[Pasted image 20241121154839.png|400]]
>Valgono le stesse proprietà della [[#Legge di Lenz]].

La fem subita è [[#Legge di Faraday-Neumann-Lenz|proporzionale a]] $\Delta\Phi$, ma $\Delta \Phi$ è [[Magneti#**CAMPO MAGNETICO** di un Filo percorso da corrente (non immerso)|proporzionale a]] $B$ che è proporzionale alla corrente $I$.
Quindi si inserisce una costante di proporzionalità misurata in Henry $[H]$:
- Nella mutua induzione $M$ è la **mutua induttanza**.
	- $\Delta\Phi*N=M*I$
	- Qua si inserisce $N$, (spire della bobina secondaria)
- Nella autoinduzione $L$ è la **autoinduttanza**.
	- $\Delta\Phi=L*I$
Si possono sostituire in [[#Legge di Faraday-Neumann-Lenz|Faraday-Neumann]]:
$$
\mathcal{E}=-M*\frac{\Delta I}{\Delta t}
$$
$$
\mathcal{E}=-L*\frac{\Delta I}{\Delta t}
$$
### Autoinduttanza di un solenoide 
Formula del flusso:
$$
\Phi=N*B*A
$$
Formula del [[Magneti#Solenoide|Solenoide]]:
$$
B=\mu_0*\frac{N}{L}*I
$$
Sostituendo:
$$
\Phi=A*\mu_0*\frac{N^2}{L}*I
$$

Sostituendo nella formula dell'[[#Mutua induzione/Autoinduzione|Autoinduzione]]:
$$
L=A*\mu_0*\frac{N^2}{L}
$$
>[!note] La formula è la stessa per calcolare $B$, solo che $N$ è al quadrato, è aggiunta l'area $A$ al posto di $I$.

Un solenoide può immagazzinare energia, perchè compie un lavoro per mantenere una corrente.

#### Dimostrazione
Secondo la formula del [[Potenziale Elettrico]]:
$$
V=-\frac{\Delta W}{\Delta q}$$
$$
\Delta W=-\mathcal{E}*\Delta q
$$
Sostituendo la formula dell'[[#Mutua induzione/Autoinduzione|Autoinduzione]]:
$$
\Delta W=L*\frac{\Delta I}{\Delta t}*\Delta q
$$
dato che:
$$
I=\frac{\Delta q}{\Delta t}
$$
$$
\Delta W=L*{\Delta I}*I
$$
>${\Delta I}$ e $I$ sono due cose diverse.

Il lavoro totale compiuto dalla corrente mentre va da $0$ al valore finale si calcola con l'integrale.
$$
W=\frac{1}{2}*L*I^2
$$
Possiamo sostituire $L$ con la formula Dell'[[#Autoinduttanza di un solenoide]].
$$
W=\frac{1}{2}*\mu_0*\frac{N^2}{L}*A*I^2
$$
Possiamo sostituire $I$ con la formula inversa del [[Magneti#Solenoide|Solenoide]]:
$$
W=\frac {B^2*A*L}{2*\mu_0}$$
$A*L$ è il volume $Vol$.

$$
W=\frac {B^2*Vol}{2*\mu_0}
$$
>Dividendo per il volume otteniamo la densità di energia, risultato valido in generale in ogni punto dove c'è un campo magnetico. Quindi il campo magnetico può immagazzinare energia

# Circuito RL
Un circuito RL è formato da un [[Circuiti Elettrici|Resistore]] con resistenza $R$ e da un [[#Mutua induzione/Autoinduzione|Induttore]] con induttanza $L$.
![[Pasted image 20241121163016.png]]
1. Quando l' interruttore è aperto la corrente è nulla.
2. Se l'interruttore è chiuso la corrente inizia a crescere, nell'induttore si sviluppa una corrente che si [[#Legge di Lenz|oppone a questa crescita]].
	1. L'intensità della [[Circuiti Elettrici# Leggi di Ohm|Legge di Ohm]] $I=V/R$, non viene raggiunta subito, ma dopo molto tempo.
	2. $I$ cresce secondo:$$ I=\frac{V}{R}*(1-e^{-\frac{R*t}{L}})$$
	3. $e$ è elevato a $-R*t/L$
	4. ![[Pasted image 20241121163300.png|300]]
3. **Quando la corrente scorre con valore costante, l'induttore non ha effetto.** (vale la [[Circuiti Elettrici# Leggi di Ohm|Legge di Ohm]])
4. Se apriamo l'interruttore la corrente smette di circolare, nell'induttore si sviluppa una corrente che si [[#Legge di Lenz|oppone a questa diminuzione]].
	1. La corrente complessiva diminuisce asintoticamente.
	2. ![[Pasted image 20241121163937.png|300]]

# Circuiti in corrente alternata
## Circuito resistivo
- Contiene solo resistori.
- La corrente inverte il verso ogni volta che si inverte la polarità del generatore.
- fem e corrente sono *in fase*.
![[Pasted image 20241121164128.png|400]]
## Circuito Capacitivo
- Contiene solo [[Elettricità#Condensatori Piani|Capacitori]] (chiamati anche condensatori).
	- ![[Pasted image 20241121164510.png|400]]
- La corrente è sfasata in anticipo di $90 °$ rispetto alla fem
	- La corrente è **avanti** di un quarto di ciclo.
- La potenza/energia media utilizzata dal condensatore **è nulla**.
	- La potenza varia tra valori positivi e negativi in uguali tempi (per metà del tempo è positiva.)
		- Tra $A$ e $B$, sia $I$ che $\mathcal{E}$ sono positivi, [[Circuiti Elettrici#Potenza elettrica|quindi]] $P$ positiva. 
		- Tra $B$ e $C$, $\mathcal{E}$ è positiva, $I$ negativa, [[Circuiti Elettrici#Potenza elettrica|quindi]] $P$ negativa
	- ![[Pasted image 20241121164543.png|400]]
-  $\mathcal{E}_{eff}=X_C*{I}_{eff}$
	- $X_C$ è la **reattanza capacitiva** $$ X_C=\frac{1}{\omega C}$$
	- Dove $C$ è la [[Elettricità#Condensatori Piani|Capacità]].
	- Resistenza trascurabile se la frequenza è alta.

>[!info] $\mathcal{E}_{eff}=X*{I}_{eff}$ è come se fosse [[Circuiti Elettrici|Ohm]] ma con $X$ invece di $R$ e i valori efficaci.

## Circuito induttivo
- Contiene solo un induttore.
- La corrente è **indietro** di un quarto di ciclo.
	- La potenza/energia media utilizzata **è nulla**.
![[Pasted image 20241121165619.png|300]]
![[Pasted image 20241121165639.png|300]]
-  $\mathcal{E}_{eff}=X_L*{I}_{eff}$
	- $X_L$ è la **reattanza induttiva** $$ X_L={\omega L}$$- Resistenza trascurabile se la frequenza è bassa.

## Circuiti RLC
Contiene un [[#Circuito resistivo|resistore]], un [[#Circuito Capacitivo|condensatore]] e un [[#Circuito induttivo|induttore]].
![[Pasted image 20241121170807.png|300]]
$$\mathcal{E}_{eff}=Z*{I}_{eff}$$
Dove $Z$ è l'**impedenza**.
$$
Z=\sqrt{R^2+(X_L-X_C)^2}
$$
L'angolo di sfasamento $\theta$ tra corrente e tensione è:
$$
tan(\theta)=\frac{X_L-X_C}{R}
$$
$$
\overline P={I_{eff}}*{\mathcal{E}}_{eff}*cos(\theta)
$$
La corrente è massima quando $X_{L}-X_C=0$.
Ovvero quando si ha frequenza di risonanza, ottenuta sostituendo le due formule.
$$
f=\frac{1}{2*\pi \sqrt{L*C}}
$$
In questo caso $Z=R$, fem e corrente sono in fase, come un circuito RL.
>Se due parti dell'impedenza sono uguali a $0$ si ha un circuito precedente (tipo RL se $X_L=0=X_C$)

# Trasformatore
Aumenta o diminuisce la tensione alternata.
![[Pasted image 20241121171458.png]]
$$
\frac{V_s}{V_p}=\frac{N_s}{N_p}
$$