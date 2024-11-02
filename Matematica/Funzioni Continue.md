---
tags: matematica
---

Una funzione è continua in $x_0$ se 
$$f(x_0)=\lim_{x->x_0} f(x)$$
>![[Pasted image 20241009154930.png]]
>La funzione non è continua in $A$, perchè il limite per $x$ che tende ad $A$ è diverso da $f(A)$.

>Si puo scrivere anche come $\lim_{h->0} f(x_0+h)=f(x_0)$

- Una funzione può essere continua a destra o a sinistra in base a quale lato del limite coincide.
- Una funzione __definita__ in un intervallo $[a,b]$ può essere continua in $[a,b]$ se è continua in ogni punto.
>Sono sempre continue nel loro dominio:
>- funzioni non fratte
>- funzioni goniometriche
>- funzioni esponenziali 
>- funzioni logaritmiche

>Se facciamo operazioni tra due funzioni continue lo rimangono.

# Teoremi sulle Funzioni Continue 
Tutti e 3 i teoremi assumono che $f(x)$ sia continua in un intervallo __CHIUSO E LIMITATO__ $I$.
## Weierstrass
$f(x)$ assume in $I$ sia il minimo che il massimo assoluto.
>Dove Il minimo assoluto è il minimo valore assunto in $I$.

>
## Valori intermedi
$f(x)$ assume in $I$ tutti i valori tra il minimo e il massimo assoluto.
### Esistenza degli zeri
Se agli estremi di $I$ $f(x)$ assume valori di segno opposto esiste un punto $p$ appartenente ad $I$ dove $f(p)=0$

# Punti di discontinuità
Se $f$ non è continua in $x_0$, allora è un punto di discontinuità.
per $x->x_{0}$ si distinguono in:

## Prima specie
Il limite destro e il limite sinistro sono numeri finiti e diversi.
La differenza tra i due è detta salto.
![[Pasted image 20241009160244.png]]
## Seconda specie
Uno dei due limiti è infinito/non esiste.
![[Pasted image 20241009160339.png]]
## Terza specie/eliminabili
I due limiti in $x_0$ sono uguali ma diversi da $f(x_0)$.
>Oppure $f(x)$ non è definita in $x_0$ 

La discontinuità è chiamata eliminabile perchè si può riscrivere la funzione per eliminarla.
![[Pasted image 20241009160450.png]]

# Esercizi
## Controllare se vale il teorema di Weierstrass in un intervallo $[a,b]$
Verificare se la funzione è continua nell'intervallo (chiuso) $[a,b]$.
## Individua massimo e minimo in $[a,b]$
Verificare se la funzione è continua in $[a,b]$.
- Se la funzione è retta/logaritmica/esponenziale controllare gli estremi 
- Altrimenti se è una parabola controllare il vertice.
## Verifica il teorema degli zeri in $[a,b]$
Verificare se la funzione è continua in $[a,b]$.
Verificare che gli estremi abbiano segno opposto.

##  Verificare che l'equazione $f(x)+g(x)=0$ ha una soluzione in $[a,b]$ tramite il teorema degli zeri. 
Controllare che entrambe le funzioni siano continue in $[a,b]$.
Verificare gli estremi di $y=f(x)+g(x)$ siano di segno opposto.
>L'abbiamo verificato, perchè l'equazione chiede se c'è un punto in $[a,b]$ dove $f(x)+g(x)=0$.

##  Verificare graficamente che l'equazione $f(x)+g(x)$ ha una soluzione in $[a,b]$.
$f(x)+g(x)=0$ può essere riscritta come $f(x)=-g(x)$, quindi se in $[a,b]$ $f(x)$ e $-g(x)$ si intersecano, esiste un punto dove  $f(x)=-g(x)$.
y7