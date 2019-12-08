


> **Notas de aula por Francisco Hartur Lopes de Alcântara**
> **Prof. Marciel Barros**
> **Disciplina: Cálculo Diferencial e Integral I**
> **Universidade Federal do Ceará - Campus Crateús**

CÁLCULO DIFERENCIAL E INTEGRAL I
=
Derivadas de Funções Polinomiais

Vamos iniciar a avaliação de Derivada de funções de caracteristicas polinomiais. Para tal, tomamos inicialmente uma função constante f(x) = c.

Definição: Seja f uma função real ou real ou vizinhança de um ponto x = a. Dizemos que D = $\displaystyle{\lim_{h \to 0}}\frac{f(x+h)-f(x)}{h}$ é a derivada da função f no ponto x = a.

D é a representação pela notação f'(x) (lê-se f_linha de a). A derivada é, normalmente, representada na forma da função substituindo-se, a por x, ou seja:
D = f'(x) = $\displaystyle{\lim_{h \to 0}}\frac{f(x+h)-f(x)}{h}$ "Notação de Leibriz"
em todos os pontos onde existir o limite.

## Derivada da função constante

Seja f(x) = c, uma função constante, consequentemente, contínua para todo $x \in R$ A derivada de uma função constante é obitida a partir da aplicação no limite, também denominado "Notação de leibriz" ou seja:

$$ D f(x)= f'(x) = \displaystyle{\lim_{h \to 0}}\frac{f(x+h)-f(x)}{h} \ \ "Notação \ de \ Leibriz"$$

Uma vez que f(x) = f(x+h) = c, tem-se:
$$ f'(x) = \displaystyle{\lim_{h \to 0}}\frac{c -c}{h} =0$$
A derivada de uma função constante é igual a zero.

Ex.: Utilizar o conceito de derivada para determinar a derivada de uma função quadrática f(x) = x².

<p align="center">
  <img width="560" height="300" src="https://i.imgur.com/1KWmxSX.png">
</p>

Generalização: funções potência. sabendo que f(x) = x² -> f'(x) = 2x, vamos analisar os demais casos:

(1) f(x) = x -> f'(x) = 1
Prova: $\displaystyle{\lim_{h \to 0}}\frac{x+h-x}{h} = \displaystyle{\lim_{h \to 0}}\frac{h}{h} = 1$

(2) f(x) = x³ -> f'(x) = 3x²
Prova: $\displaystyle{\lim_{h \to 0}}\frac{(x+h)³ - x³}{h} = \displaystyle{\lim_{h \to 0}}\frac{x³+3x²h+h³-x³}{h} = \displaystyle{\lim_{h \to 0}}  \ {3x³+3xh+h²}$

Dessa forma, podemos demonstrar que, para uma função potência genérica f(x) = $x^{h}$, sua deriva será:
$$f'(x) = n\cdot x^{n-1}$$

Expoentes negativos ou fracionários

Regra geral: se n for um número real qualquer, tem-se que:
$$f(x)=x^{h} \longrightarrow f'(x) = n\cdot x^{n-1}$$

$Ex_{1}: f(x) =\frac{1}{x²} \longrightarrow \ f'(x)=\frac{-2}{x³}$

$Ex_{2}: f(x) =\sqrt[3]{x²} \longrightarrow \ f'(x) = \frac{2}{3}\cdot x^{\frac{-1}{3}}$

Novas derivadas apartir de conhecidas:

Sejam f(x) e g(x) funções DERIVÁVEIS, ou seja, o limite $\displaystyle{\lim_{h \to 0}}\frac{f(x+h)-f(x)}{h}$ existe para ambas então:

1. Regra da multiplicação por escalar:
$$c \in R \longrightarrow [c \cdot f(x)]' = c \cdot f'(x)$$
A derivada de $c \cdot f(x)$ equivale a c vezes a derivada $f'(x)$
2. Regra da adição/subtração
$$[f(x)+g(x)]' = f'(x) + g'(x)$$
$$[f(x)-g(x)]' = f'(x) - g'(x)$$

Exemplo: Determinar, por notação de leibriz, as derivadas a seguir:

a) f(x) = 3x³- 4x² $\longrightarrow$ f'(x) = ?

