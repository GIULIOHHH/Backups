>Ovunque si parla di sistema di riferimento ci si riferisce ai [[Sistema di Riferimento Inerziale|Sistemi di Riferimento Inerziali]]!
>
>Tecnicamente la Terra non è completamente inerziale perchè ruota attorno al suo asse e attorno al Sole, ma gli effetti sono così piccoli che possono essere ignorati.

---
# Relatività Galileiana
1. **Le leggi fisiche sono assolute:** sono uguali in qualsiasi [[Sistema di Riferimento Inerziale]].
2. **Il moto è relativo:** Si può dire che un sistema di riferimento è in moto solo se cambia la sua posizione rispetto ad un altro. 
	1. Senza un riferimento esterno non è possibile capire quale dei due sistemi è effettivamente in moto.

Quindi non è possibile capire se un sistema di riferimento è in moto solo osservando le leggi fisiche.

>- Non esiste un sistema di riferimento *privilegiato.*
>	- Non esiste una *Velocità Assoluta*

>**Problemi con la Relatività Galileiana:**
>---
>Particelle in Moto
>---
>Abbiamo due protoni in moto con velocità e distanza costanti.
>Nel sistema di riferimento del laboratorio abbiamo:
>- [[Elettricità#Legge di Coulomb|Forza Elettrica Repulsiva]]
>- [[Magneti#Forza di Lorentz|Forza Magnetica Attrattiva]] (dipende dalla velocità)
>
>Ma nel sistema di riferimento [[Solidale]] ai protoni essi rimangono fermi nello spazio, quindi abbiamo solo:
>- [[Elettricità#Legge di Coulomb|Forza Elettrica Repulsiva]]
>
>Che forza subiscono le particelle?
>
>---
>
>Velocità della Luce
>---
>In che sistemi di riferimento la [[ Luce#^7f21aa|Velocità della Luce nel vuoto]] è uguale a $c$?
>- In tutti?
>	- Allora non varrebbero le [[Leggi Galileiane sulla composizione del moto]] *(La velocità non dipenderebbe dal sistema di riferimento).*
>- Solo in alcuni?
>	- Allora tramite esperimento sarebbe possibile capire se un sistema è in moto. *(Le leggi fisiche non sarebbero più assolute)*.

# Postulati della Relatività Ristretta
>Viene chiamata relatività ristretta perchè applicata solo ai [[Sistema di Riferimento Inerziale|Sistemi di Riferimento Inerziali]].
>Einstein estende la relatività di Galileo:
>- ai fenomeni scoperti dopo di lui (Dai fenomeni meccanici anche ai fenomeni elettrici e magnetici)
>- a osservatori che si muovono con velocità molto vicine alla luce.

>[!Done] **Principi:**
>1. **[[#Relatività Galileiana|Principio di Relatività]]:** Le leggi fisiche sono uguali in qualsiasi [[Sistema di Riferimento Inerziale]]. Non esiste sistema di riferimento privilegiato.
>2. **Principio di Invarianza della velocità della luce:** La [[ Luce#^7f21aa|Velocità della Luce nel vuoto]] ha sempre lo stesso valore in qualsiasi [[Sistema di Riferimento Inerziale]] *(Indipendentemente dalla velocità relativa tra sorgente e osservatore).*

>Soluzione alle Particelle in Moto
>---
>Campo elettrico e Campo magnetico assumono valori diversi in base al sistema di riferimento *(per via delle [[#Trasformazioni di Lorenz]])*, ma la loro relazione con il movimento delle particelle rimane costante.

## Esperimenti Sulla Velocità della Luce 
Una stella ruota attorno al Sole a velocità $v$ e periodo $T$.
La osserviamo a distanza $d$.
![[Pasted image 20250227210234.png]]
Secondo la [[#Relatività Galileiana|Relatività Galileiana]], la velocità della luce dovrebbe variare.
>- Quando la stella si avvicina dovrebbe essere $c+v$.
>- Quando la stella si allontana dovrebbe essere $c-v$.

 1.  Se la stella si trova in posizione $1$ *(In alto)* la luce dovrebbe arrivare in tempo:
$$
t_1=\frac{d}{c-v}
$$
2. Se la stella si trova in posizione $2$ *(In basso)* la luce dovrebbe arrivare in tempo:
$$
t_2=\frac{T}{2}+\frac{d}{c+v}
$$
>Perchè $T/2$ è il tempo per arrivare in posizione $2$.
3. Quando la stella ritorna in posizione $1$, la luce dovrebbe arrivare nel tempo
$$
t_3=T+t_1
$$
4. Quindi
$$\Delta t_{1->2}=t_2-t_1=\frac{T}{2}-\frac{2*d*v}{c^2-v^2}$$
>La formula finale si ottiene facendo i calcoli
5. Invece:
$$
\Delta t_{2->3}=t_3-t_{2}=\frac{T}{2}+\frac{2*d*v}{c^2-v^2}
$$
6. Quindi i due valori dovrebbero essere diversi, ma osservando **sono uguali a $T/2$**.
7. Questo è possibile solo se la velocità della luce rimane costante.
	1. Non si aggiunge o si sottrae niente da $c$.
# [Simultaneità](https://www.youtube.com/watch?v=SV6mzHH41gk)
>[!done] Legge
>1. Se due eventi avvengono contemporaneamente **nello stesso punto,** risultano simultanei in tutti i sistemi inerziali.
>2. Altrimenti la simultaneità di due eventi dipende dal moto dell'osservatore.

Abbiamo un treno con un osservatore $A$. Un osservatore $B$ è al di fuori del treno.

Due fulmini colpiscono simultaneamente lati opposti del treno. 
- Per $B$ i due fulmini sono simultanei.
	- Perchè $B$ rimane equidistante dai due punti.
- Per $A$, il fulmine destro avviene prima.
	- Perchè $A$ si muove verso la luce generata dal fulmine destro.
![[Pasted image 20250302195008.png]]
>- Se $A$ vedesse i due fulmini come simultanei, $B$ dovrebbe vedere il fulmine sinistro colpire prima.
>- La simultaneità dipende dal sistema di riferimento.

# Orologi a Luce
![[Pasted image 20250302205324.png]]
1. Una sorgente emette della luce.
2. La luce colpisce una parete e viene riflessa.
3. Ritorna alla prima parete e viene rilevata.
4. Viene registrato un *tic*.
5. Una sorgente emette della luce...
# Dilatazione Temporale

Un'astronauta su un astronave e un'osservatore a terra hanno due [[#Orologi a Luce]].

1. L'astronauta è a riposo **rispetto al suo orologio**. 
	1. Per lui sorgente e rilevatore si trovano nello stesso punto.
	2. La luce rimbalza verticalmente tra due specchi.
	3. Il **Tempo Proprio** $\Delta t_0$ è il tempo percepito dall'astronauta tra un rimbalzo e l'altro.
![[Pasted image 20250302205041.png]]
2. Un osservatore guarda da terra l'astronave. è in movimento **rispetto all'orologio** a velocità $v$.
	1. Per lui sorgente e rilevatore si trovano in punti diversi.
	2. Dato che l'astronave si muove orizzontalmente, la luce percorre una traiettoria inclinata.
	3. Poiché la velocità della luce è costante, la luce deve percorrere uno spazio maggiore.
	4. Questo significa che per l'osservatore terrestre **il tempo sull'astronave appare rallentato**.
		1. perchè per calcolare un secondo la luce deve viaggiare per più spazio.
		2. Il **Tempo Dilatato** $\Delta t$ è il tempo che l'osservatore a terra misura nell'astronave.
![[Pasted image 20250302205455.png]]

>- Il mio orologio batte il tempo più velocemente di qualsiasi altro orologio che si sta muovendo rispetto a me. $\Delta t> \Delta t_0$.
>- Per entrambi gli osservatori l'orologio dell'altro è più lento del proprio.

## Dimostrazione Formula
![[Pasted image 20250302212908.png]]
1. Osservando da terra, nel tempo di un *tic* spaziale, l'astronave si muove
$$
2L={v}*{\Delta t}
$$
>Usiamo $\Delta t$ perchè stiamo osservando da terra. $v$ è la velocità dell'astronave.
2. La luce invece percorre una distanza di $2s$. Usando Pitagora
$$2s=2*\sqrt{L^2+D^2}$$
3. Sostituendo $L$
$$2s=2*\sqrt{(\frac{v*\Delta t}{2})^2+D^2}$$
4. La formula inversa della definizione del tempo dilatato è
5. 
$$
2s=c*\Delta t
$$
6. Quindi sostituendo
$$c*\Delta t=2*\sqrt{(\frac{v*\Delta t}{2})^2+D^2}$$
eleviamo al quadrato.
$$
{(c*\Delta t)}^2={(v*\Delta t)}^2+{(2D)}^2
$$
fattorizziamo $\Delta t$
$$
\Delta t^2=\frac{{(2D)}^2}{(c^2-v^2)}
$$
Facciamo la radice.
$$
\Delta t=\frac{2D}{\sqrt{c^2-v^2}}
$$
Usciamo $c$ dalla frazione.

$$
\Delta t=\frac{2D}{c}*\frac{1}{\sqrt{1-(\frac{v}{c})^2}}
$$
2. Il tempo proprio è
$$
\Delta t_0=\frac{2D}{c}
$$
3. Sostituendo
$$
\Delta t=\frac{\Delta t_0}{\sqrt{1-(\frac{v}{c})^2}}
$$

>[!Done] Formula:
> Il fattore di dilatazione è:
>$$\gamma=\frac{1}{\sqrt{1-(\frac{v}{c})^2}}$$ Quindi:$$\Delta t=\gamma*\Delta t_0$$

>In generale in $\gamma$ $v$ è la velocità con cui si muove l'oggetto rispetto ad un sistema.
# Contrazione delle Lunghezze
Una navicella si muove dalla terra alla luna a velocità $v$. 
>Sia l'osservatore a terra che l'astronauta sono d'accordo sulla velocità relativa. 

Dato che $v$ è uguale per entrambi e il tempo [[#Dilatazione Temporale|risulta dilatato]], deve variare anche lo spazio.
>perchè $v=s/t$

L'osservatore che misura il tempo più breve misura la lunghezza più breve.
>Se l'osservatore terrestre misura un intervallo più lungo per mantenere uguale la velocità deve misurare anche una lunghezza maggiore.

- $L$ è la distanza misurata da un osservatore in moto da un punto all'altro.
- $L_0$ è la **Lunghezza Propria**, misurata da un osservatore a riposo **rispetto ai due punti**.

$L$ è sempre minore di $L_0$.

1. L'astronauta misura $v=L/{\Delta}t_0$
2. L'osservatore terrestre misura $v=L_0/\Delta t$
3. Uguagliando le $v$:
$$
\frac{L}{\Delta t_0}=\frac{L_0}{\Delta t}
$$
Sostituendo le formule del tempo:
>[!Done] Formula
>$$
L=\frac{L_0}{\gamma}
$$

>Per entrambi gli osservatori le lunghezze dell'altro sono contratte.

>$L_0$ e $\Delta t_0$ non possono essere misurati dalla stessa persona, perchè $L_0$ richiede una quiete rispetto all'oggetto in moto e $\Delta t_0$ richiede un sistema solidale all'oggetto in moto. 
### Direzione del moto
La contrazione delle lunghezze avviene solo lungo la direzione del moto.

>Se non fosse così un oggetto di altezza $h_0$ a riposo sarebbe più basso se visto da un sistema in moto.
>- Due osservatori tenendo righelli in mano si avvicinano. 
>- Per un osservatore il righello dell'altro risulta più piccolo del proprio.
>- Quando si incontrano, per un istante i due righelli si trovano affiancati, quindi è oggettivamente possibile capire quale dei due osservatori è in moto.
>- Questo contraddice [[#Postulati della Relatività Ristretta|Il principio di relatività]].
>- Nella direzione del moto invece non si può fare il confronto istantaneo tra i due oggetti (perchè uno è più lungo)
>- Bisogna registrare l’istante in cui passa il primo estremo e l’istante in cui passa il secondo estremo.
>- Il tempo di passaggio dipende dal sistema di riferimento e quindi anche la lunghezza misurata cambia.

# Dinamica
Le [[Leggi di Newton]] si mantengono?
#### Principio di Inerzia
Si. (è la base dei [[Sistema di Riferimento Inerziale|Sistemi di Riferimento Inerziali]])
#### $F=m*a$
No, perchè si potrebbe avere un accelerazione oltre $c$. Bisogna riscriverlo come:
$$
\overrightarrow{F}=
\frac{\Delta \overrightarrow{p}}{\Delta t}
$$
dove $\overrightarrow{p}$ è la [[Quantità Di Moto]].

$$
\overrightarrow p=\gamma*m*\overrightarrow v
$$

Se applichiamo una forza costante la [[Quantità Di Moto]] cresce e la velocità tende a $c$.
>Se facciamo la formula inversa per $v$, per $p$ che tende all'infinito $v$ tende a $c$.
### Conservazione del moto
La [[Quantità Di Moto]] relativistica di un sistema isolato si conserva in tutti i sistemi di riferimento inerziali.
>Non possiamo formularlo in termini di azione e reazione perchè non esiste la simultaneità.
# Relazione tra massa e energia
Un corpo di massa $m$ è fermo in un sistema di riferimento $K^{`}$.
Riceve due pacchetti di radiazione elettromagnetica di energia $ε$. 
La [[Quantità Di Moto#Nel caso di particelle prive di massa|Quantità di moto]] è quindi:
$$
p=+\frac{ε}{c}
$$
per quello diretto verso l'alto e
$$
p=-\frac{ε}{c}
$$
per quello diretto verso il basso.

La quantità di moto totale è nulla, così come quella finale.
![[Pasted image 20250508154342.png]]
Un sistema di riferimento $K$ si muove rispetto a $K^{`}$ con velocità $-v$ nell'asse $x$.
Nel sistema di riferimento $K$, il corpo si muove a velocità $v$ e quantità di moto $p_m=m*v*\gamma$ (nell'asse $x$.)

I fotoni si muovono sempre alla velocità della luce $c$, ma non è tutta verticale come in $K^{`}$. La velocità orizzontale è data da:
$$
v=c*sin(\alpha)
$$
![[Pasted image 20250508155220.png]]
La [[Quantità Di Moto#Nel caso di particelle prive di massa|Quantità di moto]] dei fotoni si può dividere nelle componenti:
$$
p_{x}=+\frac{ε}{c}*sin(\alpha)
$$
$$
p_{y}=\pm\frac{ε}{c}*cos(\alpha)
$$
La somma è:
$$
p_f=p_m+p_x+p_v$$
$$
p_f=m*v*\gamma\;+2*\frac{ε}{c}*sin(\alpha)+0
$$
Quindi la [[Quantità Di Moto#Nel caso di particelle prive di massa|Quantità di moto]] finale è solo lungo l'asse x.
La quantità di moto $p_x$ cambia la velocità con cui si muove il corpo, che diventa $v_f$, quindi $\gamma$ diventa $\gamma_f$ e possiamo scrivere la [[Quantità Di Moto#Nel caso di particelle prive di massa|Quantità di moto]] finale come
$$
p_f=m*v_f*\gamma_f
$$
I due devono essere uguali, quindi questa DOVREBBE essere vera:
$$
m*v*\gamma\;+2*\frac{ε}{c}*sin(\alpha)=m*v_f*\gamma_f
$$
In $K^{`}$ la velocità del corpo non cambia, quindi in $K$ $v=v_f$, ma questo renderebbe falsa l'equazione di sopra.
Ma cambiando la massa entrambi possono essere veri:
$$
m*v*\gamma+2*\frac{ε}{c}*sin(\alpha)=m_f*v*\gamma
$$
Riscrivendo:
$$
m_f=m+\frac{2}{ε*\gamma*c}*\frac{sin(\alpha)}{v}
$$
Dato che
$$
c*sin(\alpha)=v
$$
Facendo la formula inversa:
$$
m_f=m+\frac{2ε}{\gamma*c^2}
$$
Possiamo indicare la quantità di energia aggiunta con $\Delta E$:
$$
m_f=m+\frac{\Delta E}{\gamma*c^2}
$$
Spostando $m$ a sinistra otteniamo

>[!Done] Formula
>$$\Delta m=\frac{\Delta E}{\gamma*c^2}$$**Applicando una quantità di energia ad un corpo senza modificarne la velocità, ne si modifica la massa**.
>La massa di un corpo è una misura della sua energia.
>L'energia equivalente alla massa si misura con la formula inversa:
>$$E=\gamma*m*c^2$$
>Se il corpo è fermo misuriamo l'energia a riposo $E_0$.
$$E_0=m*c^2$$

Se il corpo si muove possiede l'energia cinetica:
$$
E=K+E_0
$$
>L'energia totale di un corpo è l'energia e riposo più l'energia cinetica.

Dalla formula inversa otteniamo l'energia cinetica.
>Non ha niente a che fare con l'energia cinetica classica, ma per velocità molto bassa si può approssimare a $E=m*v^2/2$

>Ogni variazione di massa è legata ad una variazione di energia:
>- Il sole rilascia energia, quindi la sua massa diminuisce.
>- Quando un onda elettromagnetica si avvicina ad un nucleo atomico, può scomparire e creare un elettrone e un positrone.

>Dall'equazione
$$
K=E-E_0
$$
>si può dimostrare che la velocità della luce è irraggiungibile:
>$$
{K=mc^2(\frac{1}{\sqrt{1-\frac{v^2}{c^2}}}-1)}{}{}{}{}{}{}
$$
>Quando $v$ -> $c$, $K$ -> $\infty$, ma come sappiamo dal [[Teorema dell'energia cinetica]], servirebbe un lavoro infinito per un energia cinetica infinita, ma questo è impossible.

>[!Done] Energia di un corpo in movimento
>$$
E^2=p^2c^2+m^2c^4
>$$

# Trasformazioni di Lorenz

