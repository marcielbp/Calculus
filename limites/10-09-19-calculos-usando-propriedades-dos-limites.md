#### [aula anterior](./09-09-19-limites.html) | [próxima aula](./16-09-19-definicao-precisa-de-limite.html)

#### Digitado por [$\color{black} \text{Diefesson de Sousa Silva - 471942}$](mailto://diefesson.so@gmail.com)

# Cálculos usando propriedades dos limites

Supondo que $c$ seja uma constante e os limites:

$$\lim_{x \rightarrow a} f(x) \text{ e } \lim_{x \rightarrow a} g(x)$$

Existam, e então seguem as propriedades

*1.* soma

$$
\lim_{x \rightarrow a}(f(x) + g(x)) = \lim_{x \rightarrow a} f(x) + \lim_{x \rightarrow a} g(x)
$$

*2.* diferença

$$
\lim_{x \rightarrow a}(f(x) - g(x)) = \lim_{x \rightarrow a} f(x) - \lim_{x \rightarrow a} g(x)
$$

*3.* produto por escalar

$$
\lim_{x \rightarrow a}(c \cdot f(x)) = c \cdot \lim_{x \rightarrow a} f(x)
$$

*4.* produto

$$
\lim_{x \rightarrow a}(f(x) \cdot g(x)) = \lim_{x \rightarrow a} f(x) \cdot \lim_{x \rightarrow a} g(x)
$$


*5.* quociente

$$
\lim_{x \rightarrow a}\left(\frac{f(x)}{g(x)}\right) = \frac{\lim_{x \rightarrow a} f(x)}{\lim_{x \rightarrow a} g(x)}
$$

Se $\lim_{x \rightarrow a} g(x) \ne 0$

Em decorrência das propriedades $1$  a $5$, são observadas outras propriedades a seguir:

*6.* potência

$$
\lim_{x \rightarrow a}(f(x)^n) = \lim_{x \rightarrow a}(f(x))^n
$$

**Limites especiais** 

*7.*

$$\lim_{x \rightarrow a} c = c$$

*8.*

$$\lim_{x \rightarrow a} x = a$$

*9.*

$$\lim_{x \rightarrow a} x^n = a^n, n \ge 0$$

*10.*

$$
\lim_{x \rightarrow a} \sqrt[n]{x} = \sqrt[n]{a}, n \ge 0
$$

*11.*

$$
\lim_{x \rightarrow a} \sqrt[n]{f(x)} = \sqrt[n]{\lim_{x \rightarrow a} f(x)}
$$

Se o limite for não negativo e $n$ inteiro positivo.

**EX:** use as propriedades para encontrar os limites das funções a seguir.

*1)*

$$\lim_{x \rightarrow 5}(2x^2 - 3x + 4)$$

**R:**

$$
\lim_{x \rightarrow 5}(2x^2 - 3x) + \lim_{x \rightarrow 5} 4
$$

$$
\lim_{x \rightarrow 5}(2x^2) - \lim_{x \rightarrow 5} (3x) + \lim_{x \rightarrow 5} 4
$$

$$
2\cdot \lim_{x \rightarrow 5}(x^2) - 3 \cdot \lim_{x \rightarrow 5} x + \lim_{x \rightarrow 5} 4
$$

$$
2\cdot (\lim_{x \rightarrow 5}x)^2 - 3 \cdot \lim_{x \rightarrow 5} x + \lim_{x \rightarrow 5} 4
$$

$$
2 \cdot 5^2 - 3 \cdot 5 + 4
$$

$$
2 \cdot 25 - 3 \cdot 5 + 4
$$

$$
50 - 15 + 4
$$

$$39$$

*2)*

$$
\lim_{x \rightarrow -2} \left( \frac{x^3 + 2x^2 - 1} {5 - 3x} \right)
$$

**R:**

$$
\frac {\lim_{x \rightarrow -2}(x^3 + 2x^2 - 1)} {\lim_{x \rightarrow -2}(5 - 3x)}
$$

$$
\frac
{\lim_{x \rightarrow -2}(x^3) + \lim_{x \rightarrow -2}(2x^2) - \lim_{x \rightarrow -2} 1}
{\lim_{x \rightarrow -2} 5 - \lim_{x \rightarrow -2}(3x)}
$$