**Solução:**
<p align="center">
  <img width="560" height="300" 	src="https://i.imgur.com/gDUnZso.png">
</p>


## Derivadas de funções exponencias
Vamos observar o comportamento da função derivada de uma exponencial, utilizando a notação de LEIBNIZ:
$\ \ \ \ f(x) = a^{x} ;a \in R$

$f'(x) = \displaystyle{\lim_{h \to 0}}\frac{f(x+h)-f(x)}{h} = \displaystyle{\lim_{h \to 0}}\frac{a^{x+h}-a^{x}}{h} = \displaystyle{\lim_{h \to 0}}\frac{a^{x}\cdot a^{h}-a^{x}}{h} = \displaystyle{\lim_{h \to 0}}\frac{a^{x}\cdot (a^{h}-1)}{h}$

O termo $a^{h}$ não depende de h, portanto:

$f'(x) = a^{x}\cdot[ \displaystyle{\lim_{h \to 0}}\frac{a^{h}-1}{h}]$

O termo em 1 equivale à derivada de $a^{x}$, em torno de x=0, ou seja, f'(x=0). Portanto, se a função $f(x)=a^{x}$ possuir derivada em x=0, a função f'(x) existe para todo $x \in R$.

Assim: $f'(x) = a^{x} \cdot f'(0)$, ou seja, a taxa de variação de uma função exponencial é proporcional à própria função.

Veja que: 
$[ \displaystyle{\lim_{h \to 0}}\frac{2^{h}-1}{h}]=0,69$
$[ \displaystyle{\lim_{h \to 0}}\frac{3^{h}-1}{h}]=1,10$

$f(x) = 2^{x} \longrightarrow f'(0) = 0,69$
$f(x) = 3^{x} \longrightarrow f'(0) = 1,10$

Perceba que cada valor da base **a** produz uma derivada em x=0 de valor único.

Definição do número $e$.
$[ \displaystyle{\lim_{h \to 0}}\frac{e^{x}-1}{h}]=1$, ou seja, a função $f(x)=e^{x}$ possui uma taxa de variação $f'(0)=1.$

Por sua vez:

Definição: A função e^{x} é denominada Exponencial natural e sua derivada $f'(x) = e^{x} \cdot f(0) = f(x) = e^{x}$.

O valor do limite arbitrário de f(x) = $a^{x} \longrightarrow f'(0)=\displaystyle{\lim_{h \to 0}}\frac{a^{h}-1}{h}$ equivale a $f'(0) = log_{e}a$, observe que $log_{e}e=1$.

Também usa-se a notação: $log_{e}a = ln(a)$: logaritmo natural.

Assim: $f(x) = a^x \longrightarrow f'(x) = a^x \cdot ln(a)$

OBS: O valor aproximado de $e$ vale $$e ~= 2,71828$$ 

## Regras de derivação: produto e quociente

### Regra do produto
Se f e g são funções deriváveis, ou seja, existe o limite $\displaystyle{\lim_{h \to 0}}\frac{f(x+h)-f(x)}{h}$ e $\displaystyle{\lim_{h \to 0}}\frac{g(x+h)-g(x)}{h}$ para todo o x, então:
$$[f(x)\cdot g(x)]' = f'(x)\cdot g(x) + f(x)\cdot g(x)'$$

### Regra do quociente
Se f e g atenderem ás mesmas condições da regra do produto, então:
$$[\frac{f(x)}{g(x)}]' = \frac{f'(x)\cdot g(x) + f(x)\cdot g(x)'}{[g(x)]^2}$$

Tabela de fórmulas de derivação (parcial):

$1) [f(x) = c]' = 0$ (DERIVADA DA CONSTANTE = 0)

$2) [x^n]' = n \cdot x^{n-1}$ (DERIVADA DA POTÊNCIA)

$3) [c \cdot f(x)]' = c \cdot f'(x)$ (REGRA DO PRODUTO ESCALAR)

$4) [f(x)\pm g(x)]' = f'(x) \pm g'(x)$ (REGRA DA ADIÇÃO E SUBTRAÇÃO)

$5) [a^x]' = a^x \cdot ln(a)$ (EXPONENCIAL)

$6)  [e^x]' = e^x$

$7) [f(x) \cdot g(x)]' = f'(x) \cdot g(x) + f(x) + g'(x)$ (REGRA DO PRODUTO)

