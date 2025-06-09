# Probabilità Classica
$$
P(E)=\frac{casi\;favorevoi}{casi\;possibili}
$$
# Probabilità dell'evento contrario
$$
P(\bar{E})=1-P(E)
$$
# Simboli
# $P(A\land B)$
$\land$ vuol dire e. *(and)*
è uguale all'intersezione di due insiemi.
![[Pasted image 20250309114300.png]]

# $P(A\lor B)$
$\lor$ vuol dire oppure. *(or)*
è uguale all'unione di due insiemi.
 ![[Pasted image 20250309114308.png]]

$$
P(A \lor B)=P(A)+P(B)-(A\land B)
$$
>This is to avoid double counting.
>![[Pasted image 20250309114838.png]]

Due eventi possono essere:
- Incompatibili $P(A\land B)=0$
- Compatibili $P(A \land B) \neq0$
# $P(A| B)$
$P(A|B)$ è la probabilità di $A$ se $B$ è già successo. 
$$P(A|B)=\frac{P(A\land B)}{P(B)}$$
![[Pasted image 20250604193833.png]]
## Teorema di Bayes
$$P(A|B)=\frac{P(B|A)*P(A))}{P(B)}
$$
![[Pasted image 20250604210628.png]]
![[Pasted image 20250604210726.png]]


>Voglio la possibilità di $A$ se $B$.
>I casi favorevoli sono: (L'intersezione tra $A$ e $B$ diviso $A$) moltiplicato per $A$.
>I casi totali sono $B$.



>[!quote] Esempio
>Per fare gli esercizi mi [[#$P(A B)$|basta sapere la formula sopra.]]
>
>In una popolazione $40\%$ sono maschi e $60\%$ sono femmine.
>La possibilità che qualcuno sia maschio $P(A)=40\%$ 
>
>Dei maschi il $90\%$ indossa i pantaloni e delle femmine il $50\%$.
>
>Se so che qualcuno indossa i pantaloni, qual è la possibilità che sia maschio?
>Calcolo la percentuale di maschi e femmine che indossano i pantaloni.
>$$P(B\land A)=40\%*90\%=36\%$$ 
>$$P(B\land \overline{A})=60\%*50\%=30\%$$
>La possibilità che qualcuno indossi i pantaloni è la somma delle due percentuali.
>$$P(B)=36\%+30\%$$
>Quindi la probabilità è: maschi che indossano i pantaloni fratto persone che indossano i pantaloni.
>$$P(A|B)=\frac{P(A\land B)}{P(B)}=\frac{36\%}{36\%+30\%}$$

