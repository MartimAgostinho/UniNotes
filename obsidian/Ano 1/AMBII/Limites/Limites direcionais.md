
# Limites direcionais

Consideramos [[Curvas]] que são retas passando em $(a,b)$ [[Parametrização]] de uma retas passando em $(a,b)$

$y=m(x-a)+b,m\in\mathbb R$
$\vec r(x)=(x~,~m(x-a)+b),x\in\mathbb R$

Outra reta passando em $(a,b)$ é a reta $x=a$ que tem a [[Parametrização]]:

$\vec r(y)=(a,y)$

### Exemplo
##### Alguns limites direcionais

$\displaystyle f(x,y)=-\frac{xy}{x^2+y^2}$


Vamos calcular os limites direcionais, ou seja, o limite ao longo das retas que passam no ponto $(0,0)$.

$\displaystyle \lim_{(x,y)\to(0,0)}\left( -\frac{xy}{x^2+y^2} \right),y=mx$ **Nota quando $y=mx$ temos de provar que para $x=0$ há limite**

$\Rightarrow\displaystyle \lim_{x\to0}\left( -\frac{mx^2}{x^2+m^2x^2} \right)=\lim_{x\to0}\left( -\frac{m}{1+m^2} \right)$


$\bullet \displaystyle \lim_{(x,y \to (0,0))}f(x,y)$,   $x=0\iff$
$\displaystyle \iff \lim_{y \to 0}-\frac{0}{y^2}=0$
Este limite representa o limite ao longo da reta x = 0 

$\bullet \displaystyle \lim_{(x,y \to (0,0))}f(x,y)$,   $y=0\iff$
$\displaystyle \iff \lim_{x \to 0}-\frac{0}{x^2}=0$
Este limite representa o limite ao longo da reta y = 0 

$\bullet \displaystyle \lim_{(x,y \to (0,0))}f(x,y)$,   $x=y\iff$
$\displaystyle \iff \lim_{x \to 0}-\frac{x\times x}{x^2+x^2}=\lim_{x \to0}-\frac{\cancel {x^2}}{2\cancel {x^2}}=-\frac{1}{2}$
Este limite representa o limite ao longo da reta x = y

$\bullet \displaystyle \lim_{(x,y \to (0,0))}f(x,y)$,   $y=-x\iff$
$\displaystyle \iff \lim_{x \to 0}-\frac{x\times -x}{x^2+x^2}=\lim_{x \to0}\frac{\cancel {x^2}}{2\cancel {x^2}}=\frac{1}{2}$
Este limite representa o limite ao longo da reta y = -x

###### Conclusão 
Não há limite de $f(x,y)$ em $(x,y)\to(0,0)$