$8) [\frac{f(x)}{g(x)}]' = \frac{f'(x) \cdot g(x) + f(x) + g'(x)}{[g(x)]^2}$ (REGRA DO QUOCIENTE)


Exemplo 1.
$\ \ \ f(x) = x² + 3x \\
  \ \ \ g(x) = x³+2 \\
  \ \ \ h(x) = e^x$ 
Calcule: 

$1) [f(x) \cdot g(x)]' \\
  2) [\frac{f(x)}{g(x)}]'$
  
**Solução:**
<p align="center">
  <img width="560" height="300" 	src="https://i.imgur.com/uroF64C.png">
</p>

## Derivadas de funções Trigonométricas
Primeiramente, vamos observar o comportamento da função $f(x)=sin(x)$ em termos de sua derivada utilizamos  a notação de Leibriz:
$$f(x)=sin(x) \longrightarrow f'(x) = \displaystyle{\lim_{h \to 0}}\frac{sin(x+h)-sin(x)}{h}$$
tem-se que:
$$sin(x) = sin(x)\cdot cos(h)+ cos(x) \cdot sin(x)$$
Propriedade
Assim, obtermos a seguinte expressão após a manipulação:
$f'(x) = \displaystyle{\lim_{h \to 0}} \ sin(x) \cdot \frac{cos(h)-1}{h} + f'(x) = \displaystyle{\lim_{h \to 0}} \ cos(x)\cdot\frac{sin(x)}{h}$

sin(x) e cos(x) não dependem de h, portanto, podem ser retiradas da expressão, logo:

$f'(x) = \ sin(x) \cdot  \displaystyle{\lim_{h \to 0}} \frac{cos(h)-1}{h} + f'(x) = \ cos(x)\cdot \displaystyle{\lim_{h \to 0}} \frac{sin(x)}{h}$

Sabemos que o limite em $(*)(*)$ será 1 (verificação anterior), portanto, determinamos o resultado de $\displaystyle{\lim_{h \to 0}} \frac{cos \ h -1}{h}$

A demonstração em mostre que o limite é zero, assim, a função f(x) = sin(x) possui derivada:
$f'(x) = sin(x) \cdot + cos(x) \cdot 1$
$f'(x) = cos(x)$

Portanto a derivada de $f(x)=sin(x) => f'(x) = cos(x)$

Utilizando o mesmo método visto anteriormente, tem-se que a função $f(x)=cos(x) vale f(x)=-sin(x)$, logo:

[sin(x)]'= cos(x)
[cos(x)]'= -sin(x)

Execício: Determinar a derivadas da funções a seguir
f(x) = tg(x)
g(x) = -sin(x)
h(x) = consec(x)

**Solução**
<p align="center">
  <img width="560" height="300" src="https://i.imgur.com/o7Pa3K9.png">
</p>

## Regra da Cadeia

Suponha que se deseje derivar a função  seguir? Como proceder?
$f(x)=\sqrt{x²+1} \longrightarrow F'(x)= ?$

para tal, precisamos identificar que existem duas funções encapsulada em F(x), ou seja:

Se $f(x) = \sqrt{x}$ e g(x) = x²+1, então F(x) = F'(x)=f(g(x))

A regra da cadeia nos dá um procedimento para determinar a derivadas dessas funçoes COMPOSTAS, desde que  se conheçam as derivadas das funções encapsuladas.

Definição: Sejam duas funções f(x) e g(x) tal que g seja derivável em x e f seja derivável em g(x). A derivada da função composta F(x) tal que F = (f o g) ou F(f(g(x)) é:
$$F'(x)=[f\ o\ g]' = f'(g(x)) \cdot g'(x)$$ 

Assim para determinar a derivada da função $f(x) = \sqrt{x²+1}$, devemos usar a regra da cadeia do seguinte modo:

1) identificar funções f e g e suas derivadas:

$f(x) \longrightarrow f'(x)=\frac{1}{2}x^{\frac{-1}{2}}$
$g(x) = x²+1 \longrightarrow g'(x) = 2x$

Assim:
$F'(x) = \frac{1}{2}\cdot (x²+1)^{\frac{-1}{2}}\cdot 2x = d=x\cdot(x²+1)^{{\frac{-1}{2}}} = \frac{x}{(x²+1)^{{\frac{-1}{2}}}}$

