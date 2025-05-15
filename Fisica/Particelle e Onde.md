---
tags:
  - fisica
---
Una **Particella** è un corpo a cui possiamo descrivere una posizione in ogni momento.
![[Onda#^982138]]

>- Il modello tradizionale dell'[[Atomo]] è formato da [[Elettricità#Atomo|particelle cariche]].
>	- Ci sono casi dove gli elettroni si comportano come [[Onda]]. Si ha l'[[Fenomeni ondulatori#Interferenza|Interferenza]] tra [[Elettricità#Carica elettrica|Elettroni]].
>-Per l'[[Luce#Interferenza nella luce.|Esperimento di Young]] consideriamo la [[Luce]] come un [[Onda]].
	- Ci sono [[#Corpo Nero|casi]] dove la [[Luce]] si comporta come insieme di **Particelle**.

Secondo il **Principio di Complementarietà** di *Bohr*:
**Sia la radiazione che le particelle dimostrano proprietà [[Onda|Ondulatorie]] o Corpuscolari in base all'apparato sperimentale con cui interagiscono.**

# Corpo Nero
Il corpo nero è un corpo ideale capace di assorbire ed emettere (se riscaldato) tutte le frequenze elettromagnetiche.

>Si ottiene con una cavità avente le pareti a temperatura uniforme e le emissioni si misurano tramite un foro.

A bassa temperatura la luce è infrarossa. Ad alte temperature la luce è nello spettro del visibile (per questo si illuminano.)

Misurando l’intensità della radiazione emessa per ogni lunghezza d'onda si ottiene **Distribuzione di Energia della radiazione del Corpo Nero**, che dipende solo dalla temperatura delle pareti, non dal materiale usato per il corpo nero.

![[Pasted image 20250513220851.png]]
## Legge di Stefan-Boltzmann
All'aumentare della temperatura, aumenta l'area sottesa, che è proporzionale all'energia emessa.

>[!done] Formula
>L'energia irradiata in $1s$ da $1m^2$ di un corpo a [[Temperatura#Scale termometriche|Temperatura Assoluta]] $T$ è:
>$$E=\sigma*T^4
>$$
>Dove $\sigma$ è la costante di Stefan-Boltzmann.
>$$\sigma=5.67*10^{-8}$$

## Fisica classica
Secondo la fisica classica, all'aumentare della frequenza considerata, dovrebbe aumentare l'energia emessa. 
>Se nella **Distribuzione di Energia** la frequenza tende all'infinito, l'energia emessa tende all'infinito.

La stessa cosa per una diminuzione della lunghezza d'onda.
>lunghezza d'onda e frequenza sono inversamente proporzionali ($v=\lambda*f$)

Ma questo violerebbe le leggi della conservazione dell'energia.
>Energia infinita da un corpo finito. (_catastrofe ultravioletta_)

Sperimentalmente questo non succede.
>Diminuendo la lunghezza d'onda (o aumentando la frequenza), l'energia raggiunge un picco e poi tende a $0$.
## Legge di Spostamento di Wien

All'aumentare della temperatura, la lunghezza d'[[Onda]] $\lambda_{max}$ per cui si ha il massimo valore di energia si sposta verso sinistra (lunghezza minore).

>[!done] Formula
>$$
\lambda_{max}*T=2.90*10^{-3}
$$


![[Pasted image 20250513221003.png]]


## Planck
Descrive gli atomi del corpo nero come oscillatori armonici (possono ricevere e donare energia).
>Nei suoi calcoli compariva una quantità con lettera $h$.
>Nella fisica classica $h$ veniva eliminata dai calcoli perchè infinitamente piccola.
>Planck si accorge che assegnandogli un valore piccolo ma diverso da $0$, si potevano descrivere i risultati sperimentali.

Ipotizza che l'energia di un oscillatore armonico può assumere soltanto i valori discreti:
$$
E=n*h*f
$$
Dove $n$ è un numero e $f$ è la frequenza.
>La materia non può scambiarsi energia se sotto una soglia $h*f$.

$h$ è la costante di Planck.
$$
h=6.62*10^{-34} \;\;[J*s]
$$

A frequenze elevate la soglia $h*f$ è molto maggiore dell'energia termica disponibile, quindi gli oscillatori non vengono attivati e l'energia totale rimane finita.

# Effetto Fotoelettrico
>Viene scoperto da Hertz.

1. In un tubo sottovuoto è tenuta una superficie metallica che viene colpita dalla [[Luce]].
2. Se la [[Frequenza]] della [[Luce]] supera una **frequenza minima** $f_0$, il metallo emette elettroni (chiamati **fotoelettroni**).
3. I **fotoelettroni** vengono raccolti da un **collettore** (diodo positivo) e producono una corrente misurabile da un [[Circuiti Elettrici|Amperometro]].
![[Pasted image 20250508143119.png|400]]

4. Possiamo misurare l'**energia massima degli elettroni** $K_{max}$ tramite un Potenziale $V$ di segno opposto. 
5. Il valore minimo $V_0$ che ferma gli elettroni è detto **potenziale d'arresto**.
6. Dato che $V=-L/q$, viene compiuto un lavoro che spinge indietro gli elettroni.
7. L'energia massima degli elettroni è numericamente uguale al lavoro.
8. Se vengono emessi elettroni, $K_{max}$ cresce con la [[Frequenza]].
	1. Tenendo costante la [[Frequenza]], la [[Induzione Elettromagnetica#Corrente Alternata|Corrente]] cresce con l'[[Equazioni Di Maxwell#Irradiamento|Irradiamento]]
![[Pasted image 20250508144927.png|300]]
## Interpretazione
La luce colpisce gli elettroni trasferendogli energia.
Il lavoro minimo per far fuggire l'elettrone dall'attrazione del reticolo metallico è detto **lavoro di estrazione** $W_0$.
### Difficoltà del modello ondulatorio
- La luce è un flusso continuo di energia, quindi a un certo punto il lavoro compiuto su un elettrone dovrebbe superare $W_0$, indipendentemente dalla [[Frequenza]].
 - L'energia trasportata dalla luce dipende dall'[[Equazioni Di Maxwell#Irradiamento|Irradiamento]]. Perchè è la [[Frequenza]] a determinare se i **fotoelettroni** riescono a fuggire? 
## Fotoni

>[!Done] Legge
>*Einstein* ipotizza che la luce di [[Frequenza]] $f$ è formata da un insieme di particelle chiamate fotoni, con energia:
>$$E=h*f\;\;\;\;\;\;\;\;\;[J]$$dove $h$ è la costante di Planck.

>La luce non è distribuita in modo continuo, ma formata da un insieme di *quanti*.

Quando aumenta l'[[Equazioni Di Maxwell#Irradiamento|Irradiamento]] (intensità della luce), aumenta il numero di fotoni, ma non la loro energia individuale. 
Quando un individuale fotone colpisce un elettrone gli cede energia. Se l'energia è superiore a $W_0$ può resistere all'attrazione del metallo. (altrimenti rimane dov'è).
Quindi l'energia massima degli elettroni è uguale a:
$$
K_{max}=h*f-W_0
$$
>L'energia data dai fotoni meno l'energia necessaria all'estrazione.
Quando la frequenza della [[Luce]] è $f_0$, $K_{max}=0$.
>Dato che il lavoro della luce è uguale all'energia necessaria per estrarli, non hanno energia in più.
Quindi
$$
h*f_0=W_0
$$
>Se $f<f_0$, $K_{max}$ è negativa.

L'intensità di [[Induzione Elettromagnetica#Corrente Alternata|Corrente]] è proporzionale all'[[Equazioni Di Maxwell#Irradiamento|Irradiamento]], perchè più fotoni emettono più elettroni che aumentano la [[Induzione Elettromagnetica#Corrente Alternata|Corrente]].


# Effetto Compton




Un fotone diffuso ha una lunghezza d'onda maggiore e un'energia minore del fotone incidente.


La variazione della lunghezza d'onda del fotone incidente è
$$
\Delta \lambda=\frac{h}{mc}*(1-cos({\alpha)})
$$

