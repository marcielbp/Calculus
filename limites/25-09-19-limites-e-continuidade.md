 <script>
  MathJax = {
    tex: {inlineMath: [['$', '$'], ['\\(', '\\)']]}
  };
  </script>
  <script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-chtml.js"></script>
  
   <script src="https://cdn.jsdelivr.net/npm/mermaid@8.4.0/dist/mermaid.min.js"></script>
 <script>mermaid.initialize({startOnLoad:true});</script>

#### [aula anterior](./24-09-19-derivadas-e-taxa-de-variacao.html) | você está na última aula

#### Digitado por [$\color{black} \text{Diefesson de Sousa Silva - 471942}$](mailto://diefesson.so@gmail.com)

# Limites e continuidade

Sejam $f$ e $g$ continuas próximas ao ponto $a$, são válidas as propriedades:


*1.*

$$\lim{x \rightarrow a} f(x) = L$$

*2.*

$$\lim_{x \rightarrow a} g(x) = M$$

*3.*

$$\lim_{x \rightarrow a}(f(x) + g(x)) = L + M$$

*4.*

$$
\lim_{x \rightarrow a}(c \cdot f(x) + d \cdot g(x)) = c \cdot L + d \cdot M
$$

*5.*

$$\lim_{x \rightarrow a}(f(x) \cdot g(x)) = L \cdot M$$

*6.*

$$
\lim_{x \rightarrow a}\left( \frac{f(x)}{g(x)} \right) = \frac{L}{M}
, M \ne 0
$$

## Limites laterais

*1.*

$$
\lim_{x \rightarrow a^-} = L_1 \text{ ,\color{red}pela esquerda}
$$

*2.*

$$
\lim_{x \rightarrow a^+} = L_2 \text{ ,\color{red}pela direita}
$$

## Continuidade

Se:

$$
\lim_{x \rightarrow a^-} f(x) =
\lim_{x \rightarrow a^+} f(x) =
f(a)
$$

$f$ será continua em $a$.

## Assintotas verticais

Valores de $a$ que levam a função $f(x)$ a indeterminação, ou seja:

*1.*

$$\lim_{x \rightarrow a^-} f(x) = \pm \infty$$

*2.*

$$\lim_{x \rightarrow a^+} f(x) = \pm \infty$$

*3.*

$$\lim_{x \rightarrow a^-} f(x) = \pm \infty$$

## Teorema do confronto

$$
\lim_{x \rightarrow 0} \left(
\sin\left( \frac{\pi}{x} \right) \cdot x^2
\right)
$$

Esta função está limitada entre $-x^2$ e $x^2$, para $x \rightarrow 0$, temos:

$$
-x^2 \le
\sin(\frac{\pi}{x} \cdot x^2) \le
x^2
$$

E aplicando o limite nessas funções temos:

$$
0 \le
\sin(\frac{\pi}{x} \cdot x^2) \le
0
$$

Logo:

$$
\lim_{x \rightarrow 0} \left(
\sin\left( \frac{\pi}{x} \right) \cdot x^2
\right) = 0
$$
