---
tags: fisica, termologia
---
# Teorema di Carnot
Una [[Macchina Termica]] ha il massimo [[Rendimento]] se è reversibile.

__Nessuna macchina termica irreversibile che opera tra [[Serbatoio|Serbatoi]] a [[Temperatura]] costante può avere [[Rendimento]] maggiore di una reversibile che opera con le stesse [[Temperatura|Temperature]].__

__Tutte le macchine reversibili che operano tra le stesse [[Temperatura|Temperature]] hanno lo stesso [[Rendimento]]__

Il [[Rendimento]] è indipendente dalla sostanza di lavoro (il gas usato).

>Si può dimostrare che se fosse falso il calore potrebbe trasmettersi dai corpi freddi a quelli caldi, quindi è un altro modo per affermare il [[Secondo Principio della Termodinamica]] 

# Macchina di Carnot
Il [[Rendimento]] è
![[Rendimento#^7d21ff]]
Questo spinse LORD KELVIN a creare la scala [[Termodinamica]] delle temperature (in KELVIN), in modo tale che il loro rapporto sia uguale a quello dei 2 calori.
$$
\frac{|Q_f|}{Q_c}=\frac{T_f}{T_c}
$$
Tf e Tc __DEVONO__ essere in Kelvin.

Possiamo esprimere il massimo [[Rendimento]] di una Macchina Di Carnot come:
$$
\eta=1-\frac{T_f}{T_c}
$$

Per aumentare il [[Rendimento]] Tf deve essere più basso possibile, quindi deve tendere allo [[Zero Assoluto]]. Questo non è possibile, quindi il rendimento deve essere minore di 1.

$$
\eta \;-> 1 \;\;\;quando\;\;\;T_f\;->0
$$

# Ciclo di Carnot
[[Trasformazione Reversibile|Trasformazioni Reversibili]]
1. [[Trasformazione Isoterma|Espansione Isoterma]] ([[Temperatura]] costante *Tc*) 
2. [[Trasformazione Adiabatica|Espansione Adiabatica]] (Senza scambi di [[Calore]], la [[Temperatura]] scende *Tf*) 
3. [[Trasformazione Isoterma|Compressione Isoterma]] ([[Temperatura]] costante  *Tf*)  
4. [[Trasformazione Adiabatica|Compressione Adiabatica]] (Senza scambi di [[Calore]], la [[Temperatura]] sale *Tc*) 
![[Pasted image 20231017181420.png]]

# Dimostrazione
## [[Trasformazione Isoterma]] 
Durante una [[Trasformazione Isoterma]] 
$$
\Delta U=0
$$
Quindi 
$$
Q=L
$$
$$
Q=n*R*T*ln(\frac{V_f}{V_i})
$$
Abbiamo 2 [[Trasformazione Isoterma|Trasformazione Isoterme]] 
$$
Q_c=n*R*T_c*ln(\frac{V_b}{V_a})
$$
$$
Q_f=n*R*T_f*ln(\frac{V_d}{V_c})
$$
Quindi
$$
V_c>V_d\;\;\;\;\;\;\;\;\;Q_f<0
$$
dato che n e R rimangono costanti
$$
\frac{|Q_f|}{|Q_c|}=\frac{T_f*ln(\frac{V_c}{V_d})}{T_c*ln(\frac{V_b}{V_a})}
$$
>Abbiamo scambiato Vc e Vd perchè stiamo prendendo il valore assoluto.
## [[Trasformazione Adiabatica]] 
![[Trasformazione Adiabatica#^b2dc74]]

Possiamo sostituire 
$$
pV=nRT
$$
$$
(\frac{nRT}{V_i})*(V_i)^\gamma
$$
Quindi
$$
T_i*(V_i)^{\gamma-1}=T_f*(V_f)^{\gamma-1}
$$
Abbiamo 2 [[Trasformazione Isoterma]] 
$$
T_c*(V_b)^{\gamma-1}=T_f*(V_c)^{\gamma-1}
$$
$$
T_f*(V_d)^{\gamma-1}=T_c*(V_a)^{\gamma-1}
$$

Dividendo quelle con Tc e quelle con Tf otteniamo

$$
\frac{V_b}{V_a}=\frac{V_c}{V_d}
$$

## Mettendo insieme
$$

\frac{|Q_f|}{|Q_c|}=\frac{T_f*ln(\frac{V_c}{V_d})}{T_f*ln(\frac{V_c}{V_d})}

$$
$$
\frac{|Q_f|}{|Q_c|}=\frac{T_f}{T_c}
$$
