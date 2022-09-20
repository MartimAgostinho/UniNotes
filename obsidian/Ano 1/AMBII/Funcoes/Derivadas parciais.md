
# Derivadas parciais

$f:D\subseteq \mathbb R ^2\to \mathbb R$

Vamos fixar $y = b$ e considerar a função
		$\varphi(x) = f (x, b)$
Esta função pode ser derivada no sentido de $\mathbb R$:
			$\displaystyle \lim_{h→0} \frac{f(a + h, b) − f (a, b)}{h}=\frac{\partial f}{\partial x}$

Do mesmo modo
			$\displaystyle \lim_{k→0} \frac{f(a , b + k) − f (a, b)}{k}=\frac{\partial f}{\partial y}$

### Exemplo
$\displaystyle f(x,y)=\left\{ \begin{array}{ll} \frac{xy}{x^2+y^2}~~~~,(x,y)\neq(0,0)\\ 0~~~~,(x,y)=(0,0) \end{array} \right.$

$\displaystyle \frac{\partial f}{\partial x}(0,0)=\lim_{h\to 0}\frac{f(h,0)-f(0,0)}{h}=\lim_{h\to 0}\frac{ \displaystyle\frac{h\times 0}{h^2+0} -0}{h}=0$

$\displaystyle \frac{\partial f}{\partial y}(0,0)=\lim_{k\to 0}\frac{f(0,k)-f(0,0)}{k}=0$

$\displaystyle \frac{\partial f}{\partial x}\left( \frac{xy}{x^2+y^2} \right)=\frac{y^3-x^2y^2}{(x^2+y^2)^2}$ (consideramos $y$ constante)

