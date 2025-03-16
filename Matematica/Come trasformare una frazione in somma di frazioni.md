# Come Trasformare in somma di frazioni
- Abbiamo una frazione del tipo $D/N$. 
- Dobbiamo scomporre il numeratore $N$ nei suoi fattori: $N_1,N_2,N_3...$
- Per ogni fattore:

	1. Se $N=(ax+b)^y$, aggiungiamo alla somma tutte le frazioni:
$$
\frac{A_1}{(ax+b)^1}+\frac{A_2}{(ax+b)^2}...+\frac{A_y}{(ax+b)^y}
$$
	2. Se $N=(ax^2+bx+c)^y$, aggiungiamo alla somma tutte le frazioni:
$$
\frac{A_1x+B_1}{(ax^2+bx+c)^1}+\frac{A_2x+B_2}{(ax^2+bx+c)^2}...+\frac{A_yx+B_y}{(ax^2+bx+c)^y}
$$
	3. Se nella fattorizzazione c'è una costante la aggiungiamo a un qualsiasi termine della somma. 

>-Così è come se portassimo la costante dentro un fattore.
>- $A$ e $B$ sono delle incognite. La $A_1$ di un fattore è diversa dall'$A_1$ di un altro fattore.

>Ci interessano solo questi due casi perchè secondo il teorema fondamentale dell'algebra ogni polinomio può essere ridotto in questi
# Come Trovare $A$ e $B$.
1. Abbiamo:
$$
\frac{px+q}{ax^2+bx+c}=\frac{A}{a(x-x_1)}+\frac{B}{(x-x_2)}$$
2. Calcoliamo la somma della funzione a destra:
$$
\frac{A(x-x_2)+B(ax-ax_1)}{ax^2+bx+c}
$$
$$
\frac{Ax-Ax_2+Bax-Bax_1}{ax^2+bx+c}
$$
$$
\frac{x(A+B)+(-Ax_2-Bax_1)}{ax^2+bx+c}
$$
3. Quindi 
$$
\frac{px+q}{ax^2+bx+c}=\frac{x(A+B)+(-Ax_2-Bax_1)}{ax^2+bx+c}
$$
4. Dato che le due funzioni sono uguali, $(A+B)=p$ e $(-Ax_2-Bax_1)=q$.
>Questo vale per via del principio di identità dei polinomi.
5. Facendo il sistema possiamo ottenere $A$ e $B$.