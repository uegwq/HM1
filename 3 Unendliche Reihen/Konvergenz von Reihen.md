
TARGET DECK
Höhere Mathematik I

Konvergenz von Reihen
--
## Kriterien
***
1. Monotoniekriterium:
   Sind alle $a_n\ge0$ und ist $(s_n)$ beschränkt, so ist $\sum^\infty_{n=0}a_n$ konvergent.
2. Cauchykriterium:
   $\sum^\infty_{n=1}a_n$ ist konvergent $\iff$
$$\forall\varepsilon\ge0\exists n_0\in\Bbb N\forall m>n\ge n_0: \left\vert\sum^m_{k=n+1}a_k\right\vert<\varepsilon$$
3. Ist $\sum^\infty_{n=1}a_n$ konvergent, so gilt $a_n\rightarrow 0$.
4. Die Reihe $\sum^\infty_{n=1}a_n$ sei konvergent. Dann ist für jedes $m\in\Bbb N$ die Reihe $\sum^\infty_{n=m+1}a_n$ konvergent und für $r_m=\sum^\infty_{n=m+1}a_n$ gilt: $r_m\rightarrow 0$.

5. Leibnitzkriterium:
   Es sei $(b_n)$ eine Folge, sodass
   1. $(b_n)$ ist monoton fallend und
   2. $b_n\rightarrow 0$
   Dann ist $\sum^\infty_{n=1}(-1)^{n+1}b_n$ konvergent.

6. Majorantenkriterium:
   Gilt $|a_n|\le b_n$ ffa $n\in\Bbb N$ und ist $\sum^\infty_{n=1}b_n$ konvergent, so ist $\sum^\infty_{n=1}a_n$ absolut konvergent.
7. Minorantenkriterium:
   Gilt $a_n\ge b_n\ge 0$ ffa $n\in\Bbb N$ und ist $\sum^\infty_{n=1}b_n$ divergent, so ist $\sum^\infty_{n=1}a_n$ divergent.

8. Wurzelkriterium (WK):
   Es sei $(a_n)$ eine Folge, $c_n:=\sqrt[n]{\left|a_n\right|}$.
   1. Ist $(c_n)$ unbeschränkt, so ist $\sum^\infty_{n=1}a_n$ divergent.
   2. Es sei $(c_n)$ beschränkt und $\alpha:=\lim\ sup_{n\rightarrow\infty}c_n$. Dann:
      1. Ist $\alpha<1$, so ist $\sum^\infty_{n=1}a_n$ absolut konvergent.
      2. Ist $\alpha >1$, so ist $\sum^\infty_{n=1}a_n$ divergent.
      Im Falle $\alpha=1$ ist keine allgemeine Aussage möglich.

9. Quotientenkriterium:
   (Es sei $a_n\not=0$ ffa $n\in\Bbb N$ und $c_n:=\left|\frac{a_{n+1}}{a_n}\right|$.
   1. Ist $c_n\ge1$ ffa $n\in\Bbb N$, so ist $\sum^\infty_{n=1}a_n$ divergent.
   2. Es sei $(c_n)$ beschränkt. Dann gilt:
      Ist $\lim\ sup_{n\rightarrow\infty}c_n<1$, so ist $\sum^\infty_{n=1}a_n$ absolut konvergent.
      Ist $\lim\ inf_{n\rightarrow\infty}c_n>1$, so ist $\sum^\infty_{n=1}a_n$ divergent.)
    Basic Zusammenfassung: 
    $(a_n)$ ist eine Folge, $c_n:=\left|\frac{a_{n+1}}{a_n}\right|$ und $\alpha:=\lim_{n\rightarrow\infty}c_n$.$\sum^\infty_{n=1}a_n \text{ ist}\begin{cases} \text{absolut konvergent} & \text{falls } \alpha < 1 \\ \text{divergent} & \text{falls } \alpha > 1 \end{cases}$
    Im falle $\alpha=1$ ist keine allgemeine Aussage möglich.
## Definition absolute Konvergenz
***
$\sum^\infty_{n=1}a_n$ heißt absolut konvergent $\iff$ $\sum^\infty_{n=1}\left|a_n\right|$ ist konvergent.

Es sei $\sum^\infty_{n=1}a_n$ absolut konvergent. Dann gilt:
1. $\sum^\infty_{n=1}a_n$ ist konvergent
2. $\left|\sum^\infty_{n=1}a_n\right|\le \sum^\infty_{n=1}|a_n|$ ($\triangle$-Ungleichung für Reihen.)
## Siehe auch
***
* [[Konvergenz von Permutationen von Reihen bzw. Folgen]]
* [[Cauchyprodukt]]
* [[Verknüpfung konvergenter Reihen]]