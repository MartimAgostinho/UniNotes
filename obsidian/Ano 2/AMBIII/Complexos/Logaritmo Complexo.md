

Dizemos que o complexo $w$ é um logaritmo de $z$ se 
$$e^w=z$$
Representamos o conjunto de todos os logaritmos de $z$ por $\log(z)$,
ou seja,$$\log(z)=\{w\in\mathbb C:e^w=z\}.$$
### Exemplo
$$\log(-i)$$
$\log(-i)=w\Leftrightarrow -i=e^w\Leftrightarrow -i=\cos(\theta) + i\sin(\theta)$ 
$\displaystyle \cos(\theta) = 0 \land \sin(\theta) = -1 \Leftrightarrow \theta=-\frac{\pi}{2}$
- portatnto $\displaystyle w=-\frac{\pi}{2}i +2k\pi~~,~~k\in\mathbb Z$


# Ramo principal do logaritmo

Definimos o ramo principal do logaritmo
como a função $Log : \mathbb C \setminus \{0\} → \mathbb C$  com expressão
$$Log (z)=\ln|z|+iArg(z)$$

## Propriedades

Seja $z, w ∈ C \setminus \{0\}$ e $m ∈ \mathbb Z$. 
1. $Re(Log(z)) = \ln |z|$ e $Im(Log(z)) = Arg(z)$ 
2. A função Log é contı́nua em $\mathbb C \setminus R^-_0$.
3. Verificam-se as seguintes igualdades

- $Log(z.w ) = Log(z) + Log(w ) + 2kπi$, para um certo $k ∈ \mathbb Z$.

- $\displaystyle Log \left (\frac{z}{w} \right) = Log(z) − Log(w ) + 2kπi$, para um certo $k ∈ \mathbb Z$.

- $Log(z^m)=mLog(z)+2k\pi i$ ,para um certo $k\in\mathbb Z$   


## Funcao logaritmica

Seja $f(z)~~,~~z\in \mathbb C$ tal que :
$$f(z)=Log(z)$$ $f(z)$ tem continuidade em $\mathbb C\setminus \{Re(z)\leq 0 \land Im(z)=0\}$   

- isto garante que se o numero for real, nao imaginario nao podemos fazer o logaritmo de um numero negativo

#### Exemplo

[[Holomorfismo|Holomorfia]] da funcao $Log(e^z+2)$ 

Esta funcao é holommorfa quando $\mathbb C\setminus \{Re(e^z+2)\leq 0 \land Im(e^z+2)=0\} = \mathbb C \setminus \{ \mathbb R_0^- \}$  

$z=x+yi$
$e^z+2 \leq 0$ - conjunto de numeros onde a funcao nao ]e holommorfa
$e^{x+yi} \leq -2$
$e^xe^{yi}\leq-2 \Leftrightarrow e^x(\cos(y)+i\sin y)\leq-2\Leftrightarrow \sin(y)=0~,~y=k\pi$
$\Leftrightarrow \cos(y)<0~,~y=\pi+2k\pi$
$\Leftrightarrow x\geq \ln(2)$

