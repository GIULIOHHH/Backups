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
Dove $\gamma$ è una curva chiusa. Il valore è $0$ perchè il  [[Elettricità#Campo elettrico|Campo elettrico]] è un campo [[Conservativo]].
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

La circuitazione del [[Induzione Elettromagnetica#Induzione|Campo Elettrico Indotto]] non è $0$, quindi il  [[Induzione Elettromagnetica#Induzione|Campo Elettrico Indotto]] non è [[Conservativo]].

[[Induzione Elettromagnetica#Legge di Faraday-Neumann-Lenz|La Legge di Faraday-Neumann-Lenz]] è una generalizzazione della [[Potenziale Elettrico|Circuitazione di un Campo Elettrico]]:
$\Gamma_\gamma(\overrightarrow E)=0$ quando il campo magnetico rimane costante ($\Delta \Phi(\overrightarrow B)=0$).

## Campo Elettrico in un [[Magneti#Solenoide|Solenoide]]
*Abbiamo un [[Magneti#Solenoide|Solenoide]] di raggio $R$. Qual'è il [[Induzione Elettromagnetica#Induzione|Campo Elettrico Indotto]] in un punto a distanza $r$ dall'asse del  [[Magneti#Solenoide|Solenoide]]?*

>Partendo da (vedi perchè a pag 97)
>$\Gamma_\gamma(\overrightarrow E)=-\frac{\Delta \Phi(\overrightarrow B)}{\Delta t}$

La [[Potenziale Elettrico|Circuitazione del Campo Elettrico]] è
$$
\Gamma_\gamma(\overrightarrow E)=\overrightarrow{E}*\sum\limits_{k}\overrightarrow{\Delta l_k} 
$$
Inoltre $\sum\limits_{k}\overrightarrow{\Delta l_k}$ è il perimetro della curva $\gamma$, quindi
$$
\Gamma_\gamma(\overrightarrow E)=\overrightarrow{E}*2*\pi*r
$$
