
Seja $D ⊂ \mathbb C$ e $f : D →  \mathbb C$. Suponhamos que $f$ é  $\mathbb C$-derivável em $z_0$ . Então existe função complexa de variável complexa $ε$ tal que $\lim ε(h) = 0$ e:

$$f(z_0+h)=f(z_0)+f'(z_0).h+|h|\varepsilon(h)$$ Seja:

- $z = x + iy ;$
- $z_0 = x_0 + iy_0 ;$
- $f' (z_0 ) = a + ib$;
- $h = h_1 + ih_2 ;$
- $f (z) = f (x + iy ) = u(x, y ) + iv (x, y );$
- $ε(h) = ε(h_1 + ih_2 ) = ε_1 (h_1 , h_2 ) + iε_2 (h_1 , h_2 ).$

Através da identificação $z → (Re(z), Im(z))$, a igualdade $$f(z_0+h)=f(z_0)+f'(z_0).h+|h|\varepsilon(h)$$é equivalente à igualdade matricial
$$\left[{\begin{array}{cc}
u(x_0+h_1~, ~y_0+h_2)\\
v(x_0+h_1~,~ y_0+h_2)\\
\end{array}}\right] = 
\left[{\begin{array}{cc}
u(x_0~,~ y_0)\\
v(x_0~,~ y_0)\\
\end{array}}\right]+
\left[{\begin{array}{cc}
a~-b\\
b~~~~~a\\
\end{array}}\right].\left[{\begin{array}{cc}
h_1\\
h_2\\
\end{array}}\right]+||(h_1,h_2)||
\left[{\begin{array}{cc}
\varepsilon(h_1~,~ h_2)\\
\varepsilon(h_1~,~ h_2)\\
\end{array}}\right]$$

Da definição de $R^2$-diferenciabilidade em $(x_0 , y_0 )$ obtemos
$$\left[{\begin{array}{cc}
a~-b\\
b~~~~~a\\
\end{array}}\right]=J_{(u,v)}(x_0,y_0)=
\left[{\begin{array}{cc}
\frac{\partial u}{\partial x}(x_0~,~ y_0)&\frac{\partial u}{\partial y}(x_0~,~ y_0)\\
\frac{\partial v}{\partial x}v(x_0~,~ y_0)&\frac{\partial v}{\partial y}v(x_0~,~ y_0)\\
\end{array}}\right]$$
($J_{(u,v)}(x_0,y_0)$ é a [[Matriz Jacobiana]])

## Conclusao

Como tal, $f = u + iv$ tem de verificar as condições de **Cauchy-Riemann** no ponto $x_0 + iy_0$ definidas pelas igualdades:

$$\left\{ \begin{array}{cc} 
\frac{\partial u}{\partial x}(x_0~,~ y_0)=\frac{\partial v}{\partial y}(x_0~,~ y_0)\\
\frac{\partial u}{\partial y}(x_0~,~ y_0)=-\frac{\partial v}{\partial x}(x_0~,~ y_0)
\end{array}\right.$$
Verifica 