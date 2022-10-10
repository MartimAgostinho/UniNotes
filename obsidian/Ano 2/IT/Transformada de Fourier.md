# Transformada de [[Analise de Fourier|Fourier]]

Construir uma funcao periodica $g_{T_0}(t)$ de periodo $T_0$,de tal modo que $g(t)$ define um desta nova funcao periodica

$G(f)$ é a transformada de $g(t)$ (??)

$$G(f)=F[g(t)]$$

$Arect(\frac{t}{T})\Leftrightarrow AT~sinc(tT)$  


## Propriedades

### Linearidade 


### Escalar no tempo
$g(at)$ representa $g(t)$ comprimida no tempo pelo fator $a$

### Regra da conjugação

### Dualidade 
$$g(t)= G(f)$$
$$G(t)=g(-f)$$
### Translação no Tempo

$g(t-t_0) = G(f)$

### Area sob $g(t)$
$$\int_{-\infty}^{+\infty}gx(t)dt=G(0)=$$
### Area sob $G(t)$
$$g(0)=\int_{-\infty}^{+\infty}G(f)df$$

### Diferenciacao no dominio do tempo
$$\frac{d^n}{dt^n}g(t)=(j2\pi f)^nG(f)$$
### Integracao no tempo
$$\int_{-\infty}^tg(t)dt=\frac{1}{j2\pi f}G(f)+\frac{G(0)}{2}g(f)$$
### Teorema da coorelação
$g_1\to G_1(f)$     $g_2\to G_2(f)$ 
$$\int_{-\infty}^\infty g_1(t)g_2^*(t-\tau)dt\to G_1(f)G_2^*(f)$$
Em que $G_2^*(f)$ é o [[numeros complexo#Conjugado|complexo conjugado]] de $G_2(f)$ e $\tau$ é a variavel tempo envolvida na definição da TF inversa do produto 

### Teorema da energia
$g(t)\to G(f)$

$$\int_{-\infty}^\infty|g(t)|^2dt=\int_{-\infty}^\infty|G(f)|^2df$$
