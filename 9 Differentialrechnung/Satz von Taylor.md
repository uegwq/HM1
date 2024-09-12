
TARGET DECK
Höhere Mathematik I

Satz von Taylor
--
## Definition
***
Beim Satz von Taylor geht es darum, wie wir Funktionen mit seinen Werten der Ableitung approximieren können. Es ist ziemlich klar, dass wir um einen Punkt $a$ einer Funktion eine relativ gute lokale Annäherung machen können, indem wir die Steigung der Ableitung verwenden. Es gilt also ein bisschen
$f(x,a)=f(a)+f'(a)+(x-a)$. Der Satz von Taylor erweitert dieses Konzept aber wesentlich genauer, indem wir sagen

Es sei $n\in\Bbb N_0$ und $f$ sei auf $I$ $(n+1)$-mal differenzierbar. Es seien $x,x_0\in I$ und $x\not=x_0$. Dann existiert ein $\zeta\in(min\{x,x_0\},max\{x,x_0\}$ mit $$f(x)=f(x_0)+\frac{f'(x_0)}{1!}(x-x_0)+\dots+\frac{f^{(n)}(x_0)}{n!}(x-x_0)^n+\frac{f^{(n+1)}(\zeta)}{(n+1)!}(x-x_0)^{n+1}$$ also $$f(x)=\sum^n_{k=0}\frac{f^{(k)}(x_0)}{k!}(x-x_0)^k+\frac{f^{n+1}(\zeta)}{(n+1)!}(x-x_0)^{n+1}$$
Das geht, weil wir die Funktion mit dem Polynom mit grad $n$ annähern, und dann den Rest mit $\zeta$ addieren.
Wenn n gegen unendlich geht, kann es sein, dass der Restterm gegen null geht. Dann kann man sagen, dass die Funktion gegen die Taylorreihe konvergiert.
  
## Siehe auch
***
* Hier immer spezifischer Werden. Z.b. Abbildung linkt zu arten von Abbildungen und nicht umgekehrt