$$
\frac
{\lim_{x \rightarrow -2}(x^3) + 2 \cdot \lim_{x \rightarrow -2}(x^2) - \lim_{x \rightarrow -2} 1}
{\lim_{x \rightarrow -2} 5 - 3 \cdot \lim_{x \rightarrow -2} x}
$$

$$
\frac
{(\lim_{x \rightarrow -2}x)^3 + 2 \cdot (\lim_{x \rightarrow -2}x)^2 - \lim_{x \rightarrow -2} 1}
{\lim_{x \rightarrow -2} 5 - 3 \cdot \lim_{x \rightarrow -2} x}
$$

$$
\frac
{(-2)^3 + 2 \cdot (-2)^2 - 1}
{5 - 3 \cdot (-2)}
$$

$$
\frac
{-8 + 2 \cdot 4 - 1}
{5 - 3 \cdot (-2)}
$$

$$
\frac
{-8 + 8 -1}
{5 + 6}
$$

$$
\frac{-1}{11}
$$

## Propriedade da substituição direta

Se $f(x)$ for uma função polinomial ou racional e $a$ estiver no domínio de $f(x)$, então:

$$\lim_{x \rightarrow a}f(x) = f(a)$$

Uma outra propriedade vem á tona quando analisamos funções que possuam indeterminação. Veja o caso da função:

$$f(x) = \frac{x^2 - 1}{x - 1}$$

Se fizermos $\lim_{x \rightarrow 1}\left(\dfrac{x^2 - 1}{x - 1}\right)$, não é possível usar substituição direta, por conta da indeterminação.

Nesse caso devemos modificar a função $f(x)$ por $\color{red} \text{fatoração}$. Então:

$$
\lim_{x \rightarrow 1}\left(\frac{x^2 - 1}{x - 1}\right) = 
\lim_{x \rightarrow 1}\left(\frac{(x + 1)\cancel{(x - 1)}}{\cancel{x - 1}}\right) = 
\lim_{x \rightarrow 1}(x + 1) = 2
$$

Logo:

Se $f(x) = g(x)$ quando $x \ne a$, então:

$$
\lim_{x \rightarrow a} f(x) = \lim_{x \rightarrow a} g(x)
$$

Desde que o limite exista.

Vale lembrar que:

$$
\lim_{x \rightarrow a} f(x) = L \text{, se, e somente se,} \\
\lim_{x \rightarrow a^-} f(x) = \lim_{x \rightarrow a^+} f(x)
$$

Outro teorema importantediz que: se $f(x) \le g(x)$, quando $x$ está próximo de $a$ e os limites de $f$ e $g$ existam quando $x \rightarrow a$, então:

$$
\lim_{x \rightarrow a}f(x) \le \lim_{x \rightarrow a} g(x)
$$

Decorre então o importante teorema:

## Teorema do confronto

Se $f(x) \le g(x) \le h(x)$, quando $x$ está próximo de $a$ e:

$$
\lim_{x \rightarrow a} f(x) = \lim_{x \rightarrow a} h(x) = L
$$

Então:

$$
\lim_{x \rightarrow a} g(x) = L
$$

**EX:** use o teorema do confronto para determinar o limite da função

$$\lim_{x \rightarrow 0}\left( x^2 \cdot \sin\left(\frac{1}{x}\right) \right)$$

**R:**

não é prático resolver este problema por tabela verdade, já que seu sinal oscila cada vez mais a medida que $x$ se aproxima de $a$.

$\bold x$ | $\bold{f(x)}$
-|-
$1$     | $0,841$
$0,5$   | $0,454$
$0,2$   | $-0,191$
$0,1$   | $-0,054$
$0,01$  | $-5E-3$
$0,001$ | $8E-4$

Logo usamos o teorema do confronto.

$$
-1 \le \sin \left( \frac{1}{x} \right) \le 1 \\
$$

$$
-x^2 \le x^2 \cdot \sin \left( \frac{1}{x} \right) \le x^2
$$

$$
\lim_{x \rightarrow 0}(-x^2) \le \lim_{x \rightarrow 0}\left(x^2 \cdot \sin \left(\frac{1}{x}\right)\right) \le \lim_{x \rightarrow 0}(x^2)
$$

$$
0 \le \lim_{x \rightarrow 0}\left(x^2 \cdot \sin \left(\frac{1}{x}\right)\right) \le 0
$$

$$
\lim_{x \rightarrow 0}\left(x^2 \cdot \sin \left(\frac{1}{x}\right)\right) = 0
$$
