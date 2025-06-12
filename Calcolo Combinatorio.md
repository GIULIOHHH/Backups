# Permutazioni
Abbiamo $n$ oggetti. In quanti modi possiamo ordinarli?
$$
P(n)=n!
$$
>Abbiamo $n$ opzioni per il primo oggetto, $(n-1)$ per il secondo. Continuo $n$ volte (finche non arrivo all'ultimo)

# Disposizioni
Abbiamo $n$ oggetti. In quanti modi possiamo ordinare $k$ oggetti?
$$
D(n,k)=\frac{n!}{(n-k)!}
$$
>Se scegliamo $k$ oggetti ne restano $r=(n-k)$.
>Abbiamo $n$ opzioni per il primo oggetto, $(n-1)$ per il secondo. Faccio $n!$ ma considero $k$ oggetti, quindi devo eliminare i primi $r$ termini. Per farlo divido per $r!$

 >[!quote] Esempio.
 >Da 7 oggetti scegline 3.
 >Le opzioni di oggetti da scegliere sono:
 >$$7*6*5$$
 >Come lo scrivo?
 >Posso scrivere $$7!=7*6*5*4*3*2*1$$
 >
Devo eliminare $4*3*2*1$, aka $(7-3)!=4!$ 
Quindi faccio
>$$
\frac{7!}{(7-3)!}
$$
# Combinazioni
Abbiamo $n$ oggetti. In quanti modi possiamo prendere $k$ oggetti? (senza l'ordine)
$$
C(n,k)=\frac{n!}{k!*(n-k)!}
$$
Si scrive anche come
$$
  \binom{n}{k}
$$
$$
  \binom{n}{k}=\binom{n-1}{k-1}+\binom{n-1}{k}
$$