Exemplos 
1. $F(x) = sen²(x) \longrightarrow F'(x) = ?$

$f(x) = x² \longrightarrow F'(x)=2\cdot(sin(x)\cdot cos(x))$

Fórmula geral: Regra da cadeia para potências

Se n for qualquer número real e g(x) for derivável então:

$$([g(x)]^{n}) = n\cdot[g(x)]^{n-1}\cdotg'(x)$$

Determinar as derivadas a seguir:

1. $F(x) = cos³(x)$
2. $G(x) = sin(x) \cdot cos²(x)$
3. $H(x) = (x³-1)^{100}$

## Derivadas de funções exponenciais

Vamos escrever uma função exponencial a partir do exponencial natural
$$a^x => a = e^{ln(a)} = a^{x} = e^{ln(a)}$$
portanto: $(a^{x}) = a^{x}\cdot (ln(a))$

Regra geral para exponenciais:
$(a^{k\cdot x}) = k\cdot a^{k\cdot x}\cdot (ln(a))$

Caso particular: $a = e$
$(a^{k\cdot x}) = k\cdot e^{k\cdot x}$

## Devição implícita
Algumas funções não são representadas por uma variável explícita, como acontece com curvas como eclipses, cicloides e outras curvas parametrizáveis ou não.

Uma função implicíta é aquilo que não pode ser representada na forma y=f(x). Em vez disso, tomamos f(x,y) = 0. Eis alguns exemplos:

1. x²+y² = 25
$f(x,y) = x²+y² -25 => x²+y² -25 = 0$
2. $sin(x+y) = y²\cdot cos(x)$
$f(x,y) sin(x,y) - y²\cdot cos(x)$

para determinar a derivada, derivamos os lado da expressão em relação a x a fim de se obter, explicitamente uma expressão para y' com base em f(x,y).

Ex.: Determinar implicitamente a derivada de x²+y²=25

(x²+y²)'=25'
(x²)¹ = 2x
(y²)¹ = 2y * (y)'

