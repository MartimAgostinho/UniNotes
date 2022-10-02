# Campo Eletrico

## Definição
É um campo vétorial ([[AMBII]]), em que cada ponto ($P$) do espaço em torno de uma carga, ou de um conjunto de cargas, está associado a um vetor $\vec E$ definido por: $$\displaystyle \vec E = \frac{\vec F}{q_0}$$ onde $\vec F$ : $$|\vec F| = k\frac{q_0q_1}{d^2}$$
logo: $$\vec E = \frac{ k\frac{q_1q_2}{d^2}}{q_0} \Leftrightarrow k\frac{q_1}{d^2}$$
- $k$ é constante de [[Coulomb]]
- $q_0$ carga no ponto $P$  
- $q_1$ Carga que cria o campo eletrica em questao
- $d$ distância à carga $q_1$ 

## Unidades SI
A unidade SI para o campo elétrico é [[Newton]] por  
[[Coulomb]] ($N/C$)

# Linhas do Campo Elétrico
Conceito criado para visualizar o campo vetorial de um campo eletrico


# Campo Elétrico Devido a um conjunto de particulas

O campo elétrico devido a um conjunto de $n$ cargas é  
dado por:

$$\vec E=\sum_{i=0}^n \vec E_i$$

#### Exemplo . :
![[Pasted image 20221001181641.png]]

O campo elétrico em $P$ é $\vec E = \vec E_1 +\vec E_2 +\vec E_3$

## Conjunto infinito

Quando $n$ tende para $+\infty$ o $\sum$ torna se em $\int$ :
$$\vec E = \int \vec E dE$$  
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

$\displaystyle \Leftrightarrow \vec E=\frac{z\sigma}{4\varepsilon_0}\left[ \frac{ 1 }{-\frac{1}{2} \sqrt{z^2+r^2} } \right]_0^R \Leftrightarrow \vec E= \frac{z\sigma}{4\varepsilon_0}\left( \frac{-2}{\sqrt{z^2+R^2}}-\frac{-2}{\sqrt{z^2}} \right)\Leftrightarrow$ $$\Leftrightarrow \vec E= \frac{\sigma}{4\varepsilon_0}\left( 1-\frac{z}{\sqrt{z^2+R^2}} \right)$$ 
(m8 eu tenho a certeza q o 4 devia ser um 2 cmon)

