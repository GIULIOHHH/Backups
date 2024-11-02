---
tags: fisica
---
# I Magneti
I magneti sono oggetti capaci di attirare il ferro.
>L'ago di una bussola è un magnete che può ruotare liberamente e si orienta nella direzione nord-sud.

Ogni magnete possiede un polo nord e un polo sud, non è possibile avere un monopolo magnetico.
>Se dividiamo in 2 un magnete ogni metà avrà un polo nord e un polo sud.
Poli simili si respingono, poli opposti si attraggono.
>Come le cariche elettriche.

# Campo magnetico 
Attorno a un magnete esiste un campo magnetico.
Il campo magnetico è un vettore; posto un ago magnetico in un punto:
- la **direzione** è quella lungo la quale si orienta l'ago magnetico.
- Il **verso** è quello indicato dal polo nord dell'ago.
- Il **modulo** è la formula inversa della [[#Forza di Lorentz]].
Si indica con $\overrightarrow B$ e si misura in _Tesla_ $[T]$.
>Si può misurare anche in _Gauss_: $1G=1*10^{-4}\:T$
![[Pasted image 20241010151814.png]]
Il campo magnetico in un area si rappresenta con:
- $\times$ se è entrante
	- guardando il foglio dall'alto vediamo la freccia del vettore.
- $\cdot$ se è uscente
	- guardando il foglio dall'alto vediamo la punta del vettore.
![[Pasted image 20241010152516.png]]
### Linee di forza
Possiamo disegnare le linee di forza di un campo magnetico.
>Si visualizzano spargendo della polvere di ferro.
- Il campo magnetico in un punto è tangente alla linea di forza che passa per quel punto.
- Le linee escono dal polo nord e entrano nel polo sud.
	- Dentro il magnete entrano nel polo sud e escono nel polo nord.
- Le linee sono sempre chiuse (dal polo nord al polo sud)
- è più inteso dove le linee di forza sono piu vicine tra loro.
- è uniforme se le linee sono parallele e con distanze uguali.

![[Pasted image 20241010151857.png]]
# Forza di Lorentz
Se una carica $q$ si muove con una velocità $v$ in un campo magnetico $B$, subisce una forza:
$$
\overrightarrow F=q*\overrightarrow v\; \times \overrightarrow B
$$
oppure:
$$
F=q*v*B*sin(\theta)
$$
>Dove $\theta$ è l'angolo tra $v$ e $B$

>La carica subisce una forza d'intensità proporzionale alla componente [[perpendicolare]] della velocità.

Dato che la forza di Lorentz è sempre [[perpendicolare]] alla velocità (e anche al campo magnetico) non compie lavoro, quindi non ne varia il modulo, ma solo la direzione.
>Perchè $L=F*s*cos(90)=0$

>Invece il campo elettrico aumenta la componente parallela ad esso della velocità, quindi compie un lavoro.

Per stabilire verso e direzione si usa la __Prima regola della mano destra__.
Aprendo pollice, indice e medio in modo tale che tutti e 3 siano [[perpendicolare|perpendicolari]]: 
1. Pollice verso la velocità
2. Indice verso il campo magnetico 
3. Il verso del dito medio sarà quella della carica (positiva).
4. Se la carica è negativa il verso si inverte.
![[Pasted image 20241010162228.png|400]]
## Traiettorie Circolari
Se la velocità è [[perpendicolare]] al campo magnetico, la carica si muove di traiettoria circolare.
![[Pasted image 20241010162217.png|400]]
>Se la carica si trova in basso la forza la spinge verso l'alto, la velocità verso sinistra. Se la carica si trova al lato la forza la spinge verso destra, la velocità verso l'alto.

La forza di Lorentz è sempre diretta verso il centro e si comporta come [[Forza centripeta]]. 
$$
F_c=\frac{mv^2}{r}
$$
Dato che in questo caso $v$ e $B$ sono perpendicolari:
$$
F=q*v*B
$$
quindi uguagliando:
$$
q*B=\frac{m*v}{r}
$$
$$
r=\frac{m*v}{q*B}
$$

Usando le altre formule del [[Moto circolare]] possiamo calcolare anche la [[Frequenza]]:
$$
f=2*\pi*\omega
$$
$$
\omega=\frac{v}{r}
$$
$$
f=2*\pi*\frac{q*B}{m}
$$
### Traiettorie elicoidali
Se la velocità forma un angolo $\theta$ con il campo magnetico la carica si muove di traiettoria elicoidale.
![[Pasted image 20241010155940.png]]
1. La componente [[perpendicolare]] della velocità $v_{\perp}=v*sin (\theta)$ determina il [[Moto circolare]] della forza di Lorentz.
2. La componente parallela della velocità determina un [[Moto Rettilineo Uniforme]].
$$
r=\frac{m*v}{q*B} *sin(\theta)
$$
>[!info] Il raggio è uguale a quello circolare moltiplicato per il seno.

Il passo (spazio tra due eliche) è uguale allo spazio percorso d1alla componente parallela della velocità in un [[Periodo]].

$$
p=v_{//}*T
$$
## Selettore di Velocità
Viene usato misurare la velocità di una particella carica.
è un [[Elettricità#Condensatori Piani|Condensatore]] immerso in un [[#Campo magnetico]], in modo tale che il campo elettrico sia [[perpendicolare]] a quello magnetico.
Le particelle entrano con una velocità [[perpendicolare]] ad entrambi; per uscere dal selettore non devono essere deflesse, quindi le forze dei due campi devono annullarsi. 
Dato che $F_E=E*q$ e $F_B=q*v*B$, si annullano quando:
$$
E*q=q*v*B
$$
$$
v=\frac{E}{B}
$$
>Si seleziona la velocità modificando il modulo dei due campi.
![[Pasted image 20241010162204.png]]

## Spettrometro di Massa 
Usato per determinare la massa.
>Usato per misuare gli _isotopi_ di un elemento (numero diverso di neutroni, resto uguale)

1. Gli [[Atomo|Atomi]] sono prima ionizzati (perdono un elettrone e ottengono [[Elettricità#Carica elettrica|Carica]] $+e$)
2. Una differenza di [[Potenziale Elettrico#Potenziale elettrico|Potenziale]] $V$ gli da una velocità $v$.
3. Gli ioni attraversano un foro e si trovano in un campo magnetico uniforme $B$.
4. Solo gli ioni che si muovono con una traiettoria di raggio $r$ entrano nel rilevatore.
![[Pasted image 20241010162154.png|400]]

Variando $B$, si ottengono cariche di massa:
$$
m=B^2*\frac{q*r^2}{2*V}
$$
>Al posto di $q$ si può trovare anche $e$.
#### Dimostrazione:
Dato che:
$$
V=\frac{U}{q}
$$
la formula inversa è:
$$
U=V*q
$$
Un'altra formula per l'energia è:
$$
U=\frac{1}{2}m*v^2
$$
Uguagliando:
$$
V*q=\frac{1}{2}m*v^2
$$
Quindi la velocità è:
$$
v=\sqrt{\frac{2*V*q}{m}}
$$
La formula del raggio nella [[#Traiettorie Circolari|traiettoria circolare]] è 
$$
r=\frac{m*v}{q*B}
$$
quindi si fà la formula inversa per la velocità 
$$
v=\frac{r*q*B}{m*v}
$$
Si uguaglia questa con quella di prima e si eleva al quadrato.

# Filo percorso da corrente **IMMERSO** In un campo magnetico 
Un filo di lunghezza $L$ percorso da corrente $I$, **IMMERSO** in un [[#Campo magnetico]] $B$ subisce una forza magnetica:
$$
\overrightarrow F= I*\overrightarrow L \times \overrightarrow B
$$
$$
F=I*L*B*sin(\theta)
$$
Dove $\overrightarrow L$ ha come modulo la lunghezza e come verso e direzione quelle della corrente.
#### Dimostrazione dalla [[#Forza di Lorentz]]:
$$
F=q*v*B
$$
Se divido e moltiplico per $\Delta t$:
$$
F=\frac{q}{\Delta t} *(v*\Delta t) *B
$$
Dove ${q}/{\Delta}t$ è [[Circuiti Elettrici#Corrente elettrica|l'intesità di corrente]] e $v*\Delta t$ (per la formula inversa di $v=s/t$) è la lunghezza del filo.
$$
F=I*L*B
$$
![[Pasted image 20241010163751.png|400]]
La direzione e il verso della formula sono determinate dalla **Prima regola della mano destra**, allo stesso modo della [[#Forza di Lorentz]], tranne che invece di puntare verso la velocità il pollice punta verso la direzione della [[Circuiti Elettrici#Corrente elettrica|Corrente Convenzionale]] $I$.
# Spira percorsa da corrente in un campo magnetico 
Una spira rettangolare di lati $w$ e $L$ viene attaccata a un perno libero di ruotare.
Quando attraverso la spira passa corrente, sui due lati verticali agiscono forze magnetiche uguali e opposte ($\overrightarrow F$ e $-\overrightarrow F$), quindi sulla spira agisce una forza totale nulla.
Nonostante questo la spira subisce un [[momento]] torcente che tende a ruotarla in senso orario. 
Il [[momento]] torcente fa comportare la spira come un magnete che ruota per allinearsi con il campo magnetico.
>Quindi il [[momento]] torcente è massimo se la [[normale]] della spira è [[perpendicolare]] al [[#Campo magnetico]].

![[Pasted image 20241010171236.png]]
Il [[momento]] è:
$$
M=F*r*sin(\theta)
$$
In questo caso la distanza è $r=w/2$. 
La forza si ottiene con la [[#Filo percorso da corrente **IMMERSO** In un campo magnetico|formula del filo]].
Il [[momento]] torcente totale $\tau$ è la somma dei momenti su due lati:
$$
\tau=(I*L*B*\frac{w}{2}*sin(\theta))+(I*L*B*\frac{w}{2}*sin(\theta))
$$

$$
\tau=I*L*w*B*sin(\theta)
$$


dato che ($L*w=A$):
>$L$ e $w$ sono i due lati del rettangolo.
$$
\tau=I*A*B*sin(\theta)
$$

>[!info] Questa formula è la stessa di [[#Filo percorso da corrente **IMMERSO** In un campo magnetico|quella del filo]], solo che ha l'Area $A$ invece della lunghezza $L$.

Se il filo della spira è avvolto $N$ volte per formare una bobina, il modulo sarà $N$ volte più grande. ^dd040f
$$
\tau=I*A*B*sin(\theta)*N
$$

>Anche sui lati orizzontali agiscono forze magnetiche, però il [[momento]] torcente è nullo, perchè le forze sono parallele al perno $sin(0)=0$.

Possiamo utilizzare anche il _momento magnetico_ $\mu_m$ nella formula:
$$
\overrightarrow \mu_m=I*\overrightarrow A
$$
$$
\overrightarrow \tau=\overrightarrow\mu_{m}\times \overrightarrow B
$$
Il _momento magnetico_ è un vettore:
- Ha come direzione quella del [[Vettore Area]]
- Il verso è dato dalla [[#Seconda regola della mano destra]].
# **CAMPO MAGNETICO** di un Filo percorso da corrente (non immerso)
Un filo percorso da corrente genera un campo magnetico concentrico.
$$
B=\frac{\mu_0}{2*\pi}*\frac{I}{r}
$$
Dove $I$ è l'intensità della corrente, $r$ è la distanza dal filo e $\mu_0$ è la **permeabilità magnetica nel vuoto**.
$$
\mu_0=4*\pi*10^{-7}
$$
>[!info] Possiamo scrivere questa formula come:
>$$
>B=2*10^{-7}*\frac{I}{r}
>$$

Il verso e la direzione sono dati dalla **seconda regola della mano destra**.
>Si dice anche legge di Biot-Savart.
### Seconda regola della mano destra
1. Si punta il pollice nel verso della [[Circuiti Elettrici#Corrente elettrica|Corrente Convenzionale]] $\overrightarrow I$
2. Le altre dita si chiudono nel verso del campo magnetico $\overrightarrow B$.
![[Pasted image 20241010173816.png]]
## Forze tra correnti
Il campo magnetico [[#**CAMPO MAGNETICO** di un Filo percorso da corrente (non immerso)|generato da una corrente]] può esercitare [[#Filo percorso da corrente **IMMERSO** In un campo magnetico|una forza su altre correnti]].

Abbiamo 2 fili paralleli, infinitamente lunghi, dove scorrono correnti di modulo uguale.
![[Pasted image 20241010174711.png]]
Una sezione di lunghezza $L$ del filo 2 subirà una forza $F_{12}$ dovuta al campo magnetico $B_1$ uguale a:
$$
F_{12}=I_2*B_1*L
$$
>Dove l'angolo è di $90$ gradi perchè $B_1$ è [[perpendicolare]] sia al filo 1 che al 2.

$B_1$ si può calcolare con la legge di  [[#**CAMPO MAGNETICO** di un Filo percorso da corrente (non immerso)|Biot-savart]]:
$$
B_1=\frac{\mu_0}{2*\pi}*\frac{I_1}{d}
$$
>$d$ è la distanza tra i fili $1$ e $2$.

quindi sostituendo:
$$
F_{12}=\frac{\mu_0}{2*\pi}*\frac{I_1*I_2}{d}*L
$$
>[!info] Anche questa formula si può scrivere come $$2*10^{-7}*\frac{I_1*I_2}{d}*L $$
>Ovvero il prodotto delle due correnti e della sezione considerata, fratto la distanza tra i due fili.


Si può dimostrare che $F_{12}=-F_{21}$, quindi le forze sono uguali e opposte.

- Fili percorsi da correnti con lo stesso verso si attraggono. 
- Fili percorsi da correnti con verso opposto si oppongono.
# Campo magnetico di spire e bobine
Al centro di una spira di raggio $r$ il campo magnetico è [[perpendicolare]] al [[piano]] della spira e ha intensità:
$$
B=\frac{\mu_0}{2}*\frac{I}{r}
$$
>[!info] Questa formula è la stessa della [[#**CAMPO MAGNETICO** di un Filo percorso da corrente (non immerso)|Legge di Biot-Savart]], solo che non è divisa per $\pi$.


![[#^dd040f]]
$$
B=N*\frac{\mu_0*I}{2*r}
$$
Per trovare direzione e verso si usa la [[#Seconda regola della mano destra]].
![[Pasted image 20241010175941.png]]
La spira si comporta come un magnete, con un polo nord su un lato e un polo sud su un altro. 
>La direzione in cui si chiudono le dita è il polo nord.
![[Pasted image 20241010180610.png]]
# Solenoide
Il solenoide è un avvolgimento di filo a forma elicoidale.

Per un solenoide di lunghezza $L$ e $N$ avvolgimenti, **Quando il solenoide è molto più lungo rispetto al diametro**
- Il campo magnetico all'esterno del solenoide è praticamente nullo.
- Il campo magnetico all'interno del solenoide (lontano dalle estremità) è uniforme e parallelo all'asse del solenoide, con intensità:
$$
B=\mu_0*\frac{N}{L}*I
$$
>è il rapporto tra gli avvolgimenti e la lunghezza, moltiplicato per l'intesità e la costante.
![[Pasted image 20241010180730.png|400]]
# Teorema di Gauss 
>Dato che il campo magnetico è un campo vettoriale si può calcolare il suo flusso attraverso una superficie.

$$
\Phi(\overrightarrow B)=\overrightarrow B\cdot \overrightarrow A
$$
$$
\Phi( B)=B*A*cos(\theta)
$$
Si misura in __Weber__ $[Wb]$ 

Data una superficie chiusa o _superficie gaussiana_, possiamo dividerla in tanti regioni tali che:
- Ogni regione è piana 
- Il flusso in ogni regione è uniforme.
$$
\Phi(\overrightarrow B)=\sum\limits_k\overrightarrow B_k\cdot \overrightarrow A_k
$$
**Il flusso del campo magnetico attraverso una superficie chiusa _(o gaussiana)_ è sempre nullo.**
>Per il campo elettrico il flusso era la carica totale dentro la superficie (quindi potevano esserci più cariche positive che negative e viceversa). Il numero di linee entranti in una superficie chiusa poteva essere diverso dal numero di linee uscenti.

Questo è perchè non esistono monopoli magnetici, quindi una superficie racchiude sempre un numero uguale di poli nord e poli sud.
# Circuitazione
Data una curva chiusa, la dividiamo in sezioni tali che:
- Ogni sezione è rettilinea, è può essere rappresenta da un vettore spostamento $\Delta \overrightarrow  l$ tra i suoi estremi.
- In ogni sezione il campo magnetico è costante e forma un angolo $\theta$ con  $\Delta \overrightarrow  l$ .
![[Pasted image 20241010182111.png|500]]
La circuitazione è quindi 
$$
 \Gamma_\gamma (\overrightarrow B)=\sum_{k} \overrightarrow B \cdot \overrightarrow \Delta l
$$
$$
 \Gamma_\gamma ( B)=\sum_{k}  B* \Delta l*cos(\theta)
$$
## Teorema di Ampère
Una corrente si dice concatenata a una curva quando attraversa ogni superficie che ha come contorno la curva.
![[Pasted image 20241010182600.png|500]]
Per i [[#Campo magnetico|Campi Magnetici]] __stazionari__:
$$
 \Gamma_\gamma ( B)=\mu_0*\sum_{k} I_k
$$
dove le correnti concatenate $I_k$ sono prese con il segno positivo se generano un campo magnetico con lo stesso verso di percorrenza del circuito, altrimenti sono prese con il segno negativo.

>[!info]
>- Se la corrente scorre verso l'alto il filo è concorde con la percorrenza antioraria
>- Se la corrente scorre verso il basso il filo è concorde con la precorrenza oraria.


