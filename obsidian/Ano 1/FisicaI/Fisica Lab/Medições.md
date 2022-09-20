
# Medições

## Propagação da incerteza

Consoante façamos uma ou mais medidas de uma grandeza assim temos associada, respectivamente, uma incerteza de leitura e/ou uma incerteza estatística. Ao utilizar estes valores em cálculos, essas incertezas vão propagar-se.

Seja $Z$ a grandeza em questão, função das variáveis $W1, W2, . . . , Wn$ com incertezas $u(W1), u(W2), . . . , u(Wn)$, respectivamente: 
$~~~~~~~~Z = f(W1, W2,…;Wn)$

Então a incerteza associada a $Z$ pode ser calculada com base na expressão geral de propagação da incerteza:

$\displaystyle u(Z)=\sqrt{\left(\frac{\delta f}{\delta W_1}u(W_1)\right)^2+\left(\frac{\delta f}{\delta W_2}u(W_2)\right)^2+...+\left(\frac{\delta f}{\delta W_n}u(W_n)\right)^2}$


#### Exemplo

Para o cálculo da área de um triângulo temos $\displaystyle A=\frac{b\times h}{2}$:
Admitindo um triângulo com $b=3,0cm~\pm 0,5cm$ e $h=5,00cm~\pm 0,05cm$
Então a incerteza da área do triângulo vai ser:

$\rightarrow f =\displaystyle A=\frac{b\times h}{2}$
$\rightarrow W_1=b$
$\rightarrow W_2=h$
$\rightarrow u(W_1)=u(b)\pm 0,5cm$
$\rightarrow u(W_2)=u(h)\pm 0,05cm$

$\displaystyle u(A)=\sqrt{\left(\frac{\delta A}{\delta b}u(b)\right)^2+\left(\frac{\delta A}{\delta h}u(h)\right)^2}\iff$

$\displaystyle u(A)=\sqrt{\left(\left(\frac{b\times h}{2}\right)'\times0,5\right)^2+\left(\left(\frac{b\times h}{2}\right)'\times0,05\right)^2}\iff$

$\displaystyle u(A)=\sqrt{\left(\frac{h}{2}\times0,5\right)^2+\left(\frac{b}{2}\times 0,05\right)^2}\iff$

$\displaystyle u(A)=\sqrt{\left(\frac{5,00}{2}\times0,5\right)^2+\left(\frac{3,0}{2}\times 0,05\right)^2}\iff$

$u(A)=1,252248$ 

Logo a incerteza da área do triângulo é: $2$
