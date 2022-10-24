# Dirac Delta
Usando funcoes de dirac delta conegue-se: 
- combinar as [[Analise de Fourier|series]] e as [[Transformada de Fourier|transformadas]] numa unica teoria 
- incluir os sinais de potencia no conjunto de sinais para os quais existe [[Transformada de Fourier]]
A função é definida por duas experssões:
$\delta(t)=0$                  $t\neq0$
$$\int_{-\infty}^\infty\delta(t)dt=1$$
É um impulso em $t = 0$ com uma area de 1 nesse ponto


### Propriedade de peneira

$$\int_{-\infty}^\infty g(t)\delta(t-t_0)dt=g(t_0)$$

Como é par, pode se escrever a expressao na forma integral de convolucao
$$\int_{-\infty}^\infty g(t)\delta(t-\tau)d\tau=g(t)$$

### [[Transformada de Fourier]] de $\delta(t)$
$$F[\delta(t)]=1$$

#### Operação inversa
Transformada de um sinal continuo
$$F[1]=\delta(t)$$


