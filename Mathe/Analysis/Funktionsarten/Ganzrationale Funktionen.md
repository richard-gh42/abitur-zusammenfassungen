# Ganzrationale Funktionen

## Definition

> Eine **ganzrationale Funktion** oder **Polynomfunktion** ist in der Mathematik eine Funktion, die als Summe von Potenzfunktionen mit natürlichen Exponenten beschrieben werden kann.
>
> — Wikipedia

Eine ganzrationale Funktion kann also wie folgt dargestellt werden:
$$
f(x) = a_{n}x^{n} + a_{n-1}x^{n-1} + \dots + a_{2}x^{2} + a–{1}x + a_{0}
$$
Hierbei gilt $n \in \mathbb{N}$ sowie $a_{n}, a_{n-1}, \dots, a_2, a_1, a_0 \in \mathbb{R}$ und $a_n \neq 0$.

- $n$ wird als Grad der Funktion bezeichnet.
- $a_{n}, a_{n-1}, \dots, a_2, a_1, a_0$ werden als Koeffizienten bezeichnet.
- $a_n$ ist der Leitkoeffizient.

## Grenzverhalten

Wie sich der Graph einer ganzrationalen Funktion verhält wenn $x$ gegen $\infty$ oder $-\infty$ geht, hängt davon ab, ob $a_n$ größer oder kleiner $0$ ist und ob $n$ grade oder ungrade ist.\
Es besteht folgender Zusammenhang:

|         | $n$ ist grade                             | $n$ ist ungrade                                                                 |
| ------- | ----------------------------------------- | ------------------------------------------------------------------------------- |
| $a_n<0$ | $f(x) \to \infty$ für $x \to \pm \infty$  | $f(x) \to \infty$ für $x \to \infty$ und $f(x) \to -\infty$ für $x \to -\infty$ |
| $a_n>0$ | $f(x) \to -\infty$ für $x \to \pm \infty$ | $f(x) \to -\infty$ für $x \to \infty$ und $f(x) \to \infty$ für $x \to -\infty$ |

## Symmetrie

Der Graph einer ganzrationalen Funktion ist Achsen symetrisch um die $y$-Achse wenn allle Exponenten grade sind. Er ist um den Nulpunkt punktsymetrisch, wenn alle Exponenten ungrade sind.

## Nullstellen

Die höchst mögliche Anzahl von Nullstellen die eine ganzrationale Funktion haben kann, entspricht ihrem Grad. Eine ganzrationale Funktion $n$ten Grades kann also $n$ Nullstellen haben.

Eine ganzrationale Funktion kann auch als Produkt von Linearfaktoren vorliegen. Das sieht z.B. so aus:
$$
f(x) = (x-3) \cdot (x+1)^2 \cdot (x+3)^3
$$
Hier ist es besonders leich die Nullstellen zu finden, da lediglch einer der Faktoren $0$ Ergeben muss.

Ganzrationale Funktionen können 3 Formen von Nullstellen haben.

1. Eine einfache Nullstelle\
   ![Einfache Nullstelle](../../../images/Mathe/Einfache%20Nullstelle.png)
2. Eine grade Nullstelle\
   ![Grade Nullstelle](../../../images/Mathe/Grade%20Nullstelle.png)
3. Eine ungrade Nullstelle (größer $1$)\
   ![Ungrade Nullstelle](../../../images/Mathe/Ungrade%20Nullstelle.png)

Die Namen beziehen sich auf die Exponenten bei der Linearfaktor-Form.
