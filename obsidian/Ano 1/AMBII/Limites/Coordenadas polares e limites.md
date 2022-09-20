
# [[Coordenadas polares]] e limites

Seja $D$ uma bola centrada em $(a, b) ∈ \mathbb R^2$ de raio $R$ e
$f:D \setminus \{(a,b)\}\to \mathbb R$.

Define-se a função 
$F(r,\theta)=f(a+r\cos \theta,b+r\sin \theta),~~~~(r,\theta)~\in]0,R[\times[0,2\pi[$.

Se o limite semi-direcional $\displaystyle \lim_{r\to0^+}f(r,\theta)$ não existe para algum $\theta \in [0,2\pi[$, ou depende de $\theta$, então o limite 

$\displaystyle \lim_{(x,y)\to(a,b)}f(x,y)$, não existe.

#### Exemplo 
$\displaystyle \lim_{(x,y)\to(0,0)}f(x,y)\iff$

$\iff\displaystyle \lim_{(x,y)\to(0,0)}\frac{x^2}{x^2+y^2}\cos(x^2+y^2)$

$\displaystyle f(x,y)\Rightarrow\frac{r^2\cos^2\theta}{r^2}\cos(r^2)$ *Com o $\theta$ fixo corresponde aos [limites semi-direcionais](Limites%20direcionais.md)*

$\displaystyle \Rightarrow \lim_{r\to0}\frac{\cancel{r^2}\cos^2\theta}{\cancel{r^2}}\cos(r^2)=\cos^2(\theta)$
Como depende do $\theta$ o limite $\displaystyle \lim_{(x,y)\to(0,0)}f(x,y)$ **não existe**.
