---
tags: matematica
---
Un [[equazione]] goniometrica contiene una [[funzione]] goniometrica dell'incognita.

- [[Coseno-Seno]] devono essere compresi tra -1 e 1.
- [[Tangente]]/[[Cotangente]] sono sempre determinate.
---
$$
sin(γ)=a
$$
$$
x=γ+2k\pi \;\; V\;\;(\pi-γ)+2k\pi
$$
---
$$
cos(γ)=b
$$
$$
x=γ+2k\pi \;\;\;V\;\;-γ+2k\pi
$$
---
$$
tan(γ)=c
$$
$$
x=γ+k\pi
$$
---
# Casi particolari 
>Per avere lo stesso seno devono essere [[congruenti]] o supplementari
$$
sin(\alpha)=sin(\beta)
$$
$$
\alpha=\beta+2k\pi\;\;V\;\;\alpha+\beta=\pi+2k\pi
$$
---
$$
sin(\alpha)=-sin(\beta)
$$
$$
-sin(\beta)=sin(-\beta)
$$
---
$$
sin(\alpha)=cos(\beta)
$$
$$
sin(\alpha)=sin(\frac{\pi}{2}-\beta)
$$
---
$$
sin(\alpha)=-cos(\beta)
$$
$$
sin(\alpha)=sin(-\frac{\pi}{2}+\beta)
$$
---
$$
cos(\alpha)=cos(\beta)
$$
$$
\alpha=±\beta+2k\pi
$$
---
$$
cos(\alpha)=-cos(\beta)
$$
$$
cos(\alpha)=cos(\pi-\beta)
$$
---
$$
tan(\alpha)=tan(\beta)
$$
$$
\alpha=\beta+k\pi
$$
---
$$
tan(\alpha)=tan(\beta)
$$
$$
tan(\alpha)=tan(-\beta)
$$
# Equazioni riconducibili ad equazioni elementari
Per ricondurre equazioni con più funzioni goniometriche ad equazioni elementari si devono esprimere le diverse funzioni con una sola di esse.
# Equazioni lineari in seno e coseno.
$$
a sin(x)+bcos(x)+c=0
$$
dove 
$$
a≠0\;\;\;\;\;\;\;\;\;\;b≠0

$$
---
## SE c=0
$$
asin(x)+bcos(x)=0
$$
possiamo dividere tutto per il coseno, in modo da avere:
$$
tan(x)=-\frac{b}{a}
$$
inoltre il coseno deve essere ≠0, ovvero
$$
x≠\frac{\pi}{2}+2k\pi
$$
perchè altrimenti
- Primo caso
$$
a*1+b*0=0
$$
$$
a=0
$$
$$
b=0
$$
- Secondo caso
$$
a*(-1)+b*0=0
$$
$$
a=0
$$
$$
b=0
$$
---
## SE c≠0
### CON formule parametriche
$$
sin(x)=\frac{2t}{1+t^2}
$$
$$
cos(x)=\frac{1-t^2}{1+t^2}
$$

- sostituiamo queste formule al seno e al coseno.

inoltre bisogna verificare che l'[[equazione]] di partenza __NON AMMETTE__ la soluzione
$$
x=\pi+2k\pi
$$
Quindi
$$
x≠\pi+2k\pi
$$
perchè
$$
tan(\frac{x}{2})≠\frac{\pi}{2}+k\pi
$$
### Metodo Grafico
Aggiungiamo la relazione fondamentale della [[Goniometria]].
$$


\begin{cases} 
asin(x)+bcos(x)+c=0  \\
cos^2(x)+sin^2(x)=1

\end{cases}
$$
Poniamo
$$
cos(x)=X\;\;\;\;\;\;\;sin(x)=Y
$$
$$


\begin{cases} 
aY+bX+c=0  \\
X^2+Y^2=1

\end{cases}
$$
1. La prima è l'[[equazione]] di una [[Retta]] 
2. La seconda è l'[[equazione]] di una [[Circonferenza_old]] con centro nell'origine e raggio 1

Otteniamo 1/2 paia di coordinate, che corrispondono alle intersezioni tra [[Retta]] e [[Circonferenza_old]].

In base a quelle possiamo trovare gli angoli.
>Ad esempio se otteniamo X=1/2 e Y=√(3)/2, sappiamo che l'angolo è π/3+2kπ

>Se necessario possiamo ri-sostituire seno e coseno e risolvere un secondo sistema.
>