# Kurvendiskusion

## Monotonie

Monotie beschreibt die Steigung eines Graphen. Ein Graph oder Abschnitt eines Graphen der Konstant steigt, ist streng monoton steigend. Selbiges gilt für fallende Graphen oder Abschnitte, diese fallen streng monoton.

Dabei ist nicht relevant wie stark die Steigung oder der Fall ist, sondern nur ob der Graph steigt oder fällt.\
Enthält der Graph auch Stellen mit einer Steigung von $0$ ist er dennoch monoton solange er keine negative und positive Steigung enthält, er ist dann jedoch nicht mehr streng monoton.

Die Bedingung für Monotonie sind also:

|              | streng      | nicht streng   |
| ------------ | ----------- | -------------- |
| **Steigung** | $f'(x) > 0$ | $f'(x) \geq 0$ |
| **Fall**     | $f'(x) < 0$ | $f'(x) \leq 0$ |

Ein Graph kann in einem Abschnitt monoton Steigen und in einem anderen monoton fallen.

## Extrem- und Sattelstellen

Extrem- und Sattelstellen sind Stellen, an dennen ein Graph eine steigung von $0$ hat.

$$
f'(x) = 0
$$

- Wechselt die Steigung von $-$ zu $+$, handelt es sich um eine Tiefstelle.\
  Die Bedingungen für eine Tiefstelle sind also:

$$
f'(x) = 0 \wedge f''(x) > 0
$$

- Wechselt die Steigung von $+$ zu $-$, handelt sie sich um eine Hochstelle.\
  Die Bedingungen für eine Hochstelle sind also:

$$
f'(x) = 0 \wedge f''(x) < 0
$$

- Wechselt die Steigung nicht das Vorzeichen, handelt es sich um eine Sattelstelle.\
  Die Bedingungen für eine Sattelstelle sind also:

$$
f'(x) = 0 \wedge f''(x) = 0 \wedge f'''(x) \neq 0
$$

## Wendestellen

Wendestellen sind Stellen an denen der Funktionsgraph seine Krümmung wechselt. Es handelt sich um Extremstellen in der 1. Ableitung. Es gelten also folgende Bedingungen:

$$
f''(x) = 0 \wedge f'''(x) \neq 0
$$

Auch Sattelstellen sind daher Wendestellen.

## Tangenten und Normalen

### Tangenten

Eine Tangente ist eine Grade, die einem Funktionsgraphen an einee Stelle anliegt und seiner Steigung an dieser entspricht.

Die Funktion einer Tangente $g$ an der Stelle $x_0$ der Funktion $f$ lässt sich also wie folgt erschließen:

$$
g(x) = f(x_0) + f'(x_0) (x - x_0)
$$

Der Wert $g(x)$ entspricht somit dem Wert $f(x)$ an der Stelle $x_0$, plus dem Wert der Steigung von $f$ an der Stelle $x_0$ mal der diferenz von $x$ und $x_0$.

Umgestellt ergibt das:

$$
g(x) = f(x_0) - f'(x_0) \cdot x_0 + f'(x_0) \cdot x
$$

Wobei $f(x_0) - x_0 \cdot f'(x_0)$ konstant ist und somit zu einer Zahl wird.

### Normalen

Eine Normale ist eine Grade, die den Graphen an einer Stellescheidet und in einem rechten Winkel zur Tangente dieses Punktes steht. Dies ist der Fall wenn:

$$
Steigung_{Tangente} \cdot Steigung_{Normale} = -1
$$

$$
\implies Steigung_{Normale} = \frac{-1}{Steigung_{Tangente}}
$$

Dem entsprechend ist die Funktion der Normale $g$ an der Stelle $x_0$:

$$
g(x) = f(x_0) + \frac{-1}{f'(x_0)} (x - x_0)
$$

Oder:

$$
g(x) = f(x_0) - \frac{-1}{f'(x_0)} x_0 + \frac{-1}{f'(x_0)} x
$$
