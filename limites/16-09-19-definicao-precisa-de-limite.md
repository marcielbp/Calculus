 <script>
  MathJax = {
    tex: {inlineMath: [['$', '$'], ['\\(', '\\)']]}
  };
  </script>
  <script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-chtml.js"></script>
  
   <script src="https://cdn.jsdelivr.net/npm/mermaid@8.4.0/dist/mermaid.min.js"></script>
 <script>mermaid.initialize({startOnLoad:true});</script>

#### [aula anterior](./10-09-19-calculos-usando-propriedades-dos-limites.html) | [próxima aula](./17-09-19-definicao-precisa-de-limite.html)

#### Digitado por [$\color{black} \text{Diefesson de Sousa Silva - 471942}$](mailto://diefesson.so@gmail.com)

# Definição precisa de limite

Primeiramente, vamos observar o comportamento de uma função próximo a um ponto de interesse.

Suponha um função $f(x)$ definida como:

$
f(x) \begin{cases}
2x - 1 & , x \ne 3 \\
6 &, x = 3
\end{cases}
$

Observe a afirmação, qual a proximidade que $x$ deve ter de $3$ para que $f(x)$ seja diferente de $5$ em menos que $0,1$?

Veja que a medida que $x \rightarrow 3^+$ ou $x \rightarrow 3^-$, $f(x)$ se aproxima de $5$, apesar que $f(3) = 6$. Para encontramos uma distância mínima de $3$ para $f(x)$ ser próximo de $5$ por um valor menor que $0,1$ devemos realizar a desigualdade:

$|f(x) - 5| \lt 0,1$

Chamamos de $\delta$(delta minusculo) a distância entre $x$ observado e $3$, assim, se $|f(x) - 5| \lt 0,1$ então $0 \lt |x - 3| \lt \delta$.

Vamos supor que $x = 2,9$, logo $0 \lt | 2,9 - 3 | \lt \delta = 0 \lt 0,1 \lt \delta$. Ao mesmo tempo: $f(2,9) = 2 \cdot 2,9 - 1 = 4,8$, $\color{red} \text{não satisfaz}$ a condição imposta. Porém se $x = 2,95$, $\delta > 0,05$, consequentemente, $2 \cdot 2,95 - 1 = 4,9$, satisfaz a condição.

Logo, há uma relação entre a proximidade do ponto onde se deseja calcular o limite e o $\delta$ escolhido.

**EXEMPLO:** encontre um valor de $\delta$ que satisfaça, dado $f(x) = x^3 - 5x + 6$

$
|x - 1| < \delta \rightarrow |f(x) - 2| < 0,2
$

$\bold{x < 1}$ | $\bold{f(x)}$ | $\bold{x > 1}$ | $\bold{f(x)}$
-|-|-|-
$0$    | $6,000$ | $2$    | $4,000$
$0,5$  | $3,725$ | $1,5$  | $1,875$
$0,7$  | $2,943$ | $1,3$  | $1,697$
$0,9$  | $2,229$ | $1,1$  | $1,831$
$0,99$ | $2,020$ | $1,01$ | $1,980$

**R:** $\delta = 0,1$
