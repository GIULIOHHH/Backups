# Definizione di Massimo e Minimo
## Assoluti
Data una funzione $f(x)$ in un domino $D$, $x_0$ è:
- **Punto di Massimo assoluto** se $f(x_0)\ge f (x) \;\;\forall x \in D$ 
	- $f(x_0)=M$ è il massimo assoluto.
- **Punto di Minimo assoluto** $f(x_0)\le f (x) \;\;\forall x \in D$ 
	-  $f(x_0)=m$ è il minimo assoluto.
>Un punto è il massimo se in nessun altro punto si può ottenere un valore maggiore.

>Punti di massimo e minimo assoluto si dicono anche *punti di estremo assoluto*.

## Relativi
Data una funzione $f(x)$ in un intervallo $[a,b]$, $x_0$ è:
- **Punto di Massimo relativo** se esiste un intorno $I$ dove $f(x_0)\ge f (x) \;\;\forall x \in I$ 
-  **Punto di Minimo relativo** se esiste un intorno $I$ dove $f(x_0)\le f (x) \;\;\forall x \in I$ 
>[!info] La stessa definizione di quelli assoluti, ma la formula deve essere vera solo per un intorno qualsiasi. 

- Se $x_0$ è interno a $[a,b]$, l'intorno $I$ deve essere [[Limiti#Intorno di un punto|completo]].
- Se $x_0=a$, L'intorno deve essere destro. 
>stessa cosa se $x_0=b$
![[Pasted image 20250119210950.png|400]]
![[Pasted image 20250119211211.png|200]]

>- Punti di massimo e minimo assoluto si dicono anche *punti estremanti relativi*.
>- I valori in quei punti sono *estremi relativi.*
>- Un punto di estremo assoluto è sempre anche di estremo relativo, ma il contrario non è sempre vero.
>- Ci può essere un punto di estremo assoluto/relativo anche quando la funzione non è continua/derivabile.

# Concavità
Data una funzione $f(x)$ continua e derivabile in $]a,b[$ e una retta $r(x)$ tangente in $x_0$:
- In $x_0$ ha la concavità rivolta verso l'alto se esiste un intorno completo $I$ di $x_0$ tale che $f(x)>r(x) \;\;\forall x \in I - \{x_0\}$
	- La funzione si dice **Convessa** (se è sempre verso l'alto)
- In $x_0$ ha la concavità rivolta verso il basso se esiste un intorno completo $I$ di $x_0$ tale che $f(x)<r(x) \;\;\forall x \in I - \{x_0\}$
	- - La funzione si dice **Concava** (se è sempre verso il basso)
>[!info] Deve esistere un intorno tale che per tutti i suoi punti (tranne $x_0$), $f(x)$ è sempre sopra la retta tangente.

>- Invece di alto/basso si può scrivere *semiasse positivo/negativo delle y.*
>- Una funzione può avere la concavità verso l'alto/basso in un intervallo.

![[Pasted image 20250119212441.png]]

# Flessi
Data una funzione definita in $]a,b[$, un flesso è un punto dove cambia concavità.

- Se la funzione è derivabile, la tangente alla curva è parallela all'asse x o obliqua.
	- Il flesso è orizziontale o obliquo.
- Se la derivata è infinita, la tangente è parallela all'asse y.
	- Il flesso è verticale.
![[Pasted image 20250119212952.png|300]]


Se la concavità a sinistra del punto di flesso è negativa e quella a destra positiva il flesso è ascendente. 
>Altrimenti è discendente.
![[Pasted image 20250119213242.png|400]]

# Teorema di Fermat
Data una funzione $f(x)$ definita in $[a,b]$ e derivabile nei valori interni, se $x_0$ è interno e un [[#Definizione di Massimo e Minimo|punto estremante relativo]], $f'(x_0)=0$.
Negli estremi o quando la funzione non è derivabile, il teorema non è applicabile.
![[Pasted image 20250119214329.png]]
Quindi, i punti di massimo e minimo sono da cercare:
1. Dove $f'(x)=0$.
	1. Chiamati anche **punti stazionari.**
2. Agli estremi.
3. Nei punti non derivabili.

Questa è una condizione **necessaria**, ma **non sufficiente**.
![[Pasted image 20250119213750.png]]

Data una funzione $f(x)$, definita e continua in un intorno completo $I$ di un punto stazionario $x_0$ e derivabile in ogni punto appartenente a $I$ (ma non necessariamente $x_0$):

- Se in $x_0^-$ $f'(x)>0$ e in $x_0^+$ $f'(x)<0$, $x_0$ è punto di massimo relativo
- Se in $x_0^-$ $f'(x)<0$ e in $x_0^+$ $f'(x)>0$, $x_0$ è punto di minimo relativo
- Se i segni a sinistra e destra sono uguali (e la funzione è derivabile in $x_0$), si ha un flesso orizzontale.
	- Se il segno è positivo è un flesso ascendente.
>Si può dire anche che si ha un punto di massimo relativo se per ogni x nell' intorno $I$ si ha $f'(x)>0$ se $x<x_0$ e $f'(x)<0$ quando $x>x_0$.

![[Pasted image 20250119220037.png]]

>**Trovare massimo e minimo assoluti in una funzione continua.**
>1. Se la funzione è definita in un intervallo chiuso e limitato, [[Funzioni Continue#Weierstrass|Il teorema di Weierstrass]] garantisce l'esistenza di massimo e minimo. Si confrontano tutti i punti estremanti relativi + gli estremi.
>2. Altrimenti, potrebbero non esistere. Calcoliamo i limiti agli estremi dell'intervallo e vediamo se sono finiti o infiniti.

# Trovare i flessi
>- Facciamo la derivata seconda. 
>	- I punti dove non è definita sono flessi a tangente verticale.
>- Studiamo il segno.
>	- I punti dove il segno cambia sono flessi a tangente orizzontale o obliqua.
>		- Orrizzontale se sostituendoli alla derivata prima otteniamo zero.