# Condizioni Statiche
In condizioni statiche (quando i campi non dipendono dal tempo), [[Magneti#Campo magnetico|Campo magnetico]] e [[Elettricità#Campo elettrico|Campo elettrico]] sono indipendenti. 
1. Il [[Elettricità#Flusso elettrico|Flusso di un Campo Elettrico]] è:
$$
\Phi_S(\overrightarrow E) =\frac{Q_T}{ε_0}
$$
Dove $S$ è una superficie chiusa, $Q_T$ è la somma delle cariche nella superficie e $ε_0=8.85*10^{-12}.$
2. La [[Potenziale Elettrico|Circuitazione di un Campo Elettrico]] è:
$$
\Gamma_\gamma(\overrightarrow E)=0
$$
Dove $\gamma$ è una curva chiusa. Il valore è $0$ perchè il [[Elettricità#Campo elettrico|Campo elettrico]] è un campo [[Conservativo]].
3. Il [[Magneti#Teorema di Gauss|Flusso di un Campo Magnetico]] Magnetico è:
$$
\Phi_S(\overrightarrow B) =0
$$
Questo è perchè non esiste un monopolo magnetico. (Se dentro una superficie esiste una carica positiva ne deve esistere anche una uguale e negativa.)
4. La [[Magneti#Circuitazione|Circuitazione di un Campo Magnetico]] è:
$$
\Gamma_\gamma(\overrightarrow B)=\mu_0*\sum_{k} I_k
$$
Dove $\mu_0=4*\pi*10^{-7}$ e $I_k$ sono le correnti concatenate a $\gamma$.

>Le prime due formule rappresentano il campo elettrico a partire dalle sue sorgenti: __cariche elettriche__.
>Le ultime due il campo magnetico a partire dalle sue sorgenti: **correnti elettriche.**

# Campo Magnetico Variabile
>In condizioni dinamiche, le variazioni di flusso sono sorgenti di campo.

[[Induzione Elettromagnetica#Legge di Faraday-Neumann-Lenz|La variazione del Campo Magnetico (nel tempo) genera un Campo Elettrico Indotto]]:
$$
\mathcal{E}=-\frac{\Delta \Phi(\overrightarrow B)}{\Delta t}
$$
La [[Potenziale Elettrico|FEM]] è:
$$
\mathcal{E}=\frac{L}{q}
$$
Il [[Lavoro]] è:
$$
\overrightarrow{L}=\overrightarrow{F}*\overrightarrow{s}
$$
[[Potenziale Elettrico#^b18d97|Se spostiamo la carica lungo una curva]] $\gamma$, divisa in tratti $\Delta \overrightarrow l$, così piccoli da essere rettilinei e dove $\overrightarrow F$ è uniforme:

$$
L=\sum\limits_{k} \overrightarrow F_{k} * \Delta \overrightarrow l_{k} 
$$
Quindi 
$$
\mathcal{E}=\sum\limits_{k} \frac{\overrightarrow F_{k}}{q} * \Delta \overrightarrow l_{k} 
$$
Il [[Elettricità#Campo elettrico|Campo elettrico]] è:
$$
\overrightarrow{E}=\frac{\overrightarrow{F}}{q}
$$
Quindi sostituendo:
$$
\mathcal{E}=\sum\limits_{k} \overrightarrow E_{k} * \Delta \overrightarrow l_{k} 
$$
Inoltre la [[Potenziale Elettrico|Circuitazione del Campo Elettrico]] è 
$$
\Gamma_\gamma(\overrightarrow E)=\sum\limits_{k} \overrightarrow{E}_k*\overrightarrow{\Delta l_k} 
$$
Quindi
$$
\Gamma_\gamma(\overrightarrow E)=-\frac{\Delta \Phi(\overrightarrow B)}{\Delta t}
$$
>Questo è il valore medio. Facendo le derivate otteniamo il valore istantaneo.

La circuitazione del [[Induzione Elettromagnetica#Induzione|Campo Elettrico Indotto]] non è $0$, quindi il [[Induzione Elettromagnetica#Induzione|Campo Elettrico Indotto]] non è [[Conservativo]].

[[Induzione Elettromagnetica#Legge di Faraday-Neumann-Lenz|La Legge di Faraday-Neumann-Lenz]] è una generalizzazione della [[Potenziale Elettrico|Circuitazione di un Campo Elettrico]]:
$\Gamma_\gamma(\overrightarrow E)=0$ quando il campo magnetico rimane costante ($\Delta \Phi(\overrightarrow B)=0$).

## Campo Elettrico in un [[Magneti#Solenoide|Solenoide]]
*Abbiamo un [[Magneti#Solenoide|Solenoide]] di raggio $R$. Qual'è il [[Induzione Elettromagnetica#Induzione|Campo Elettrico Indotto]] in un punto a distanza $r$ dall'asse del  [[Magneti#Solenoide|Solenoide]]?*

>Le linee di campo elettrico saranno circonferenze concentriche all'asse del solenoide *(col verso dato dalla [[Induzione Elettromagnetica#Legge di Lenz|Legge di Lenz]]),* quindi consideriamo una linea circolare in modo tale che il modulo del campo sia constante lungo essa.

Partendo da
$\Gamma_\gamma(\overrightarrow E)=-\frac{\Delta \Phi(\overrightarrow B)}{\Delta t}$

La [[Potenziale Elettrico|Circuitazione del Campo Elettrico]] è
$$
\Gamma_\gamma(\overrightarrow E)=\overrightarrow{E}*\sum\limits_{k}\overrightarrow{\Delta l_k} 
$$
Inoltre $\sum\limits_{k}\overrightarrow{\Delta l_k}$ è il perimetro della curva $\gamma$, quindi
$$
\Gamma_\gamma(\overrightarrow E)=\overrightarrow{E}*2*\pi*r
$$

---
Il [[Magneti#Teorema di Gauss|Flusso di un Campo Magnetico]] all'interno del [[Magneti#Solenoide|Solenoide]] è:
$$
\Delta \Phi( B)=\Delta  B* A
$$
Quindi $A$ è l'area del solenoide:
$$
A=\pi*R^2
$$
Unendo:
$$
{E}*2*\pi*r=\frac{\pi*R^2*\Delta B}{\Delta t}
$$
Quindi
$${E}*2r=\frac{R^2*\Delta B}{\Delta t}$$

![[Pasted image 20250122185151.png|400]]
#### 1. **Se $r>R$ si lascia così**
>[!example] Perchè stiamo cercando il valore del flusso in un punto esterno, quindi dobbiamo considerare tutto il solenoide.
>*(Il campo magnetico è non nullo solo nella parte della curva che contiene il solenoide.)*
#### 2. **Se $r<R$ si semplifica**
$$
{E}*2r=\frac{r^2*\Delta B}{\Delta t}
$$
$$
E=\frac{r*\Delta B}{2*\Delta t}
$$

>[!example] Perchè stiamo cercando il valore del flusso in un punto interno, quindi non ci interessa il resto del solenoide.
>*(Ci interessa la parte di campo magnetico in cui è immersa tutta la curva)*
# Campo Elettrico Variabile/Teorema Di Ampère
Maxwell generalizza il [[Magneti#Teorema di Ampère|Teorema di Ampère]] aggiungendo una **corrente di spostamento**:
$$
I_s=ε_0*\frac{\Delta \Phi (\overrightarrow E)}{\Delta t}
$$
Dove il [[Elettricità#Flusso elettrico|Flusso del Campo Elettrico]] è calcolato attraverso una superficie avente come bordo la curva $\gamma$.
>La corrente di spostamento **non** è una corrente di cariche elettriche.

Quindi il teorema diventa:
$$
\Gamma_\gamma(\overrightarrow B)= \mu_{0}*(\sum\limits_{j} *I_j+ε_0*\frac{\Delta \Phi (\overrightarrow E)}{\Delta t})
$$
## Dimostrazione della corrente di spostamento
Consideriamo un [[Circuito RC]] in fase di carica del [[Elettricità#Condensatori Piani|Condensatore]].
Studiamo il [[Magneti#Teorema di Ampère|Teorema di Ampère]] su una circonferenza $\gamma$ centrata sul filo e perpendicolare a esso.

![[Pasted image 20250122190823.png]]
Nel primo e nel terzo caso $\Gamma_\gamma ( B)=\mu_0*I$
>Dove $I$ è la corrente che passa per il filo.

Ma nel secondo caso, $I$ non è concatenato a $\gamma$, quindi la circuitazione dovrebbe essere nulla *(e quindi anche il campo magnetico)*.
Ma misurando $B$, non è nullo e ha una circuitazione pari al primo/terzo caso.

Quindi deve esistere una corrente legata al campo elettrico tra le armature del [[Elettricità#Condensatori Piani|Condensatore]].
![[Pasted image 20250122190829.png]]
Prendiamo una gaussiana:
All'esterno del [[Elettricità#Condensatori Piani|Condensatore]], il [[Elettricità#Campo elettrico|Campo Elettrico]] è nullo, all'interno è parallelo alle armature e uniforme.
Il [[Elettricità#Flusso elettrico|Flusso del Campo Elettrico]] è:
$$
\Phi_S(\overrightarrow E) =\frac{Q}{ε_0}
$$
Dove $Q$ è la carica sull'armatura. 
Dato che il [[Elettricità#Condensatori Piani|Condensatore]] è in carica, $Q$ aumenta grazie alla corrente del circuito *(e anche perchè la carica si conserva)* $Q_f=Q_i+I*\Delta t$.
Quindi:
$$
\Delta \Phi_S(\overrightarrow E) =\frac{Q+I*\Delta t}{ε_0}-\frac{Q}{ε_0}
$$
$$
\Delta \Phi_S(\overrightarrow E) =\frac{I*\Delta t}{ε_0}
$$
Quindi la formula inversa è quella della **corrente di spostamento**:
$$
I=ε_0*\frac{\Delta \Phi (\overrightarrow E)}{\Delta t}
$$

La corrente di spostamento è uguale alla corrente di conduzione che passa per il circuito. 

La circuitazione del campo magnetico è indipendente dal tipo di corrente *(o di conduzione o di spostamento)* concatenata a $\gamma$.

>Quali sono le equazioni di Maxwell?
>$\Phi (E)=Q/ε_0$
>$\Gamma(E)=-{\Delta \Phi(B)}/{\Delta t}$
>$\Phi (B)=0$
>$\Gamma(B)= \mu_{0}*(\sum\limits_{j} *I_j+ε_0*{\Delta \Phi (\overrightarrow E)}/{\Delta t})$

# Onde Elettromagnetiche

[[Magneti#Campo magnetico|Campo magnetico]] e [[Elettricità#Campo elettrico|Campo elettrico]] sono aspetti diversi del **Campo Elettromagnetico**.

- Un [[#Campo Elettrico Variabile/Teorema Di Ampère|Campo Elettrico Variabile]] genera un [[#Campo Magnetico Variabile|Campo Magnetico Variabile]].
- Un [[#Campo Magnetico Variabile|Campo Magnetico Variabile]] genera un [[#Campo Elettrico Variabile/Teorema Di Ampère|Campo Elettrico Variabile]].
- E così via.

L'[[oscillazione]] di un [[Elettricità#Campo elettrico|Campo elettrico]] in un punto porta all'[[oscillazione]] del [[Magneti#Campo magnetico|Campo magnetico]] in punti vicini e così via. 
Il fenomeno si propaga tramite **Onda Elettromagnetica.**
Le [[Onda|Onde meccaniche]] portano all'oscillazione di un mezzo materiale *(quindi non si propagano nel vuoto),* mentre nelle **Onde Elettromagnetiche** oscillano [[Magneti#Campo magnetico|Campo magnetico]] e [[Elettricità#Campo elettrico|Campo elettrico]].

![[Luce#^7f21aa]]

Perchè la velocità è:
$$
c=\frac{1}{\sqrt{ε_0*\mu_0}}
$$
La [[Luce]] è un'onda elettromagnetica.

## Campi Vicini
Abbiamo un alternatore *(Di periodo $T$)* connesso a due fili metallici in modo tale da formare un [[antenna]].

- L'alternatore porta ad un accumulo periodico di cariche agli estremi:
- Queste cariche generano un campo elettrico variabile che si propaga in tutte le dimensioni.
- Il movimento di cariche forma una corrente che forma un [[Magneti#Campo magnetico|Campo magnetico]] variabile che si propaga in tutte le dimensioni.
- [[Magneti#Campo magnetico|Campo magnetico]] e [[Elettricità#Campo elettrico|Campo elettrico]] sono perpendicolari tra loro e con la direzione di propagazione.
	- Quindi le onde elettromagnetiche sono [[Onda#Trasversali|Onde Trasversali]].
- In ogni punto i due campi oscillano in fase con la stessa frequenza dell'alternatore.
>Il verso del campo magnetico si calcola con la [[Magneti#Seconda regola della mano destra|Seconda regola della mano destra]].
### Esempio (semplificato in solo una direzione!)

---
In $t=0$ non c'è carica agli estremi e non c'è campo in $P$.
![[Pasted image 20250123172539.png|200]]

---
In $t=T/4$ le estremità sono cariche (e raggiungono il loro valore massimo).
>Quella superiore positivamente e quella inferiore negativamente. 

Il campo in $P$ *(freccia rossa)* raggiunge il valore massimo.
>Ed è diretto verso il basso.

Il [[Elettricità#Campo elettrico|Campo elettrico]] creato negli istanti precedenti *(freccia nera)*, si propaga verso destra col passare del tempo.
>**Non cambia valore!** Si sposta verso destra.
![[Pasted image 20250123172640.png|200]]
---
In $t=T/2$ le estremità non sono più cariche *(perchè la polarità si sta invertendo)* e il campo in $P$ è nullo *(perchè il verso si sta invertendo)*.

![[Pasted image 20250123173106.png|200]]

---
In $t=\frac{3}{4}* T$, le estremità sono cariche e la polarità è opposta a $t=T/4$
>Quella inferiore positivamente e quella superiore negativamente. 

Stessa cosa per $P$.
![[Pasted image 20250123173229.png|200]]


# Campi Vicini VS Campi Lontani
- I campi generati a pochi metri dall'antenna vengono detti **Campi Vicini.** 
	- L'ampiezza decresce rapidamente più ci si allontana.
		- Perchè i campi dipendono dall'energia dell'antenna. 
		- I campi si propagano in tutte le direzioni.
- I **Campi Lontani/DI Radiazione** sono campi a grandi distanze.
	- L'ampiezza diminuisce molto lentamente.
		- Si mantengono perchè $\overrightarrow E$ e $\overrightarrow B$ si autosostengono.
		- I campi formano un'onda elettromagnetica.

# Spettro Elettromagnetico

La serie ordinata *(ordered set!)* di frequenze/lunghezze d'onda è lo Spettro Elettromagnetico.
Lo spettro è diviso in varie regioni, anche se il loro confine non è netto e spesso si sovrappongono.
![[Pasted image 20250123180511.png]]
## Onde Radio
>- $\lambda$ tra $\approx 10^4$ *(decine di $km$)* e $\approx 3*10^{-2}$ *($30cm$)*
>- Utilizzate per le trasmissioni radio/tv. 
>	- Le onde AM hanno una maggiore [[Diffrazione]] delle onde FM, quindi hanno una maggiore capacità di aggirare ostacoli.
## Microonde
>- $\lambda$ fino a  $\approx 10^{-4}$  *( $1mm$)*
>- Usate nei telefoni, nel micronde e nei radar. 
>	- Il micronde ruota le molecole d'acqua nei cibi, donandole energia e riscaldando il cibo.
>	- I radar misurano il tempo in cui l'onda riflessa da oggetti metallici ritorna all'origine per calcolare la distanza. *(kinda echolocation)*
## Infrarosso
>- $\lambda$ fino a  $\approx 750*10^{-9}$  *( $750nm$)*
>- Generate dalla vibrazione/rotazione delle molecole. 
>- Se assorbite dalla pelle provocano calore.
>	- è possibile misurare la temperatura misurando la quantità di raggi infrarossi. 

## **Luce Visibile**
- $\lambda$ da a  $\approx 750*10^{-9}$  a $\approx 380*10^{-9}$   *(da $750nm$ a $350 nm$)*
- Vanno dal rosso al viola. 
## Ultraviolette
>- $\lambda$ fino a  $\approx 10*10^{-9}$  *( $10nm$)*
>- Penetrano gli strati superficiali della pelle. Attivano reazioni chimiche benefiche (Vitamina D e melanina) ma esposizione eccessiva provoca tumori.
>- Il sole emette UV-A, UV-B e UV-C. L'atmosfera assorbe tutta la banda UV-B, quindi basta proteggersi per l'UV-A.

## Raggi X
>- $\lambda$ fino a  $\approx 10^{-12}$  *( $0.001nm$)*
>- Emesse dalle violente decelerazioni di elettroni in metalli pesanti. 
>- Usate in medicina perchè attraversano i tessuti molli ma sono assorbite dalle ossa.

## Raggi gamma
>- $\lambda$ minore dei Raggi X.
>- Emessi dai decadimenti nucleari.
>- Uccidono i batteri con cui interagiscono. 
>	- Usate per la radioterapia dei tumori e per la sterilizzazione di strumenti chirurgici.  

# Energia

### [[Energia Di Un Condensatore]]

### [[Induzione Elettromagnetica#Dimostrazione|Energia Di Un Induttore]] 

## Valore istantaneo 


Le onde elettromagnetiche trasportano energia.

La densità di energia di un onda elettromagnetica nel vuoto è la somma tra quella elettrica e quella magnetica.

$$
u=\frac{1}{2}u_E+\frac{1}{2}u_B
$$
$$
u=\frac{1}{2}ε_0*E^2\;+\;\frac{1}{2*\mu_0}*B^2
$$
Campo elettrico e campo magnetico trasportano la stessa quantità di energia:
$$
\frac{1}{2}ε_0*E^2\;=\;\frac{1}{2*\mu_0}*B^2
$$

>[!info] Quindi raddoppiando/sostituendo una delle due ($u_e$ o $u_b$) possiamo ottenere $u$. 
>$u=B^2/\mu_0$
>$u=E^2*ε_0$

Se facciamo la formula inversa
$$
E^2=\frac{1}{ε_0*\mu_0}*B^2
$$
Noi sappiamo che
$$
c=\frac{1}{\sqrt{\mu_0*ε_0}}
$$
Quindi sostituendo
$$
E^2=c^2*B^2
$$
$$
E=c*B
$$
---
[[Onda#Formula Matematica del movimento delle particelle|Il valore istantaneo di E/B si calcola così!]]
## Valore medio
Per calcolare il valore medio bisogna usare i valori medi di $E^2$ e $B^2$. Sostituiamo $E_{eff}$ e $B_{eff}$:
$$
E_{eff}=\frac{E}{\sqrt 2}
$$
## Irradiamento
L'energia è determinata dall'irradiamento $S$:
Potenza di un onda fratto la superficie ch
e attraversa perpendicolarmente.
$$
S=\frac{P}{A}
$$
>Se la luce viene emessa in maniera uniforme l'area è quella di una sfera $A=4*\pi*r^2$
Inoltre
$$
P=\frac{U}{t}
$$
quindi 
$$
S=\frac{U}{t*A}
$$
Inoltre, l'energia $U$ è la densità di energia $u$ per il volume $Vol$:
$U=u*Vol$
In tempo $t$ la luce attraversa $c*t$ spazio, quindi moltiplicandolo per L'area $A$ che attraversa otteniamo il volume.
![[Pasted image 20250128171600.png|400]]
$$
U=u*c*t*A
$$
Quindi sostituendo
$$
S=\frac{u*c*t*A}{t*A}
$$
semplificando:
$$
S=u*c
$$
>Possiamo sostituire a $u$ le [[#Valore istantaneo|formule per il valore istantaneo della densità di energia.]]
>$S=c*E^2*ε_0$
>$S=c*B^2/\mu_0$
>In questo modo otteniamo i valori istantanei.
>Per quelli medi usiamo I [[#Valore medio|Valori efficaci]].


# Polarizzazione
Un'[[Onda]] è **polarizzata linearmente** se oscilla sempre nella **direzione di polarizzazione**.
Nel caso della [[Luce]] la **direzione di polarizzazione** diventa quella con cui oscilla il [[Elettricità#Campo elettrico|Campo elettrico]].
![[Pasted image 20250515210859.png]]
La [[Luce]] non polarizzata è formata da più [[Onda|Onde]] **polarizzate**.
>Sono impulsi di [[#Onde Elettromagnetiche]] emesse da atomi diversi. 
 
>Nelle [[Onda|Onde]] longitudinali il concetto di polarizzazione non ha senso, perchè la direzione di propagazione è la direzione di oscillazione.

>Un onda polarizzata può attraversare una fenditura parallela, ma non una perpendicolare.
>![[Pasted image 20250515211036.png]]

I **Polarizzatori** sono capaci di polarizzare la luce. 
Funzionano grazie a materiali chiamati polaroid.
>[!done] Legge
>L'[[#Irradiamento]] che esce da un **Polarizzatore** è sempre metà di quello iniziale.

Il polarizzatore permette solo il passaggio della luce parallela all'**Asse di Trasmissione**.
In qualsiasi direzione, esiste sia una componente parallela che una componente perpendicolare del [[Elettricità#Campo elettrico|Campo elettrico]].
Dato che la luce non polarizzata è uniforme, le due componenti sono uguali.
>Quindi permettendo il passaggio solo della componente parallela si dimezza l'[[#Irradiamento]].

![[Pasted image 20250515211855.png]]
# Legge di Malus
Possiamo usare un altro **polarizzatore** detto **analizzatore** per ruotare la luce e modificarne l'intensità.
$\alpha$ è l'angolo tra l'asse del **polarizzatore** e l'asse dell'**analizzatore**.
Passa dall'**analizzatore** la componente della luce parallela ad $\alpha$.

>- Il campo elettrico che arriva all'**analizzatore** è $E$.
>- Il campo elettrico che esce dall'**analizzatore** è $E*cos(\alpha)$.
>- Dato che $S=c*E^2*ε_0$:

>[!done] Legge di Malus
>$$
\overline{S}=\overline{S_0}*cos^2(\alpha)$$
>- $\overline{S}$ è l'[[#Irradiamento]] medio che esce dall'analizzatore.
>- $\overline{S_0}$ è l'[[#Irradiamento]] medio che entra nell'analizzatore.
>![[Pasted image 20250515211905.png]]

>Se $\alpha=90°$, non passa luce.