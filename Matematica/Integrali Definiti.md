# Area del Trapezoide
>[!Done] Definizione
>
>Data una funzione sempre positiva (o nulla) e continua $f(x)$ e un intervallo chiuso e limitato $[a,b]$
>Il **Trapezoide** è la figura definita da:
>- $f(x)$
>- $x=a$ e $x=b$ (rette verticali)
>- $y=0$
![[test 2.png|400]]

Possiamo dividere $[a,b]$ in $n$ parti di ampiezza uguale.
>Calcoliamo l'ampiezza con $\Delta x =\frac{b-a}{n}$
Abbiamo due modi per calcolare l'altezza:
1. Prendendo il punto minimo.
2. Prendendo il punto massimo.
>Il [[Funzioni Continue#Weierstrass|Teorema di Weierstrass]] ci garantisce che entrambi esistono sempre.
- $s_n$ (_Somma integrale inferiore_) è la somma delle aree prendendo i punti minimi.
- $S_n$ (_Somma integrale superiore_) è la somma delle aree prendendo i punti massimi.
![[small 1.png|400]] ![[big 1.png|400]]
Dato che $s_n$ e $S_n$ approssimano $f(x)$ per difetto e per eccesso, l'area del trapezoide $S$:
$$
s_n{\le}S{\le}S_n
$$
Più aumenta $n$ più precisa diventa l'approssimazione. $s_n$ e $S_n$ convergono allo stesso limite ($S$).
$$
\lim_{n->\infty}s_n=\lim_{n->\infty}S_n=S
$$
$S$ è l'**Integrale definito**:
$$
\int_a^bf(x)dx
$$
Possiamo generalizzarlo a funzioni negative:
>Dimostrazione:
>- Dividiamo la funzione in $n$ intervalli con ampiezze variabili.
>- L'altezza è il valore della funzione in un punto arbitrario dell'intervallo.
>- Se l'ampiezza massima $\Delta x_{max}$ tende a $0$, tutte le altre tendono a $0$. Si può dimostrare che tutte le aree $\overline{S}$ ottenute tendono ad uno stesso valore (indipendentemente dalle ampiezze degli intervalli o i punti scelti per l'altezza).
>$$\int_a^bf(x)dx=\lim_{\Delta x_{max}->0}\overline{S}$$

>[!example] L'integrale rappresenta la differenza tra l'area positiva e quella negativa.
>1. Se $f(x)$ è sempre positiva l'integrale è l'area del trapezoide.
>2. Se $f(x)$ è sempre negativa, l'integrale è l'area del trapezoide con il segno meno.
>3. Se $f(x)$ cambia segno, l'intervallo $[a,b]$ va diviso in sottointervalli sempre positivi/negativi.

>[!done] Formula:
>se $a<b$:
>$$
>\int_a^bf(x)dx=-\int_b^af(x)dx
>$$

Inoltre:$$
\int_a^af(x)dx=0
$$
# Proprietà
Valgono le [[Integrali Indefiniti#Proprietà degli Integrali|Proprietà degli integrali indefiniti]], inoltre:

$$
\int_a^bf(x)+\int_b^cf(x)=\int_a^cf(x)
$$
>Sommando due integrali adiacenti otteniamo un unico integrale
> ![[int.png|300]]

Inoltre se $f(x)\le g(x)$:
$$
\int_a^bf(x){\le}\int_a^bg(x)
$$
Poi:
$$
\int_a^bk=k(b-a)
$$
$$
|\int_a^bf(x)|=\int_a^b|f(x)|
$$ 
# Teorema della Media
>[!done] Teorema
>Data una funzione $f(x)$ continua in $[a,b]$, esiste almeno un punto $z$ tale che:
>$$
>\int_a^bf(x)=(b-a)*f(z)
>$$
![[valore medio.png|400]]

>$z$ è il valore medio della funzione. Moltiplicando $z$ per $(b-a)$ otteniamo la stessa area dell'integrale (se la funzione è positiva), così come moltiplicando la media per il numero di casi otteniamo la loro somma.

>[!danger] Dimostrazione:
>1. $f(x)$ è continua, quindi vale il [[Funzioni Continue#Weierstrass|Teorema di Weierstrass]]. 
>$$m\le f(x)\le M$$
>2. Per le proprietà degli integrali:
>$$
>\int_a^bm{\le}\int_a^bf(x){\le}\int_a^bM$$
>3. Sempre per le proprietà:
>$$
>m*(b-a){\le}\int_a^bf(x){\le}M*(b-a)
>$$
>$$m{\le}\frac{\int_a^bf(x)}{(b-a)}{\le}M
>$$
>4. Dato che è tra $m$ e $M$, quello sopra è un valore intermedio.
>5. Per il [[Funzioni Continue#Valori intermedi|Teorema dei valori intermedi]] la funzione assume a un certo punto tutti i valori intermedi, quindi esiste un punto $z$ tale che:
>$$
>f(z)=\frac{\int_a^bf(x)}{(b-a)}
>$$
>6. Facendo la formula inversa otteniamo la formula di sopra.

>Perchè la chiamiamo media? (useless)
>L'area $\overline S$ è la somma di segmenti di ampiezza uguale $(b-a)/n$ e altezza $f(c)$ (dove $c$ è un punto arbitrario). 
>Quindi:
>$$
\overline S=f(c_1)*\frac{b-a}{n}+...+f(c_n)*\frac{b-a}{n}
$$
>$$
\overline S=\frac{b-a}{n}*(f(c_1)+...+f(c_n))
$$
>Dividendo per $(b-a)$ otteniamo la media.
>$$
\frac{\overline S}{b-a}=\frac{(f(c_1)+...+f(c_n))}{{n}}
$$
>Per $n$ che tende a infinito $\overline S=\int_a^bf(x)dx$
>$$
\lim_{n->\infty}\frac{\overline S}{b-a}=\frac{\int_a^bf(x)dx}{b-a}
$$
# Come calcolare gli integrali Definiti

L'integrale definito di $f(x)$ è la differenza tra i valori assunti da una primitiva $F(x)$ negli estremi dell'intervallo.
# Volume di un solido
>Abbiamo una funzione $f(x)$. Per ogni posizione $x_0$, $f(x_0)$ ci dà l'altezza in quel punto. Se integriamo tutte le altezze otteniamo l'area sotto la curva.

Abbiamo una funzione $A(x)$. Per ogni posizione $x_0$, $A(x)$ ci dà l'area in quel punto. Se integriamo tutte le aree otteniamo il volume.
![[3D.png]]
>[!Done] Formula
>Il volume di un solido da $a$ a $b$ è:
>$$\int_a^{b}{A(x)}$$
>Dove $A(x_0)$ è l'area in un punto $x_0$.

>Solitamente $A(x)$ dipende dalla funzione bidimensionale $f(x)$.

>Quando parla di piani perpendicolari all'asse $x$ basta pensare a questo.
>![[WhatsApp Image 2025-06-03 at 18.23.19.jpeg|300]]

# Volume del solido di rotazione attorno all'asse x
Il solido di rotazione è formato da tanti cerchi.
L'area del cerchio è $A=\pi*r^2$. 

In ogni punto $x_0$ $r=f(x_0)$, quindi dato che sono tanti cerchi:
$$
Vol=\int_a^b\pi*[f(x)]^2
$$
![[Pasted image 20250427181058.png]]
$$
Vol=\pi*\int_a^b[f(x)]^2
$$
## Traslare la funzione
>[!quote]
>Calcola il volume del solido di rotazione di $f(x)$ attorno alla retta $y=k$.
>![[trasla.png]]
>Dobbiamo traslare la funzione.
>Ogni valore di $y$ deve essere $k$ unità più basso. 
>$$Y=y-k$$
>Le $x$ non devono cambiare.
>$$
>X=x
>$$
>Sostituendo $Y$ a $y$ e $X$ a $x$ trasliamo la funzione.

# Asse Y
Se uno dei confini della funzione ($a$ o $b$) è $x=0$ , posso usare la stessa formula di sopra.
$$
Vol=\int_a^b\pi*[f(x)]^2
$$
Altrimenti uso:
## Metodo dei gusci cilindrici
$$
Vol=\int_{a}^{b}2\pi*x*f(x)
$$

### Spiegazione
Per ogni valore $f(x_0)$, possiamo creare un guscio cilindrico.
La funzione $A(x)$, che ci dà l'area in $x$ è quindi:
$$
A(x)=2\pi*x*f(x)
$$
Dove $2\pi*x$ è il perimetro del raggio e $f(x)$ è l'altezza del guscio cilindrico. 
Integrando otteniamo il volume totale.
![[bruh.png]]

# Teorema fondamentale del calcolo integrale 
>è la definizione di integrale definito.

La funzione integrale
$$
F(x)=\int_a^xf(t)$$
è una primitiva di $f(x)$ per ogni punto considerato.
$$
F^{'}(x)=f(x)
$$

>Quindi data una funzione ritorna l'area del trapezoide da $a$ a $x$.
>![[idk 1.png]]



# Integrali Impropri

# Esercizi

## Area compresa tra due curve
L'integrale della curva più alta meno l'integrale della curva più bassa.

## Cambiare gli estremi
Abbiamo una funzione $f$. Conosciamo l'integrale definito
$$
\int_{A_1}^{A_2}f(a)
$$
Dobbiamo trovare
$$
\int_{B_1}^{B_2}f(b)
$$
Il nostro obbiettivo è trasformare l'integrale sconosciuto nell'integrale noto moltiplicato per una costante.
>[!Done] Formula
$$\int_{a}^{b}{f[g(x)]}*g^{'}(x)=\int_{g(a)}^{g(b)}f(t)$$

>[!Quote] Esempio
>Sapendo che
>$$
\int_0^8f(x)=10
>$$
>trova $$\int_0^4f(2x)$$
>Osserviamo che:
> $$\int_0^4f(2x)= \frac{1}{2}\int_0^{4}2*f(2x)$$
> Quindi sostituendo nella formula:
> $$\frac{1}{2}\int_0^{4}2*f(2x)=\frac{1}{2}\int_{2*(0)}^{2*(4)}f(x)
> $$
> Quindi il risultato è
> $$
\frac{1}{2}*10=5
> $$


>[!Quote] Esempio
>Sapendo che
>$$
\int_0^8f(x)=6
>$$
>trova: $$\int_2^0x^2f(x^3)$$
>Invertiamo i due estremi:
>$$\int_2^0x^2f(x^3)=-\int_0^2x^2f(x^3)$$
>Osserviamo che $3x^2$ è la derivata di $x^3$, quindi possiamo applicare la formula:
>$$
>-\frac{1}{3}\int_0^2x^2f(x^3)=-\frac{1}{3}\int_{0^3}^{2^3}f(x)
>$$
>Quindi il risultato è
> $$
>-\frac{1}{3}*6=-2
> $$



## Trova la derivata partendo dall'Integrale
Se
$$
F(x)=\int_{b(x)}^{a(x)}f(t)
$$
$$
F^`(x)=a^`(x)*f(a(x))-b^`(x)*f(b(x))
$$
>[!quote] Esempio
>Trova $F^`(x)$
>$$F(x)=\int_x^{2x}3\sqrt{t-1}$$
>Dobbiamo fare il dominio.
>$$t-1\ge0$$
>$$t\ge1$$
>Applicando la formula
>$$F^`(x)=2*[3\sqrt{(2x)-1}]-1*[3\sqrt{(x)-1}]$$
>$$F^`(x)=6\sqrt{(2x)-1}-3\sqrt{(x)-1}$$


