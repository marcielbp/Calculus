 <script>
  MathJax = {
    tex: {inlineMath: [['$', '$'], ['\\(', '\\)']]}
  };
  </script>
  <script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-chtml.js"></script>
  
   <script src="https://cdn.jsdelivr.net/npm/mermaid@8.4.0/dist/mermaid.min.js"></script>
 <script>mermaid.initialize({startOnLoad:true});</script>

#### [aula anterior](./16-09-19-definicao-precisa-de-limite.html) | [próxima aula](./18-09-19-continuidade-de-funcoes.html)

#### Digitado por [$\color{black} \text{Diefesson de Sousa Silva - 471942}$](mailto://diefesson.so@gmail.com)

# Definição precisa de limite(continuação)

**DEFINIÇÃO:** seja $f$ uma função definida em algum lugar aberto que contenha o número $a$, exceto, póssivelmente o próprio $a$. Dizemos que o limite de $f(x)$ quando $x$ tende a $a$ é $L$ e escrevemos:

$$\lim_{x \rightarrow a} f(x) = L$$

Se para o número $\epsilon > 0$ houver um número $\delta > 0$, tal que:

$\text{se } 0 < |x - a| < \delta$ então $|f(x) - L| < \epsilon$

Ou seja:

O limite da função $f(x)$ quando $x \rightarrow a$ $\color{red}\text{existe se, e somente se}$, há um par de números $(\delta, \epsilon)$ e um valor $L$ que satisfaçam as condições apresentadas.

Consequentemente as definições de limites laterais se tornam:

*1.* Limite a esquerda.

$$\lim_{x \rightarrow a^-} f(x) = L_1$$

Se para todo número $\epsilon > 0$, existe um $\delta > 0$, tal que:

$a - \delta < x < a$

Então:

$\|f(x) - L_1\| < \epsilon$

*2.* Limite a direita.

$$\lim_{x \rightarrow a^+} f(x) = L_2$$

Se para todo número $\epsilon > 0$, existe um $\delta > 0$, tal que:

$a < x < a + \delta$

Então:

$\|f(x) - L_1\| < \epsilon$

**EXEMPLO:** Demonstrar que

$\lim_{x \rightarrow 3} x^2 = 9$

---

$\lim_{x \rightarrow 3}(x)^2 \Leftrightarrow$

$3^2 = 9$

# Limites infinitos

**DEFINIÇÃO:** seja $f$ uma função definida em um intervalo aberto que contenha $a$, exceto, possivelmente em $a$ então:

$\lim_{x \rightarrow a} f(x) = \infty$

Significa que, para todo número positivo $M$ haverá um número positivo $\delta$, tal que:

$0 < |x - a| < \delta_1$

Então:

$f(x) > M$

**DEFINIÇÃO:** Por sua vez, se:

$\lim_{x \rightarrow a} f(x) = -\infty$

Significa que para todo número negativo $N$
existem um número positivo $\delta_2$, tal que :

$0 < | x - a | < \delta$

$f(x) < N$ 

Observe que as funções a seguir:

*1.*

$
\lim_{x \rightarrow 3}\left(\frac{1}{(x-3)^2}\right) = +\infty
$

$
f(x) = \frac{1}{(x-3)^2}
$

*2.*

$
\lim_{x \rightarrow 3}\left(\frac{-3}{x^2}\right) = -\infty
$

$
g(x) = \frac{-3}{x^2}
$

$f(x)$ próximo a $x=3$

$\bold{x}$ | $\bold{\delta}$ | $\bold{f(x)}$
-|-|-
$2,9$   | $0,1$   | $100$
$2,99$  | $0,01$  | $10000$
$2,999$ | $0,001$ | $1000000$

$\bold{x}$ | $\bold{\delta}$ | $\bold{f(x)}$
-|-|-
$3,1$ | $0,1$ | $100$
$3,01$ | $0,01$ | $10000$
$3,001$ | $0,001$ | $1000000$

$g(x)$ próximo a $x = 0$

$\bold{x}$ | $\bold{\delta}$ | $\bold{g(x)}$
-|-|-
$0,1$   | $0,1$   | $-100$
$0,01$  | $0,01$  | $-10000$
$0,001$ | $0,001$ | $-1000000$

$\bold{x}$ | $\bold{\delta}$ | $\bold{g(x)}$
-|-|-
$-0,1$ | $0,1$ | $-100$
$-0,01$ | $0,01$ | $-10000$
$-0,001$ | $0,001$ | $-1000000$

# Continuidade

Dizemos que uma função é $\color{red}\text{continua em um número } a$, se:

$\lim_{x \rightarrow a} f(x) = f(a)$

Tem-se, então, as condições a seguir:

*1.* $f(a)$ está definida, $a \in \text{dom}\{f\}$

*2.*

$\lim_{x \rightarrow a} f(x) \text{ existe}$

*3.* 

$\lim_{x \rightarrow a} f(x) = f(a)$

**EXEMPLO:** verifique a função:

$
f(x) = 
\begin{cases}
\frac{x^2 - x - x}{x - 2}, \text{ se } x\ne 2\\
1, \text{ se } x = 2
\end{cases}
$

É continua

---

$\lim_{x \rightarrow 2} f(x) \Leftrightarrow$

$
\lim_{x \rightarrow 2}\left( 
\frac{x^2 - x - x}{x - 2}, \text{ se } x\ne 2\\
1, \text{ se } x = 2
 \right) \Leftrightarrow
 $

$
\lim_{x \rightarrow 2} \left( \frac{(x+1)(x-2)}{x-2}  \right) \Leftrightarrow
$

$
\lim_{x \rightarrow 2} (x + 1) = 3
$


