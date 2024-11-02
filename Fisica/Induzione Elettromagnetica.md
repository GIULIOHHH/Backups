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