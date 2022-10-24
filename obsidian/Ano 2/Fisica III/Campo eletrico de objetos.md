# Campo eletrico de objetos
### Anel 
![[Pasted image 20221001184431.png|150]]
- $dq=\lambda ds$ onde $\lambda$ é a distribuição linear da carga
- Tratando o elemento como uma carga  pontual, tem-se: $$dE = k\frac{dq}{r^2}=k\frac{\lambda ds}{\sqrt {z^2 + R^2}}$$
- Porque o anel é homogéneo e simetrico $\vec F$ só tem componente em $z$ 
- A componente da forca no eixo $OZ = dE\cos \theta$   

- $\displaystyle k\frac{\lambda ds}{\sqrt {z^2 + R^2}}\cos\theta = k\frac{\lambda ds}{\sqrt {z^2 + R^2}}\frac{z}{\sqrt {z^2 + R^2}}= k\frac{\lambda z}{ \left(z^2 + R^2\right)^{\frac{3}{2}}}ds$ 

- O campo elétrico total é dado pela  integração ao longo de todo o anel $$\vec E=\oint dE\cos \theta=k\frac{\lambda z}{ \left(z^2 + R^2\right)^{\frac{3}{2}}}\oint ds=k\frac{\lambda z( 2\pi R)}{ \left(z^2 + R^2\right)^{\frac{3}{2}}}$$
 - Com $q=\lambda(2\pi R)$ o campo eletrico gerado num anel de carga é dado por :$$\vec E =k\frac{qz}{ \left(z^2 + R^2\right)^{\frac{3}{2}}}$$
### Disco
![[Pasted image 20221001190638.png|150]] 
- Assumindo que um disco é uma soma infinita de aneis...
- O disco de raio $R$ na figura tem uma superfície carregada uniformemente com uma densidade de carga $\sigma$.
-  $dq=\sigma dA=\sigma (2\pi rdr)$
- $$\vec E =k\frac{qz}{ \left(z^2 + R^2\right)^{\frac{3}{2}}},~~~q=\sigma(2\pi rdr)\Leftrightarrow$$
$$\Leftrightarrow dE=k\frac{z\sigma\times2\pi r}{ \left(z^2 + r^2\right)^{\frac{3}{2}}}dr\Leftrightarrow,k=\frac{1}{4\pi\varepsilon_0}$$[[Coulomb]] 

$\displaystyle\Leftrightarrow \vec E=\int_0^R \frac{z\sigma\times2\cancel\pi r}{ 4 \cancel \pi\varepsilon_0\left(z^2 + r^2\right)^{\frac{3}{2}}}dr \Leftrightarrow \vec E=\frac{z\sigma}{4\varepsilon_0}\int_0^R 2r\left( z^2+r^2 \right)^{-\frac{3}{2}}dr\Leftrightarrow$

$\displaystyle \Leftrightarrow \vec E=\frac{z\sigma}{4\varepsilon_0}\left[ \frac{ 1 }{-\frac{1}{2} \sqrt{z^2+r^2} } \right]_0^R \Leftrightarrow \vec E= \frac{z\sigma}{4\varepsilon_0}\left( \frac{-2}{\sqrt{z^2+R^2}}-\frac{-2}{\sqrt{z^2}} \right)\Leftrightarrow$ $$\Leftrightarrow \vec E= \frac{\sigma}{2\varepsilon_0}\left( 1-\frac{z}{\sqrt{z^2+R^2}} \right)$$ 



### Exercicio 18

![[Pasted image 20221004232640.png]]

- a) como é uma linha $\lambda=$ carga/unidade de medida $$\lambda = \frac{Q}{\pi r}$$

- b) Como há simetria no eixo $x$ a força **não** tem componente no eixo $y$ 

- c) Sendo $ds$ uma divisao infinitamente pequena da circunferencia  $$\vec E = \int k\frac{ds\lambda}{a^2}$$ mas como só queremos a componente no $x$ $$\vec E = \int k\frac{ds\lambda}{a^2}\cos \alpha$$
- $ad\alpha = ds$ por definição de radianos (ver este ponto)
- Os extremos são os valores de $\alpha$ $$\vec E = \int_{-\frac{\pi}{2}}^{\frac{\pi}{2}} k\frac{\cancel a\times\lambda}{a^{\cancel2}}\cos \alpha ~d\alpha\Leftrightarrow$$
- $$\Leftrightarrow \vec E=\frac{k\lambda}{a}\left[ sin(\alpha) \right]_{-\frac{\pi}{2}}^{-\frac{\pi}{2}}\Leftrightarrow$$
- $$\Leftrightarrow \vec E=\frac{2k\lambda}{a}$$
