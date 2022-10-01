![[Pasted image 20220927134300.png]]

[[Analise de Fourier]]

dados: $T_0 = 1$
$\displaystyle  c_n =\frac{1}{T_0}\int_{-\frac{T_0}{2}}^{\frac{T_0}{2}} g_p(t)\exp\left(-\frac{j2\pi nt}{T_0}\right)dt \Leftrightarrow$

$\displaystyle \Leftrightarrow c_n =\frac{1}{2}\int_{0}^{1} \exp\left(-\frac{j2\pi nt}{2}\right)dt \Leftrightarrow$

$\Leftrightarrow \displaystyle \frac{1}{2}\left[ \frac{\exp\left( \frac{-j\cancel2\pi}{\cancel2}\right)}{j2\pi nt} \right]_0^1 \Leftrightarrow$

$\Leftrightarrow \displaystyle \frac{1}{2}\left[ \frac{\exp\left( -j\pi\right)}{j2\pi n} -\frac{\exp\left( -j\pi\times 0\right)}{j2\pi n} \right] \Leftrightarrow$


$\displaystyle \Leftrightarrow \frac{\exp(-j\pi n) - 1}{-j2\pi n}$


$\displaystyle \Leftrightarrow \frac{\exp\left(\frac{-j\pi n}{2}\right) \left( \exp\left(-j\pi n +\frac{j\pi n}{2} \right) - \exp\left(\frac{j\pi n}{2} \right) \right)}{j2\pi n}$ 

$\displaystyle \Leftrightarrow \frac{ \exp\left(- \frac{j\pi n}{2} \right) - \exp\left(\frac{j\pi n}{2} \right) }{j2\pi n\times\exp\left(\frac{j\pi n}{2}\right) }$   como:  $\displaystyle \sin(a)=\frac{1}{2j}\left[ \exp(ja) - \exp(-ja) \right]$ ,([[Sinc]]) entao:

$\displaystyle \Leftrightarrow \frac{\sin\left( \frac{\pi n}{2} \right)}{\pi n\times\exp\left(\frac{j\pi n}{2}\right)}$

$\displaystyle \Leftrightarrow \frac{sinc\left( \frac{\pi n}{2} \right)}{2\exp\left(\frac{j\pi n}{2}\right)}$ 


