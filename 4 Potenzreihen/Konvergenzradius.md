
TARGET DECK
Höhere Mathematik I

Konvergenzradius
--
## Definition
***
Es sei $\sum^\infty_{n=0}a_n(x-x_0)^n$ eine Potenzreihe. Wir setzen$$\rho:=\begin{cases}  \infty & \text{falls } (\sqrt[n]{\left|a_n\right|}) \text{ unbeschränkt} \\ \text{lim sup}_{n\rightarrow\infty}\sqrt[n]{\left|a_n\right|} & \text{falls } (\sqrt[n]{\left|a_n\right|}) \text{ beschränkt} \end{cases}$$und$$r=\begin{cases}0, & \text{falls }\rho=\infty \\ \infty, & \text{falls }\rho=0 \\ \frac{1}{\rho}, &\text{falls } \rho\in(0,\infty)\end{cases}$$r heißt der Konvergenzradius der Potenzreihe.
## Alternative Definition über Quotientenkriterium
***
Es sei $\sum^\infty_{n=0}a_n(x-x_0)^n$ wieder eine Potenzreihe. Wenn jetzt die Folge $\left(\frac{a_n}{a_{n+1}}\right)$ konvergent ist, dann ist der Konvergenzradius von der Potenzreihe $L=\lim_{n\rightarrow\infty}\left|\frac{a_n}{a_{n+1}}\right|$. :)
Macht sinn wenn man kurz denkt okay wenn ich die Folgeglieder der Potenzreihe wie im Wurzelkrit durcheinander Teile dann kürzt sich da voll viel weg und im Exponenten bleibt $\frac{1}{x-x_0}$ und davor steht halt dann das $L$. Und insgesamt konvergiert die ganze Reihe wenn das jetzt kleiner als 1 ist, und das ist es nur, wenn der Abstand zwischen $x$ und $x_0$ größer ist als $L$ :=| no makes no sense
## Bedeutung
***
1. Ist der Konvergenzradius $r$ einer Potenzreihe 0, so konvergiert sie nur für $x=x_0$
2. Ist $r=\infty$, so konvergiert die Potenzreihe für jedes $x\in\Bbb R$.
3. Ist $r\in(0,\infty)$, so konvergiert die Potenzreihe absolut für jedes $x\in\Bbb R$, welches einen Abstand weniger als $r$ von $x_0$ hat. Für die Randfälle ist keine allgemeine Aussage möglich. ![[Pasted image 20240403171405.png]]
## Siehe auch
***
* Hier immer spezifischer Werden. Z.b. Abbildung linkt zu arten von Abbildungen und nicht umgekehrt