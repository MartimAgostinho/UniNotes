
# Limite segundo Cauchy

Seja $D\subset \mathbb R^2$ um conjunto e $f:D\to\mathbb R,~~~(x_0,y_0)\in D'$

###### Atenção não é pedido que $(x_0,y_0)\in D$.

Dizemos que:

$\displaystyle \lim_{(x,y)\to(x_0,y_0)}f(x,y)=L$

Se e só se 

$\displaystyle \forall \varepsilon > 0, ~~\exists \delta>0:|| (x,y)-(a,b) ||<\delta\Rightarrow|f(x,y)-L|<\varepsilon$

$\displaystyle || (x,y)-(a,b) || = \sqrt{(x-a)^2+(y-b)^2}$

#### Exemplo 
##### Mostrar usando a definição segundo Cauchy que:
##### $\displaystyle \lim_{(x,y)\to(0,0)}\frac{3x^3-2x^3}{2x^2+y^2}=0$ 

Temos que provar que $\displaystyle \forall \varepsilon > 0, ~~\exists \delta>0:|| (x,y)-(0,0) ||<\delta\Rightarrow|f(x,y)-0|<\varepsilon$

Seja $\varepsilon>0$.
$\displaystyle \left| \frac{3x^3-2x^3}{2x^2+y^2} -0\right|=\frac{\left|3x^3-2y^3\right|}{2x^2+y^2}\leq\frac{3|x|^3+2|y|^3}{2x^2+y^2}$

$\displaystyle \leq\frac{3\left( \sqrt{x^2+y^2} \right)^3+2\left( \sqrt{x^2+y^2} \right)^3}{2x^2+y^2},~~2x^2+y^2\geq x^2+y^2$ logo $\displaystyle \frac{1}{2x^2+y^2}\leq\frac{1}{x^2+y^2}$

$\displaystyle \leq\frac{3\left( \sqrt{x^2+y^2} \right)^3+2\left( \sqrt{x^2+y^2} \right)^3}{x^2+y^2}=5\sqrt{x^2+y^2}$

$\displaystyle || (x,y)-(0,0) ||<\delta \iff ||(x,y)||=\sqrt{x^2+y^2}<\delta$

$5\sqrt{x^2+y^2}<5\delta$

fazendo $\displaystyle\delta=\frac{\varepsilon}{5},$ obtemos $\sqrt{x^2+y^2}<\delta\Rightarrow|f(x,y)-0|<\varepsilon$

$\displaystyle \lim_{(x,y)\to(0,0)}f(x,y)=0$ 

