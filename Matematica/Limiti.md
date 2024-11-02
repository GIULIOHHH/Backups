---
tags: matematica
---


Identifichiamo ogni sottoinsieme di $R$ come un sottoinsieme di punti della retta dei reali $r$.
>Lo possiamo fare perchè esiste una corrispondenza [[biunivoca]] tra numeri e punti nella retta.

## Intervallo 
![[Pasted image 20240429153453.png]]
Sottoinsieme della retta, può essere:
- Aperto /Chiuso
- Limitato (corrispondenza a un segmento) / Illimitato (corrisponde a una semiretta.)
Un intervallo ha:
- Estremi 
- Lunghezza 
- Raggio 
- Centro
$\infty$ e $-\infty$ non sono numeri reali quindi sono sempre esclusi dall'intervallo.

# Intorno di un punto 
Un intorno completo di un punto $x_0$ è qualunque __INTERVALLO APERTO__ contentente $x_0$. Si indica con $I(x_0)$.
$$
I(x_0)=]x_0-\delta_1;x_0+\delta_2[
$$
>$\delta_1\;\delta_2$ sono numeri reali positivi.
![[Pasted image 20240429153927.png]]

Si può dividere in:
- intorno sinistro $I^-_\delta(x_0)=]x_0-\delta;x_0[$
- intorno destro $I^+_\delta(x_0)=]x_0;x_0+\delta[$
![[Pasted image 20240429154253.png]]
L'intorno di meno infinito è un intervallo aperto verso sinistra 
$I(-\infty)=]-\infty;a[\;\;\;\;\;\;(x\in R|x<a)$
>Dove esiste un numero reale maggiore di $a$
>Stessa cosa per l'intorno di più infinito.
>L'inorno di infinito è l'unione dei 2

Se $\delta_1=\delta_2$ si ha un intorno circolare (di raggio $\delta$).
$$
I_\delta(x_0)=]x-\delta;x+\delta[
$$
### Punti isolati 
$x_0$ è un punto isolato di un sottoinsieme $A$ se esiste almeno un intorno di $x_0$ che non contiene altri elementi di $A$. 
>Tipo i numeri interi perchè esiste l'intorno di raggio 1/2.
### Punti di Accumulazione 
$x_0$ è un punto di accumulazione di un sottoinsieme $A$ se ogni suo intorno completo contiene infiniti punti di $A$.
è equivalente alla dimostrazione dire che è $x_0$ è punto di accumulazione se ogni intorno completo contiene almeno un altro elemento di $A$.

$x_0$ può essere punto di accumulazione di $A$ anche senza appartenere ad $A$.

# Cose inutili 
Un insieme $A$ può essere superiormente limitato se possiamo determinare un maggiorante tale che qualsiasi numero di $A$ sia minore di esso.
Stessa cosa per inferiormente limitato. (determiniamo il minorante)
è limitato se è sia maggiormente che inferiormente limitato.

Allo stesso modo può essere illimitato.
>Dato un qualsiasi numero $m$ è sempre possibile scegliere una $x$ appartenente ad $A$ maggiore/minore di $m$.
##### Estremi di un insieme
Dato un insieme superiormente limitato il massimo $M$ è il più piccolo maggiorante.
$x<=M\;\;(\forall x\in A)$
$\forall \epsilon >0\;\exists\; x \in A:x>(M-\epsilon)$
>Scegliendo un numero positivo qualsiasi $\epsilon$ esiste una $x$ in $A$ tale che sia maggiore di $M-\epsilon$.

Stessa cosa per il minimo
# Limiti
Data una [[funzione]] $f$ e un punto di accumulazione $x_0$ di un dominio $D$, più scegliamo $x$ vicine a $x_0$ più $f(x)$ si avvicina a $l$, quindi 
$$\lim_{x->x_0}=l$$
inoltre, scegliendo un qualsiasi numero positivo $\epsilon$ esiste un intorno completo $I(x_0)$ per ogni $x \neq x_0$ appartente a $I$ e $D$ tale che
$$
|f(x)-l|<\epsilon
$$
Quindi ogni $f(x)$ appartiene a $]l-\epsilon;l+\epsilon[$.
![[Pasted image 20240429161503.png]]
Scritto tramite formula 
$$
\forall \epsilon>0\;\exists\;I(x_0):|f(x)-l|<\epsilon\;(\forall x\in I(x_0);x\neq x_0)
$$
# Funzioni continue 
Se $x_0$ appartiene al dominio di $f$ 
$$l=f(x_0)$$
Possiamo dire che $f$ è [[Funzioni Continue|continua]] in $x_0$ se $\lim_{x->x_0}=f(x_0)$. 
>Una funzione può essere continua nel suo dominio se in ogni suo punto è continua.

### Limite per eccesso
[![[Pasted image 20240429163232.png]]]()
$f(x)$ tende ad $l$ per eccesso se per $x$ che tende a $x_0$ assume valori sempre maggiori di $l$.
$$
\lim_{x->x_0}=l^+
$$
dato che $f(x)>l$
$$
0<f(x)-l<\epsilon
$$
### Limite per difetto 
![[Pasted image 20240429163133.png]]
per $x$ che tende a $x_0$ assume valori sempre minori di $l$.
$$
\lim_{x->x_0}=l^-
$$
$$
-\epsilon<f(x)-l<0
$$
### Limite destro
$x$ tende a $x_0$ restandone sempre maggiore. (stiamo considerando l'intorno destro $I^+(x_0)$ )
$$
\lim_{x->x_0^+}=l
$$
### Limite sinistro 
$x$ tende a $x_0$ restandone sempre minore. (stiamo considerando l'intorno sinistro $I^-(x_0)$ )
$$
\lim_{x->x_0^-}=l
$$
>Esiste il linite normale solo se limite destro e sinistro coincidono (sono uguali)


# Riassunto dei limiti particolari 
Se il limite è uguale a $\pm \infty$, a $\forall \epsilon>0$ si sostituisce $\forall M>0$ e a $|f(x)-l|< \epsilon$ si sostituisce $f(x)>M \;\;//\;f(x)<-M$
>Il limite diverge positivamente/negativamente e $f(x_0)$ non è definita. Si ha un asintoto verticale

Se per $x$ tende a  $\pm \infty$  a $\exists \;I(x_0)$si sostituisce  $\exists\; c>0$ e a $x \in I(x_0)$ si sostituisce $x>c\;\;//x<-c$
>Si ha un asintoto orizzontale

>se sono entrambi non si ha nessun tipo di [[Asintoto]].

# Operazioni con i limiti 
>Negli altri casi si svolgono le operazioni normalmente, ad esempio se $lim \;f(x)=l$ e $lim \;g(x)=m$ allora $lim (f(x)+g(x))=l+m$

- $\pm \infty$ sommato ad un numero (anche $\infty$ dello stesso segno) rimane uguale.
- $\pm \infty$ moltiplicato/diviso per un numero negativo cambia di segno.
- $\pm \infty$ moltiplicato/diviso per un numero positivo (anche $+\infty$) rimane uguale 
- Qualunque numero minore di 1 elevato a $+\infty$ è uguale a $0^+$.
- Qualunque numero diviso per $\pm \infty$ è uguale a 0.
- $0^-$ equivale ad un segno negativo. 
- Qualsiasi numero diviso per $0^+$ o $0^-$ diventa $\pm \infty$ secondo la regola dei segni.
# Forme indeterminate
Sono:
$$
+\infty\;-\infty
$$
$$
0^0
$$
$$
\infty^0
$$
$$
1^\infty
$$
$$
\frac{0}{0}
$$
$$
\frac{\infty}{\infty}
$$
$$
\infty*0
$$

## $+\infty\;-\infty$
##### Funzioni polinomiali
Per risolverla si raccoglie la $x$ di grado maggiore.

##### Funzioni [[Irrazionali]]
In caso di una funzione irrazionale con 2 numeri si applica il prodotto notevole $(a-b)*(a+b)$
## $\frac{\infty}{\infty}$
Per risolverla si raccoglie la $x$ di grado maggiore nel numeratore, si rifà la stessa cosa nel denominatore e si semplifica.
## $0*\infty$
Di solito si risolve con formule goniometriche.

## $\frac{0}{0}$
Scomponiamo in fattori sia numeratore che denominatore, di solito con ruffini.
## Altri
$$
f(x)^{g(x)}=e^{ln(f(x))*g(x)}
$$
questo perchè per la definizione dei [[Logaritmo|Logaritmi]] 
$$
a=e^{ln(a)}
$$
Quindi 
$$
a^x=e^{ln(a^x)}
$$

$$
a^x=e^{x*ln(a)}
$$
# Teorema del confronto
Date 3 funzioni $h(x)$ $f(x)$ $g(x)$ definite in uno stesso intorno di $x_0$, se in ogni altro punto dell'intorno diverso da $x_0$ 
$$
h(x)\le f(x) \le g(x)
$$ oppure 
$$
h(x)<f(x)<g(x)
$$

e
$$\lim_{x->x_0}h(x)/g(x)=l$$
il limite di $f(x)$ è $l$.
> se $5\le f(x)\le5$ allora $f(x)=5$

![[Pasted image 20240506163202.png]]
# Limiti notevoli

# $$\lim_{x->0} \frac{sin(x)}{x}=1$$
$sin(x)/x$ è pari, perchè il seno è dispari, quindi sostitutendo $-x$
$$
\frac{sin(-x)}{-x}
$$
$$
\frac{-sin(x)}{-x}
$$
$$
\frac{sin(x)}{x}
$$
Dato che è pari 
$$
\lim_{x->0^+}=\lim_{x->0^-}
$$
quindi possiamo considerarla solo da destra.
$$
sin(x)<x<tan(x)
$$
Dividiamo tutto per il seno
$$
1<\frac{x}{sin(x)}<\frac{1}{cos(x)}
$$
Invertiamo 
$$
1>\frac{sin(x)}{x}>cos(x)
$$
$$
\lim_{x->0^+}1=1
$$
$$
\lim_{x->0^+}cos(x)=1
$$
quindi per il teorema del confronto 
$$
\lim_{x->0^+}\frac{sin(x)}{x}=1
$$
# $$ \lim_{x->0}\frac{1-cos(x)}{x}=0 $$
moltiplichiamo tutto per $1+cos(x)$
$$
\frac{1-cos^2(x)}{x*(1+cos(x))}
$$
Per la relazione fondamentale della [[Goniometria]] 
$$
\frac{sin(x)}{x}*\frac{sin(x)}{1+cos(x)}
$$
quando $sin(0)=0$ quindi 
$$
1*\frac{0}{1+cos(x)}=0
$$
# $$\lim_{x->x_0}\frac{1-cos(x)}{x^2}=\frac{1}{2}$$
Ripetendo la stessa procedura di sopra 
$$
\frac{sin(x)}{x}*\frac{sin(x)}{x}*\frac{1}{1+cos(x)}
$$
Dato che $cos(0)=1$
$$
1*1*\frac{1}{2}=\frac{1}{2}
$$




# $$
\lim_{x->0} \frac{\log_a(1+x)}{x}=log_a(e)
$$
# $$\lim_{x->0}\frac{a^x-1}{x}=ln(a)$$
# $$
\lim_{x->0}\frac{(x+1)^k-1}{x}=k$$
# $$\lim_{x->\pm \infty} (1+\frac{1}{x})^x=e
$$
