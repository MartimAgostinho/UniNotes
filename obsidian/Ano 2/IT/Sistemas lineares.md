# Principio da sobreposicao 

- é a soma das respostas unitarias
###### Resposta a um input continuo
- é a soma infinita dos impulsos, torna-se num integral

$$\displaystyle y(t)=\int_{-\infty}^{\infty}x(\tau)h(t - \tau )d\tau$$


$h(t)=0,t<0$ - é [[Filtros#Sistemas nao causais|causal]] 
- A resposta impulsica do filtro tem duração finita
$h(t)=0,t>T_f$
A resposta do filtro a uma excitação $x(t)$ 
$$y(t)=\int_0^{T_f} h(\tau)x(t-\tau)d\tau$$
Se
- I)    $x(t)$ é a entrada
- II)   resposta impulsiva $h(t)$
- III)  a saida $y(t)$
$\displaystyle \frac{1}{\Delta\tau}\to$ frequencia de amostragem 