Portanto:
$2x +y\cdot (y')=0 => y'=\frac{-2x}{2y} => y'=\frac{-x}{y}$

Ex.: $sin(x+y) = y²\cdot cos(x)$ [MARKDOWN]

**Solução**
<p align="center">
  <img width="560" height="300" src="https://i.imgur.com/JZQjXiR.png">
</p>

## Derivadas de funções trigonométricas inversas

**Definição função trigonométrica inversa**
$y = sin^{-1}(x)$, significa que sin(y) = x; $\frac{-\pi}{2} \leq y \leq \frac{\pi}{2}$. Estense este conceito para demais funções trigonométricas inversas $cos^{-1}(x)$, $tg^{-1}(x)$, $sec^{-1}(x)$ e $ctg^{-1}(x)$, para o domínio especificado em cada função.

Seguindo o conceito de derivação implicita para $sin^{-1}(x)$, tem-se:
$[sin(y)]' = [x]'$

Ex.: Encontrar as derivadas das funções trigonométricas inversas: 
$y=tg^{-1}(x)$
$y=sec^{-1}(x)$

**Solução**
<p align="center">
  <img width="560" height="300" src="https://i.imgur.com/r2MbjWP.png">
</p>

**Regras de derivação**

Exponencial: 

$[a^{x}] = a^{x} \cdot ln(a); [e^{k\cdot x}]; k\cdot e^{k \cdot x};\ k constante$

Implícita: 

$[f(x,y)]' = 0 => y' = g(x,y = [f(y)]' = f'(y) \cdot y'$

Trigonométricas inversas:

$(sin^{-1})' = \frac{1}{\sqrt{1-x²}}$

$(cos^{-1})' = \frac{-1}{\sqrt{1-x²}}$

$(tan^{-1})' = \frac{1}{1+x²}$

$(sec^{-1})' = \frac{1}{x \cdot \sqrt{1-x²}}$

$(cotg^{-1})' = - \frac{1}{x \cdot 1-x²}$

## Derivação logarítmica
A derivação logarítmica é uma estratégia que permite cálculo mais simplificada de derivar que envolvem produto, quocientes e potências.

O procedimento consiste em:

1. Tomar o logarítmico natural em ambos os lados da equação y = f(x). (Simplifique, se possível)
2. Derivar implicitamente em relação a x;
3. Isolar y' na equação resultado

Ex.: Derivar a expressão $y=\frac{x^{\frac{3}{4}} \cdot \sqrt{x²+1} }{(3x+2)⁵}$

**Solução**
<p align="center">
<img width="560" height="300"
src="https://i.imgur.com/rNknoTr.png">
  <img width="560" height="300" src="https://i.imgur.com/31ZCt4C.png">
</p>

## Função Hiperbólicas
Algumas funções, que são combinações das exponenciais $e^x$ e $e^{-x}$ surgem, com frequência, em aplicações da matemática.

alguns padrões dessas combinações são denominadas funções hiperbólicas, são elas:

Seno hiperbólico: $sin \ h(x) = \frac{e^x - e^{-x}}{2}$
Cosseno hiperbólico: $cos \ h(x) = \frac{e^x + e^{-x}}{2}$
Tangente hiperbólico: $tan \ h(x) = \frac{sin \ h(x)}{cos \ h(x)}$

Por sua vez:

$sin \ h(x) = \frac{1}{cos \ h(x)}$
$cos \ h(x) = \frac{1}{sin \ h(x)}$
$cotg \ h(x) = \frac{1}{tan \ h(x)}$

Algumas identidades válidas para funções hiperbólicas

$sin \ h(-x) = -sin \ h(x)$
$cos \ h(-x) = cos \ h(x)$
$sin \ h²(-x) = -sin \ h²(x)=1$
$1 - tan \ h²(-x) = sec²(x)$
$sin \ h(x+y) = sin \ h(x) \cdot cos \ h(x) + cos \ h(x) \cdot sin \ h(x)$
$sin \ h(x+y) = cos \ h(x) \cdot cos \ h(x) + cos \ h(x) \cdot cos \ h(x)$

## Funções hiperbólicas inversas

$y = sin \ h^{-1}(x) = sin \ h(y) = x$
$y = cos \ h^{-1}(x) = cos \ h(y) = x; \ y \geq 2$
$y = tg \ h^{-1}(x) = tg \ h(y) = x;$

As derivadas das funções hiperbólicas inversas:

$[sin \ h^{-1}(x)]' = \frac{1}{\sqrt{1+x²}}$

$[cos \ h^{-1}(x)]' = \frac{1}{\sqrt{x²-1}}$

$[sin \ h^{-1}(x)]' = \frac{1}{1+x²}$

Ex.: Determinar y' sabendo que $y=sin \ h(cos \ h(x))$. [MARKDOWN]
[FOTO]

## Aplicações de derivadas
No contexto do cálculo, são enumerados diversas aplicações para o uso de derivadas. Dentro da área de ciência da computação, usam-se derivadas especialmente para a determinação de ponto críticos de funções, tais como valores mínimos e máximos e pontos de inflexão.

**Máximos e mínimos**
	Seja $e$ um número  o domínio D de uma função então diz-se que:
	$f(c)$ é máximo absoluto se $f(c) \geq f(x)$ para todo x $\in$ D.
	$f(c)$ é mínimo absoluto se $f(c) \leq f(x)$ para todo x $\in$ D.

**Denominações** 
Máximo absoluto $\longrightarrow$ máximo global
Mínimo absoluto $\longrightarrow$ mínimo global
Máximo e mínimo locais, são valores de f(c) que satisfazem:
$\ \ f(e) \geq f(x)$ na vizinhança de x; (máximo)
$\ \ f(e) \leq f(x)$ na vizinhança de x; (mínimo)

Dentro desse contexto, definimos o teorema a seguir:

Teorema de Fermat: Se f possui um máximo local ou mínimo local em $c$, então $f(c) [max/min] \longrightarrow f'(c)=0.$
Dizemos que, todos os valores c que satisfazem $f'(c) = 0$. ou $f'(c)$ = não existe, são números eretivos.

Ex.: Determinar os números  críticos da funções $f(x) = 3x³-16x²+18$

**Como as derivadas de uma função afetam a forma de um gráfico?**

Para saber se uma função é crescente ou decrescente em um determinado intervalo, denominamos o comportamento da derivada f'(x):
	(a) Se f(x)>0 em um intervalo, f(x) será crescente no mesmo intervalo.
	(b) Se f'(x)<0 em um intervalo, então f(x) será decrescente nesse intervalo.

**Teste da primeira derivada**
Suponha que c seja um número crítico de uma função contínua f:

(a) Se o sinal de f' mudar de positivo para negativo em $e$, então f tem MÁXIMO LOCAL em c.
(b) Se o sinal de f' mudar de negativo para positivo, então então f terá um MÍNIMO LOCAL em c.
(c) Caso contrário, c não será máximo nem mínimo local.

**Teste da concavidade (Derivada de segunda ordem)**
(a) se f''(x)>0 em um intervalo $I$, então f terá concavidade para cima em $I$.
(b) se f''(x)<0 em um intervalo $I$, então f terá concavidade apontando para baixo em $I$.
(c) Os valores que produzem f''(x)=0 serão chamados PONTOS DE INFLEXÃO e correspondentes aos valores em que f muda seu comportamento.

<p align="center">
<img width="560" height="300" src="https://i.imgur.com/Fq4eEQj.png">

</p>

## Aplicações de Derivadas

**Teorema do valor médio**
Seja f uma função que satisfaça a:
1. f é continua em no intervalo fechado [a,b]
2. f é derivável no intervalo (a,b)

Então, existe um número c no intervalo (a,b) tal que:
$$f'(c)=\frac{f(b)-f(a)}{b-a}$$

Ou seja:
$$f(b)-f(a) = f'(c)\cdot (b-a)$$

**Representação geométrica**
A inclinação de uma rena secante nos pontos A e B é representada por
$$m_{AB} = \frac{f(b)-f(a)}{b-a}$$
significa que, para qualquer intervalo (a,b), existe um valor c talquer f'(c) corresponde à inclinação $m_{AB}$

<p align="center">
<img width="560" height="300" src="https://i.imgur.com/Gkytcvs.png">
</p>

OBS: Pode existir mais de um valor c que satisfaça a essa hipótese.

Uma consequencia do TUM é o teorema de Ralte.

Se uma função f sastifaça a:
1. f é continua no intervalo fechado [a,b]
2. f é derivável em (a,b)
3. f(a) = f(b)

$Ex_1$.: Mostre que a equação x³-15x+c = 0 tem, no máximo, uma raiz no intervalo [-2,2]
<p align="center">
<img width="560" height="300" src="https://i.imgur.com/9gdQtRV.png">
</p>

$Ex_2$.:Verificar a quantidade máximo de raízes reais das funções f(x)=x³+x-1 no intervalo [-1,2]
<p align="center">
<img width="560" height="300" src="https://i.imgur.com/5iF8sRn.png">
</p>

**Formas indeterminados e regra de L'Hospital**
Suponha que se deseje analisar o comportamento da função $f(x)= ln \ x$ próximo a x=1, apesar de f não estar definida em x=1.

**Regra de L' Hospital**
Suponha que f e g sejam deriváveis em g'(x) $\not=$ 0 em um intervalo aberto $I$ que contenha a. (exceto, possivelmente, o próprio a) Suponha que:

$\displaystyle{\lim_{x \to a} f(x) = 0 }$ ou $\displaystyle{\lim_{x \to a} f(x) = \infty }$
$\displaystyle{\lim_{x \to a} g(x) = 0 }$ ou $\displaystyle{\lim_{x \to a} f(x) = \infty }$

Então
$\displaystyle{\lim_{x \to a} \frac{f(x)}{g(x)} }=\displaystyle{\lim_{x \to a} \frac{'f(x)}{'g(x)} }$

Em outras palavras, $\frac{f(x)}{g(x)}$ gera indeterminação da forma $\frac{0}{0}$ ou $\frac{\infty}{\infty}$ 

Ex.: Determinar
a) $\displaystyle{\lim_{x \to a} \frac{ln(x)}{x-1}}$
 
b) $\displaystyle{\lim_{x \to a} \frac{ln(x)}{\sqrt[3]{x-1}}}$
**Solução**
<p align="center">
<img width="560" height="300" src="https://i.imgur.com/Z5eRfju.png">
</p>

####  End markdown!
####  Merry christmas and happy new year!


	











