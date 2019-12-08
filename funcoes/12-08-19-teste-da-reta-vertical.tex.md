# Teste da reta vertical


Seja uma curva definida no plano $x$ $y$,a curva irá representar uma função se, somente se, nenhuma reta vertical cortar a curva em mais de um ponto.

O teste da reta vertical implica que função $f(x)$ observada junto a reta $x=a$ irá resultar em um único ponto $f(a)=b$, ou seja, interceptará a curva somente em $(a, f(a))$, caso contrário a curva não representa uma função.

![função e não função](./res/funcao-nao-funcao.png)

**(1)** Qualquer reta vertical intercepta a curva em um único ponto, ou seja, **(1)** representa uma função

**(2)** Por usa vez, existem múltiplos pontos de intercepção $x=a$, ou seja, a curva **(2)** não representa uma função.

**EX:** verificar quais curvas a seguir representam funções.

![funcão q1](./res/funcao-q1.png)

É uma função

![não funcão q2](./res/funcao-q2.png)

não é uma função

![funcão q3](./res/funcao-q3.png)

É uma função

# Representar os pontos e intervalos

Existem diversas formas de representar intervalos e pontos, vamos relembrar algumas dessas formas.

- **Intervalo fechado:** Consiste em uma região numérica limitada a dois pontos extremos, inclusive é representado por colchetes ou intervalos de reta com extremos fechados.


**EX:** $[-1, 1]$ é o intervalo fechado limitado aos valores $-1$ e $1$, inclusive representado em reta da seguinte forma:

![intervalo fechado](./res/intervalo-fechado.png)

Note que -1 e 1 pertencem ao intervalo $I$

- **Intervalo aberto:** regiao numérica similar ao intervalo fechado, porém seus extremos não estão inclusos no intervalo, representado por parenteses, $(-1, 1)$

**EX:** é um intervalo $I$ que contém todos os números reais entre $-1$ e $1$, exceto os próprios $-1$ e $1$.

![intervalo aberto](./res/intervalo-aberto.png)

Note que $-1, 1 \notin I$

- **Intervalo semiaberto:** intervalo que contém um de seus extremos, mas não contém o outro.

**EX:** (-1, 1], a parte inclusiva é denotada por colchetes e a não inclusa por parenteses.

![intervalo semiaberto](./res/intervalo-semiaberto.png)

Note que $-1 \lt x \le  1$

- **Intervalos descontínuos:** quando existem um ou mais pontos a dentro do intervalo $I$, tal que $d \notin I$. É representado por uma restrição explicita.

$$x \in I | x \ne a$$

- **EX** intervalo $I = [-1, 1]$ porém excluindo zero.

$$\{x \in [-1, 1] | x \ne 0\}$$

**EXEMPLOS**
- a) $[-1, 1) = [-1, 1[$ 
- b) $(-1, 1] = ]-1, 1]$
- c) $(-1, 1) = ]-1, 1[$
- d) $[-\xcancel\infty, 1] = (-\infty, 1]$
- e) $[-1, \xcancel\infty] = [-1, \infty)$

# Representações de funções na forma álgebrica

Em geral é inviável ou ineficaz representar uma função na forma gráfica. Por esse motivo, opta-se por realizar uma representação algébrica de uma  função, como a seguir:

- a) $f(x) = ax + b$, $a$ e $b$ são números reais.
- b) $f(x) = \sin(x)$, $\cos(x)$, $\tan(x)$
- c) $f(x) = \sqrt x$
- d) $f(x) = \frac{1}{x}$

**OBS:** note que algumas dessas funções podem não estar definidas para algum(ns) números reais.

# Funções definidas por partes

São funções que são definidas algebricamente de maneira diferente para um ou mais intervalos. Uma função definida por partes não precisa ser continua.

**EX:** $f$ é definida por partes tal que:

$$
f(x) = 
	\begin{cases}
	 1-x, x \le -1 \\
	 x^2, -1 > x
	 \end{cases}
$$

**EX:** a função módulo é, ou valor absoluto é definida por partes da seguinte maneira:

$$
f(x) = |x| = \begin{cases}
	x, x \ge 0 \\
	-x, x < 0
	\end{cases}
$$
