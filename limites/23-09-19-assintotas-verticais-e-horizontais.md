 <script>
  MathJax = {
    tex: {inlineMath: [['$', '$'], ['\\(', '\\)']]}
  };
  </script>
  <script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-chtml.js"></script>
  
   <script src="https://cdn.jsdelivr.net/npm/mermaid@8.4.0/dist/mermaid.min.js"></script>
 <script>mermaid.initialize({startOnLoad:true});</script>

#### [aula anterior](./18-09-19-continuidade-de-funcoes.html) | [próxima aula](24-09-19-derivadas-e-taxa-de-variacao.html)

#### Digitado por [$\color{black} \text{Diefesson de Sousa Silva - 471942}$](mailto://diefesson.so@gmail.com)

# Assintotas verticais e horizontais

## Assintota vertical

É todo valor de $x = a$ que implica em:

$\lim_{x \rightarrow a} f(x) = \pm \infty$

## Assintota horizontal

São os valores para os quais convergem:

$
\lim_{x \rightarrow +\infty} f(x) = L_1
\text{ e }
\lim_{x \rightarrow -\infty} f(x) = L_2
$

## Algumas assintotas recorrentes

$f(x) = \frac{1}{x^r}, x > 1 \text{ e } r > 0$

$
\lim_{x \rightarrow -\infty}f(x) = \lim_{x \rightarrow -\infty}f(x) = 0
$

$g(x) = e^x \text{ e } h(x) = e^{-x}$

$
\lim_{x \rightarrow -\infty} g(x) =
\lim_{x \rightarrow +\infty} h(x)  = 0
$

## Limites no infinito

Usamos a notação:

$\lim_{x \rightarrow +\infty}f(x) = +\infty$

Quando $f(x)$ cresce a medida que $x$ se torna grande. Analogamente tem-se:

$
\lim_{x \rightarrow -\infty}f(x) = +\infty \\
\lim_{x \rightarrow +\infty}f(x) = -\infty \\
\lim_{x \rightarrow -\infty}f(x) = -\infty \\
$

**EXEMPLO:** Determinar os limites

**a)**

$\lim_{x \rightarrow +\infty}(x^2 - x)$

**R:** $+\infty$

**b)**

$
\lim_{x \rightarrow +\infty}\frac
{x^2 - x}
{3 - x}
$

**R:** $-\infty$

## Definição precisa de assintota horizontal

Seja $f$ uma função definida em um intervalo $(-\infty, a)$. Então:

$
\lim_{x \rightarrow -\infty} = L
$

Implica que para todo $\epsilon > 0$ existe um número $N$ tal que:

Se $x < N$ então $|f(x) - L| = \epsilon$

Por sua vez se em um intervalor $(a, +\infty)$ é observado que:

$\lim_{x \rightarrow +\infty} f(x) = +\infty$

Significa que, para todo positivo $M$, existe um correspondente positivo $N$, tal que:

Se $x > N$ então $f(x) > M$

**EXERCÍCIO:** Determine as assintotas horizontais e verticais das funções.

**a)** $f(x) = \dfrac{2x + 1}{x - 2}$

---

**Assintota vertical:** $x=2$

**Assintota horizontal:**

Transformando a função f(x), temos:

$\frac{2x + 1}{x - 2} \Leftrightarrow$

$\frac{x (2 + \frac{1}{x})}{x (1 - \frac{2}{x})}\Leftrightarrow$

$\frac{2 + \frac{1}{x}}{1 - \frac{2}{x}}$

E aplicando o limite:

$
\lim_{x \rightarrow \infty} \left( \frac{2 + \frac{1}{x}}{1 - \frac{2}{x}} \right) \Leftrightarrow
$

$
\frac{2 + \frac{1}{\infty}}{1 - \frac{2}{\infty}} \Leftrightarrow
$

$
\frac{2}{1} \Leftrightarrow
$

$y=2$

---

**b)** $g(x) = \dfrac{x^4 + 1}{-x^4 + x^2}$

---

**Assintota vertical:**

$\frac{x^4 + 1}{-x^4 + x^2} \Leftrightarrow$

$\frac{x^4 + 1}{x^2(-x^2 + 1)}$

Logo fica evidente que suas raízes são:

$x = -1, 0, 1$

**Assintota horizontal:**

Transformando a função, temos:

$\frac{x^4 + 1}{-x^4 + x^2} \Leftrightarrow$

$\frac{x^4(1+ \frac{1}{x^4})}{x^4(-1 + \frac{1}{x^2})} \Leftrightarrow$

$\frac{1+ \frac{1}{x^4}}{-1 + \frac{1}{x^2}} \Leftrightarrow$

E aplicando o limite:

$
\lim_{x \rightarrow \infty}\left(
\frac{1+ \frac{1}{x^4}}{-1 + \frac{1}{x^2}}
\right) \Leftrightarrow
$

$\frac{1}{-1} \Leftrightarrow$

$y = -1$

---
