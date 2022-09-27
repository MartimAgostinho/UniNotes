as **[[Series de Fourier]]** $\to$ função periódica com o período $T_0$ 


# Analise de Fourier

$$g_p(t)=a_0+2\sum_{n=1}^{\infty}\left[ a_n \cos\left (\frac{2\pi nt}{T_0}\right)+b_n\sin\left (\frac{2\pi nt}{T_0}\right) \right] \Leftrightarrow$$
$$\displaystyle \Leftrightarrow g_p(t)=\sum_{n=-\infty}^{\infty}c_n\times e^{\frac{j2\pi nt}{T_0}}$$
em que $c_n$ é o **coeficiente complexo de Fourier** :$$c_n =\frac{1}{T}\int_{I_0}^{I_1} g_p(t)\exp\left(-\frac{j2\pi nt}{T}\right)dt \Longleftrightarrow$$ $$c_n =\Delta f\int_{I_0}^{I_1} g_p(t)\exp\left(-j 2\pi  f_n t\right)dt \Longleftrightarrow$$ $T_0 =$ tempo do impulso
$T=$periodo
$I_0$ inicio do impulso
$I_1$ fim do impulso
extremos da integral sao do inicio do impulso ao fim
$g_p(t)=$amplitude* 

$\displaystyle \frac{2\pi nt }{T_0} = 2\pi nf\times t,n\in \mathbb N$, $nf$ sao harmónica de ordem n da frequência fundamental, e $\displaystyle f =\frac{1}{T}$ onde $T$ é o periodo.     

## Igualdades

$$\cos(a)=\frac{1}{2}\left[ \exp(ja) + \exp(-ja) \right]$$

$$\sin(a)=\frac{1}{2j}\left[ \exp(ja) - \exp(-ja) \right]$$