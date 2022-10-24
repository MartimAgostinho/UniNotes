as **[[Series de Fourier]]** $\to$ função periódica com o período $T_0$ 

[[Séries]] 
# Analise de Fourier

$$g_p(t)=a_0+2\sum_{n=1}^{\infty}\left[ a_n \cos\left (\frac{2\pi nt}{T_0}\right)+b_n\sin\left (\frac{2\pi nt}{T_0}\right) \right] \Leftrightarrow$$
$$\displaystyle \Leftrightarrow g_p(t)=\sum_{n=-\infty}^{\infty}c_n\times \exp\left(\frac{j2\pi nt}{T_0}\right)$$
em que $c_n$ é o **coeficiente complexo de Fourier** :
### $C_n$
$$c_n =\frac{1}{T}\int_{I_0}^{I_1} g_p(t)\exp\left(-\frac{j2\pi nt}{T}\right)dt \Longleftrightarrow$$ $$c_n =\Delta f\int_{I_0}^{I_1} g_p(t)\exp\left(-j 2\pi  f_n t\right)dt \Longleftrightarrow$$
$$c_n=\frac{A}{n\pi}\sin \left( \frac{n\pi T}{T_0} \right)$$

$T_0 =$ tempo do impulso
$T=$periodo
$I_0$ inicio do impulso
$I_1$ fim do impulso
extremos da integral sao do inicio do impulso ao fim
$g_p(t)=$amplitude* 

$\displaystyle \frac{2\pi nt }{T} = 2\pi f_n t,n\in \mathbb N$, $f_n$ sao harmónica de ordem $n$ da frequência fundamental, e $\displaystyle f =\frac{1}{T}$ onde $T$ é o periodo.     

$c_n=|c_n|\exp(j\times arg(c_n))$
$c_{-n}=c^*_n$ 
em que $c^*_n$  ]e o complexo conjugado de $c_n$ Tem se entao 
$|c_{-n}|=|c_n|$

## Igualdades

$$\cos(a)=\frac{1}{2}\left[ \exp(ja) + \exp(-ja) \right]$$

$$\sin(a)=\frac{1}{2j}\left[ \exp(ja) - \exp(-ja) \right]$$



# Funcao sinusoidal
$$\cos(2\pi f_ct)\to\frac{1}{2}\left[ \delta(f-f_c)+\delta(f+f_c) \right]$$
Isto é o espetro de uma funcao coseno consiste num par de funcoes delta centradas em $f=\pm f_{c}$ cada uma pesada por um fator de $\frac{1}{2}$ 

$$\sin(2\pi f_ct)\to\frac{1}{2}\left[ \delta(f-f_c)-\delta(f+f_c) \right]$$
