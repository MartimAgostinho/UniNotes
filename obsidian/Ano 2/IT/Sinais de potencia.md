# Sinais de potencia

Sinais infinitos no tempo

### Exemplo

- sinais periodicos 1
- White noise
- Sinais digitais

$g(t)$ ]e um sinal finito quando $t\to\infty$ 

## Potencia media

$$P_x=\lim_{t\to\infty}\frac{1}{2T_0}\int_{-T_0}^{T_0}|x(t)|^2dt$$

$\displaystyle x_{T_0} = x(t)$ quando $-T_0\leq t \leq T_0$ 
$\displaystyle x_{T_0} = 0$ nos restantes casos

Por definicao
$\displaystyle x(t) = \lim_{T_0\to \infty}x_{T_0}(t)$

A expressao de potencia media 

$$P_x=\lim_{T_0\to\infty}\frac{1}{2T_0}\int_{-\infty}^{\infty}|x_{T_0}(t)|^2dt$$

Enquanto ${T_0}$ for finito $x_{T_0}$ tem energia finita e tem [[Transformada de Fourier]] 
Fazendo uso do teorema

$$\int_{-\infty}^{\infty}|x_{T_0}(t)|^2dt=\int_{-\infty}^{\infty}|X_{T_0}(f)|^2df$$

## Densidade espetral de Potencia

$$S_x = \lim_{T_0\to\infty}\left[ \frac{1}{2{T_0}}|X_{T_0}(f)|^2 \right]$$

### Potencia media
$$P_x=\int_{-\infty}^{\infty}S_x(f)df$$
$$P_x=R_x(0)$$

(CORRELACAO ?!! VER ESTUDAR E CRIAR APONTAMENTO)


#### Exemplo

$x(t)=A\cos(2\pi f_ct+\theta)$

$\displaystyle R_X=\frac{A^2}{T_0}\int_0^t\cos(2\pi f_c\tau+\theta)\cos(2\pi f_c(t-\tau)+\theta)dt=$

$\displaystyle = \frac{A^2}{T_0}\int_0^t\cos(2\pi f_c\tau) + \cos(2\pi f_c(2t-\tau)+2\theta)=$
$\displaystyle = R_x=\frac{A^2}{T_0}\cos(2\pi f_c\tau)$
