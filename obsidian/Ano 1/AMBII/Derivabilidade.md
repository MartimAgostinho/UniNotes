
# Derivabilidade
$f:D\subseteq\mathbb{R}\longrightarrow\mathbb{R}^n$ , $D$ aberto, $a \in D$

Então $f$ é derivável em $a$ se existirem $f'_i(a)$  para que todo o $i\in \{1,...,n\}$
Se $f$ for diriv]avel em $a$, definimos $f'(a)=(f'_1(a),...,f'_n(a))$

## Exemplo
$\displaystyle {f(t)=\left(~\frac{\sin t}{t}~,~\sqrt{|~t~|}~,~t~\right)}$

$\displaystyle f_1(t)=\frac{\sin t}{t}~,~f'_1(t)=\frac{t(\cos t)-\sin t}{t^2}$ 

$\displaystyle f_2(t)=\left\{   \begin{array}{ll} \sqrt{t} & ,t>0 \\ \sqrt{-t} & ,t<0\end{array}  \right.~,$  $\displaystyle f_2'(t)=\left\{   \begin{array}{ll} \frac{1}{2\sqrt{t}} & ,t>0 \\ -\frac{1}{2\sqrt{-t}} & ,t<0\end{array}  \right.$  

$f_3=t~,~f'_3=1$

Portanto 

$\displaystyle f'(t)=\left( \frac{t(\cos t)-\sin t}{t^2}~,\left\{   \begin{array}{ll} \frac{1}{2\sqrt{t}} & ,t>0 \\ -\frac{1}{2\sqrt{-t}} & ,t<0\end{array}  \right.~,~1 \right)$
