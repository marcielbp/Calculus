 <script>
  MathJax = {
    tex: {inlineMath: [['$', '$'], ['\\(', '\\)']]}
  };
  </script>
  <script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-chtml.js"></script>
  
   <script src="https://cdn.jsdelivr.net/npm/mermaid@8.4.0/dist/mermaid.min.js"></script>
 <script>mermaid.initialize({startOnLoad:true});</script>

#### [aula anterior](./02-09-19-limites-e-derrivadas.html) | [próxima aula](./09-09-19-limites.html)

#### Digitado por [$\color{black} \text{Diefesson de Sousa Silva - 471942}$](mailto://diefesson.so@gmail.com)

# Limites e derrivadas

Anteriormente definimos  o limite de uma função como uma estimativa de $L$ do valor $\lim_{x \rightarrow a} f(x) = L$, tal que $L$ representa o valor da função na vizinhança ou próximo de $a$. É importante frisar que não necessariamente:

*1.* $\lim_{x \rightarrow a} f(x) = f(a)$.

*2.* $f(a)$ pode ser calculada.

Vamos estimar o limite das funções a seguir:

*a)* determinar $\lim_{x \rightarrow a}\left(\frac{\sin(x)}{x}\right)$

Veja que nesse caso, não se pode calcular o valor da função diretamente em $x = 0$, pois há indeterminação.

**OBS:** a função $\sin(x)$ ou qualquer outra função trigonométrica só pode ser calculada para valores em radianos. Ou seja:

$$
\sin(0) = \sin(0 \text{ rad}) \\
\sin(\pi) = \sin(\pi \text{ rad}) = \sin(180\degree)
$$

Observando a função $\frac{\sin(x)}{x}$, na vizinhança de $x = 0$ obtém-se a tabela a seguir:

$\bold{x < 0}$ | $\bold{f(x)}$ |  $\bold{x > 0}$ | $\bold{f(x)}$
-|-|-|-
$-1$    | $0,841$ | $1$    | $0,841$
$-0,5$  | $0,958$ | $0,5$  | $0,958$
$-0,2$  | $0.993$ | $0,2$  | $0,993$
$-0,1$  | $0,998$ | $0,1$  | $0,998$
$-0,01$ | $0,999$ | $0,01$ | $0,999$

Observe que o limite de $f(x)$ se aproxima de $1$ a medida que $x \rightarrow 0$, ou  seja:

$$\lim_{x \rightarrow a}\left(\frac{\sin(x)}{x}\right) = 1$$

## Exercício 1

Estime o limite da função:

$$f(x) = \frac{\cos(x)}{2x}$$

A medida que $x$ se aproximada de 0, ou seja:

$$\lim_{x \rightarrow a}\left(\frac{cos(s)}{2x}\right)$$

$\bold{x < 0}$ | $\bold{f(x)}$ | $\bold{x > 0}$ | $\bold{f(x)}$
-|-|-|-
$-1$    | $-0,27$  | $1$    | $0,27$
$-0,5$  | $-0,877$ | $0,5$  | $0,877$
$-0,2$  | $-2,45$  | $0,2$  | $2,45$
$-0,1$  | $-4,97$  | $0,1$  | $4,97$
$-0,01$ | $-49,99$ | $0,01$ | $49,99$

## Limites laterais

Quando observamos a função $f(x) = \frac{cso(x)}{2x}$, percebemos que os valores da função são diferentes - $(+)$positivos ou $(-)$ negativos - dependendo do caminho tomado($x < 0$ ou $x > 0$). Formalizaremos o limite pela esquerda ou pela direita do número de referência $a$ como limites laterais.

**DEFINIÇÃO 1**

Escrevemos os limites laterais na forma.

*1.* $\lim_{x \rightarrow a^+} f(x) = L_1$, quando $x$ tende a $a$ por valores maiores que $a$ ou a direita de $a$.

*2.* $\lim_x{x \rightarrow a^-} f(x) = L_2$, quando $x$ tende a $a$ por valores menores que $a$ ou a esquerda de $a$.

**DEFINIÇÃO 2**

Dizemos que o limite de uma função em torno de $a$ é $\lim_{x \rightarrow a} f(x) = L$, se, e somente se, seus limites laterais forem iguais, ou seja:

$$\lim_{x \rightarrow a^-} f(x) = \lim_{x \rightarrow a^+} f(x) = L$$

## Limites infinitos

Dizemos que caso o limite de uma função no ponto $x = a$ cresça positivamente ou negativamente de forma indefinida, seu limite será infinito, ou seja:

$$\lim_{x \rightarrow a} f(x) = +\infty \text{ ou } \lim_{x \rightarrow a} f(x) = -\infty$$

Dizemos nesse caso que:

"O limite de $f(x)$, quando $x$ tende a $a$ é mais infinito ou menos infinito."

## Exercício

Determine os limites laterais das funções:

*1)* $\frac{1}{x^2}$, $x \rightarrow 0$

**R:** $\lim_{x \rightarrow a} \left(\frac{1}{x^2}\right) = +\infty$, para os dois lados.

$\bold{x < 0}$ | $\bold{\frac{1}{x^2}}$ | $\bold{x > 0}$ | $\bold{\frac{1}{x^2}}$
-|-|-|-
$-1$    | $1$ | $1$ | $1$
$-0,5$  | $4$ | $0,5$ | $4$
$-0,2$  | $25$ | $0,2$ | $25$
$-0,1$  | $100$ | $0,1$ | $100$
$-0,01$ | $10000$ | $0,01$ | $10000$

*2)* $\frac{1}{-x^2}$, $x = 0$

**R:** $\lim_{x \rightarrow a} \left(\frac{1}{x^2}\right) = -\infty$, para os dois lados.

$\bold{x < 0}$ | $\bold{\frac{1}{-x^2}}$ | $\bold{x > 0}$ | $\bold{\frac{1}{-x^2}}$
-|-|-|-
$-1$    | $-1$     | $1$    | $-1$
$-0,5$  | $-4$     | $0,5$  | $-4$
$-0,2$  | $-25$    | $0,2$  | $-25$
$-0,1$  | $-100$   | $0,1$  | $-100$
$-0,01$ | $-10000$ | $0,01$ | $-10000$
