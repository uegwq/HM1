
TARGET DECK
Höhere Mathematik I

Differentiationsregeln
--
## Definition
***
Die Funktionen $f,g:I\rightarrow\Bbb R$ seien in $x_0\in I$ differenzierbar. Dann gilt
1. $\alpha f+\beta g$ ist differenzierbar mit $(\alpha f+ \beta g)'(x_0)=\alpha f'(x_0)+\beta g'(g_0)$.
2. $fg$ ist differenzierbar mit $(fg)'(x_0)=f(x_0)g'(x_0)+f'(x_0)g(x_0)$.
3. Ist $g(x_0)\not=0$, so existiert ein $\delta>0$ mit $g(x)\not=0 (x\in J:=I\cap U_\delta(x_0))$. Die Funktion $\frac{f}g:J\rightarrow\Bbb R$ ist differenzierbar in $x_0$ und$$\left(\frac{f}g\right)'(x_0)=\frac{f'(x_0)g(x_0)-f(x_0)g'(x_0)}{g(x_0)^2}$$
4. Es sei $f\in C(I)$ streng monoton, in $x_0\in I$ dfferenzierbar und es sei $f'(x_0)\not=0$. Dann ist $f^{-1}:f(I)\rightarrow\Bbb R$ differenziarber in $y_0=f(x_0)$ und es gilt:
    $(f^{-1})'(y_0)=\frac{1}{f'(x_0)}=\frac{1}{f'(f^{-1}(y_0))}$.
5. Satz 9.4 (Kettenregel): 
   Es sei $J \subseteq \mathbb{R}$ sei ein weiteres Intervall, $g: J \rightarrow \mathbb{R}$ eine Funktion und $f(I) \subseteq J$. Weiter sei $f$ in $x_0 \in I$ differenzierbar und $g$ sei in $y_0 := f(x_0)$ differenzierbar. Dann ist
   $g \circ f: I \rightarrow \mathbb{R}$ differenzierbar in $x_0$ mit
   $(g\circ f)'(x_0)=g'(f(x_0))f'(x_0)$.
6. Satz (9.12) Potenzreihen
   Es sei $f(x)=\sum^\infty_{n=0}a_n(x-x_0)^n$ eine Potenzreihe mit Konvergenzradius $r>0$. Es gilt, dass:
   1. Die Potenzreihe $\sum^\infty_{n=1}na_n(x-x_0)^{n-1}$ hat auch den Konvergenzradius r und
   2. $f$ ist auf seinem Konvergenzradius differenzierbar und die Reihe von $1.$ ist seine Ableitungsfunktion.
7. Sinus, Cosinus
   Nach 6. ist Sinus (weil es eine Potenzreihe ist) differenzierbar und es gilt:$$(\sin x)'=(\sum^\infty_{n=0}(-1)^n\frac{x^{2n+1}}{(2n+1)!})'=\sum^\infty_{n=0}(-1)^n\frac{(2n+1)(x^{2n})}{(2n+1)!}=\sum^\infty_{n=0}(-1)^n\frac{x^{2n}}{(2n)!}=\cos x$$

## Siehe auch
***
* Hier immer spezifischer Werden. Z.b. Abbildung linkt zu arten von Abbildungen und nicht umgekehrt