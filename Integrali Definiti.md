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
# Volume del solido di rotazione attorno all'asse x
Il solido di rotazione è formato da tanti cerchi.
L'area del cerchio è $A=\pi*r^2$. In ogni punto $x_0$ $r=f(x_0)$, quindi sostituendo $r$ con l'area del trapezoide otteniamo il volume.
![[Pasted image 20250427181058.png]]
$$
A=\pi*[\int_a^bf(x)]^2
$$

# Teorema fondamentale del calcolo integrale (fare meglio)

>![done] Formula
>La funzione integrale è definita come:
>$$
F(x)=\int_a^xf(t)$$
Quindi data una funzione ritorna l'area del trapezoide fino ad un punto $x$.
Per ogni punto dell'intervallo:
$$
F^{'}(x)=f(x)
$$
quindi $F(x)$ è una primitiva di $f(x)$
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

