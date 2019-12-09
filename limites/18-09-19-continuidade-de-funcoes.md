 <script>
  MathJax = {
    tex: {inlineMath: [['$', '$'], ['\\(', '\\)']]}
  };
  </script>
  <script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-chtml.js"></script>
  
   <script src="https://cdn.jsdelivr.net/npm/mermaid@8.4.0/dist/mermaid.min.js"></script>
 <script>mermaid.initialize({startOnLoad:true});</script>

#### [aula anterior](./17-09-19-definicao-precisa-de-limite.html) | [próxima aula](./23-09-19-assintotas-verticais-e-horizontais.html)

#### Digitado por [$\color{black} \text{Diefesson de Sousa Silva - 471942}$](mailto://diefesson.so@gmail.com)

# Continuidade de funções
	
Verificamos anteriormente que uma função é continua s as três condições a seguir forem válidas.

**$f$ é continua se:**

*1.* $f(a)$ está definida, $a \in \text{dom}\{f\}$

*2.*

$\lim_{x \rightarrow a} f(x) \text{ existe}$

*3.* 

$\lim_{x \rightarrow a} f(x) = f(a)$

Temos, conseguente, conceitos sobre continuidade lateral:

**DEFINIÇÃO:** Uma função $f$ é $\color{red}{\text{continua a direita }}$ em um número $\color{red} a$ se:

$\lim_{x \rightarrow a^+} f(x) = f(a)$

E é $\color{red}\text{continua pela esquerda}$ se:

$\lim_{x \rightarrow a^-} f(x) = f(a)$

Consequentemente temos a definição a seguir:

**DEFINIÇÃO:** Dizemos que $f$ é continua em $a$ se $f$ for continua simultaneamente á direita e a esquerda.

**TEOREMA:** se $f$ e $g$ forem continuas em $a$ e $c$ é uma constante real, consequentemente, as funções a seguir também serão continuas em $a$:

*1.* $f + g$

*2.* $f - g$

*3.* $c \cdot f$

*4.* $f \cdot g$

*5.* $\dfrac{f}{g}$, se $g(a) \ne 0$

Algumas classes de funções mostradas a seguir são continuas em todos os pontos que pertencem ao seu domínio:

**a.** Funções polinomiais :

$x^4 - x^2 + 16x$

**b.** Funções trigonométricas:

$\cos(3x)$

**c.** Funções exponenciais:

$e^{-3x}$

**d.** Funções racionais:

$\frac{x^2 - 3x}{x - 1}$

**e.** Funções trigonométricas inversas:

$\arcsin(x)$

**f.** Funções raízes:

$\sqrt{x^2 - 3}, \text{ se } x \ge \sqrt{3}$

**g.** Funções logarítmicas:

$\ln(3x), \text{ se } x > 0$

**EXEMPLO:** dada a função:

$f(x) = \frac{\sin(x)}{2 + \cos(x)}$

**a)** A função é continua? em que intervalo?

**R:** A função é continua para $\R$, pois $2 + \cos(x)$ nunca é igual a 0

**b)** Determinar

$
\lim_{x \rightarrow \pi} \left(
\frac{\sin(x)}{2 + cos(x)}
\right)
$

**R:**

$
\frac
{\lim_{x \rightarrow \pi} (\sin(x))}
{\lim_{x \rightarrow \pi}(2) + \lim_{x \rightarrow \pi}(\cos(x)}
\Leftrightarrow
$

$
\frac{0}{2 - 1} = 0
$

**TEOREMA:** Seja $f$ $\color{red}\text{continua}$ em $b$ e:

$\lim_{x \rightarrow a} f(x) = b$

Então:

$
\lim_{x \rightarrow a}(f(g(x))) = f(b)
$

Ou seja:

$
\lim_{x \rightarrow a}(f(g(x)) = f(\lim_{x \rightarrow a}g(x))
$

**EXEMPLO:** Calcular

$\lim_{x \rightarrow a} \sqrt[n]{x^2}$, com $a$ positivo inteiro:

$\lim_{x \rightarrow a} \sqrt[n]{x^2} \Leftrightarrow$

$\sqrt[n]{\lim_{x \rightarrow a} (x^2)} \Leftrightarrow$

$\sqrt[n]{\lim_{x \rightarrow a} (x)^2} \Leftrightarrow$

$\sqrt[n]{a^2}$

**TEOREMA:** se $g$ é continua em $a$ e $f$ é continua em $g(a)$, então a função composta $(f \circ g)(x)$ é continua em $a$

**EXEMPLO:** se $f(x) = \dfrac{1}{x - 1}$, $f$ não é continua em $x = 1$ e $g(x) = \dfrac{2}{x}$, não é continua em $x = 0$. Porém, $g(1) = 2$ e $f$ é continua em $x = 2$. Assim $f(g(x))$ é continua em $x = 1$

**TEOREMA DO VALOR INTERMEDIÁRIO**

Supondo que $f$ seja continua em um intervalo $[a, b]$ e seja $N$um número qualquer entre $f(a)$ e $f(b)$, tal que $f(a) \ne f(b)$. Logo existe um número $c \in [a, b]$ tal que $f(c) = N$.

**EXEMPLO:** Mostrar que existe uma raíz da equação $4x^3 - 6x^2 + 3x - 2 = 0$entre $x = 1$ e $x = 2$

## Limites no infinito: Assíntotas horizontais

Imaginesmos funções que: Dado um intervalo $(-\infty, a)$ ou $(a, +\infty)$. Se observarmos o comportamento da função $f(x)$ nesses intervalos, quando $x \rightarrow -\infty$ ou $x \rightarrow +\infty$, é possivel que o valor de $f(x)$ tenda a um número real, ou seja:

$
\lim_{x \rightarrow -\infty} = L_1
\text{ ou }
\lim_{x \rightarrow +\infty} = L_2
$

Dizemos que as retas $l_1$ e $L_2$, caso existam, são assintotas horizontais.


