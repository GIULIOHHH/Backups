# Teoremi dell'unicità degli zeri
## Primo Teorema
**Condizioni:**
Una funzione $f(x)$
- Continua in un intervallo chiuso e limitato $[a,b]$
- Derivabile nei valori interni.
- La derivata diversa da $0$ nei valori interni.
- $f(a)*f(b)<0$ *(gli estremi di segno opposto)*
Allora esiste un solo punto interno dove $f(x)=0$.

>**Intution:**
>- Abbiamo gli opposti di segno uguale, quindi [[Funzioni Continue#Weierstrass|prima o poi la funzione deve essere 0]].
>- La derivata prima non è mai zero, [[Teoremi Sulle Derivate#Conseguenze|quindi la funzione rimane crescente/decrescente]].
>- Se la funzione è sempre crescente/decrescente dopo il primo zero non può tornare indietro.
## Secondo Teorema
>[!info] Uguale al primo, ma invece di derivata prima usiamo la derivata seconda.

# Metodo Di Bisezione per l'approssimazione
Vogliamo approssimare una soluzione di $f(x)=0$ con $k$ cifre decimali esatte.
Dato un intervallo $[a,b]$ dove gli estremi sono di segno opposto e $f(x)=0$ una sola volta:
1. Determiniamo il punto medio $x_m=(a+b)/2$
2. Calcoliamo il valore $f(x_m)$
	1. Se è uguale a $0$ abbiamo finito.
3. Altrimenti scegliamo l'intervallo in base al segno di $f(x_m).$
![[Pasted image 20250217210855.png]]
4. Iteriamo finchè le prime $k$ cifre di $a$ e $b$ non coincidono.

>Calcoliamo l'errore come:
>$$
ε_n=\frac{b_0-a_0}{2^{n+1}}
$$

>**Come verifichiamo che la funzione è $0$ solo una volta in un intervallo?**
>Possiamo dividere la funzione originale in due portando alcuni termini a destra dell'uguale. 
>Nei punti dove si intersecano le due nuove funzioni quella originale sarà $0$.