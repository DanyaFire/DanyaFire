## Аффинно-квадратичные функции в аффинно-евклидовых пространствах

---
mathmode\heartsuit

**Определение:**<a name="definition-0"></a> Пусть $\mathbb{A}$ - [аффинно-евклидово](https://mech-math-msu.github.io/lections/linear-algebra/lection-22.04.23#definition-0) пространство. [Аффинная система координат](https://mech-math-msu.github.io/lections/linear-algebra/lection-11.04.23#definition-3) $(O, e)$ *прямоугольная*, если [базис](https://mech-math-msu.github.io/lections/linear-algebra/lection-1-11.02.23#definition-7) $e$ - [ортонормирован](https://mech-math-msu.github.io/lections/linear-algebra/lection-25.03.23#definition-8).

**Определение:**<a name="definition-1"></a> Пусть $\mathbb{A}$ - [аффинно-евклидово](https://mech-math-msu.github.io/lections/linear-algebra/lection-22.04.23#definition-0) пространство. $Q$ - [аффинно-квадратичная функция](https://mech-math-msu.github.io/lections/linear-algebra/lection-29.04.23#definition-1), $q$ - [квадратичная форма](https://mech-math-msu.github.io/lections/linear-algebra/lection-18.03.23#definition-3) функции $Q$. Если [матрица](https://mech-math-msu.github.io/lections/linear-algebra/lection-18.03.23#definition-3) $B$ формы $q$ - диагональна в [прямоугольной системе координат](https://mech-math-msu.github.io/lections/linear-algebra/lection-25#definition-0)  $(O, e)$, то $(O, e)$ - *главные оси*.

**Теорема:**<a name="theorem-0"></a> Пусть $\mathbb{A}$ - [аффинно-евклидово](https://mech-math-msu.github.io/lections/linear-algebra/lection-22.04.23#definition-0) пространство. $Q: \mathbb{A} \to \mathbb{R}$ - [аффинно-квадратичная функция](https://mech-math-msu.github.io/lections/linear-algebra/lection-29.04.23#definition-1), которая не является [аффинно-линейной](https://mech-math-msu.github.io/lections/linear-algebra/lection-29.04.23#definition-0). Тогда существует [прямоугольная](https://mech-math-msu.github.io/lections/linear-algebra/lection-25#definition-0) система координат, в которой $Q$ имеет вид (такой вид единственен с точностью до перенумерации координат):

$$Q(a) = \lambda_1 x^2_1 + \ldots + \lambda_r x^2_r + \lambda$$

или

$$Q(a) = \lambda_1 x^2_1 + \ldots + \lambda_r x^2_r + 2 \lambda_{r + 1} x_{r + 1}$$

$\lambda_1, \ldots, \lambda_r$ не равны $0$, $\lambda_{r + 1} > 0$.

*Доказательство:*

Неприятно и долго $\,\,\,\,\blacksquare$

## Квадрики

---

**Определение:**<a name="definition-2"></a> Пусть $\mathbb{A}$ - [аффинное пространство](https://mech-math-msu.github.io/lections/linear-algebra/lection-11.04.23#definition-0) ассоциированное с [векторным пространством](https://mech-math-msu.github.io/lections/linear-algebra/lection-1-11.02.23#definition-0) $V$ над полем $F$ и $\operatorname{char}F \ne 2$, $Q$ - [аффинно-квадратичная функция](https://mech-math-msu.github.io/lections/linear-algebra/lection-29.04.23#definition-1). Множество $\Gamma(Q) = \{a \in \mathbb{A}: \,\,\,\, Q(a) = 0\}$, если оно не пустое и не является плоскостью - *квадрика* или *гиперповерхность второго порядка*.

**Утверждение:**<a name="statement-0"></a> Любая [прямая](https://mech-math-msu.github.io/lections/linear-algebra/lection-11.04.23#definition-5) либо целиком лежит в [квадрике](https://mech-math-msu.github.io/lections/linear-algebra/lection-25#definition-2), либо пересекается с ней не более, чем в двух [точках](https://mech-math-msu.github.io/lections/linear-algebra/lection-11.04.23#definition-0).

*Доказательство:* 

Прямая - это плоскость размерности $1$, то есть $p = a_0 + <v>, \,\,\,\, v \in V$. Произвольная точка на прямой - это $a = a_0 + t v$.

$$0 = Q(a) = Q(a_0 + t v) = Q(a_0) + q(tv) + 2l(tv) = t^2 q(v) + 2 t l(v) + Q(a_0) \,\,\,\,\blacksquare$$

**Определение:**<a name="definition-3"></a>  [Точка](https://mech-math-msu.github.io/lections/linear-algebra/lection-11.04.23#definition-5) $O$ *центр* [квадрики](https://mech-math-msu.github.io/lections/linear-algebra/lection-25#definition-2) $\Gamma(Q)$, если $\forall v: \,\,\,\, O + v \in \Gamma(Q) \,\,\,\, O - v \in \Gamma(Q)$.

**Определение:**<a name="definition-4"></a> Пусть $O$ [центр](https://mech-math-msu.github.io/lections/linear-algebra/lection-25#definition-3) [квадрики](https://mech-math-msu.github.io/lections/linear-algebra/lection-25#definition-2) $\Gamma(Q)$. Если $O \in \Gamma(Q)$, то $O$ - *вершина* $\Gamma(Q)$.

**Утверждение:**<a name="statement-1"></a> Пусть $\Gamma(Q)$ [квадрика](https://mech-math-msu.github.io/lections/linear-algebra/lection-25#definition-2), $O$ - ее [вершина](https://mech-math-msu.github.io/lections/linear-algebra/lection-25#definition-4), $a \in \Gamma(Q), \,\,\,\, a \ne O$. Тогда [прямая](https://mech-math-msu.github.io/lections/linear-algebra/lection-1-13.02.23#definition-1) $l = O + <\overline{Oa}> \subset \Gamma(Q)$(прямая, проходящая через $O$ и $a$ лежит в квадрике).

*Доказательство:*

$O$ - вершина, следовательно $O -\overline{Oa} \in Q$. Значит минимум три точки прямой лежат на квадрике, следовательно по предыдущему утверждению $l \subset \Gamma(Q) \,\,\,\,\blacksquare$

**Утверждение:**<a name="statement-2"></a> Любая [квадрика](https://mech-math-msu.github.io/lections/linear-algebra/lection-25#definition-2) содержит [точку](https://mech-math-msu.github.io/lections/linear-algebra/lection-11.04.23#definition-0), не являющуюся ее [вершиной](https://mech-math-msu.github.io/lections/linear-algebra/lection-25#definition-4).

*Доказательство:*

Пусть это неправда. Докажем, что $\Gamma(Q)$ в таком случае будет плоскостью. Пусть $a \in \Gamma(Q), \,\,\,\, U = <\overline{ab}: \,\,\,\, b \in \Gamma(Q)>$.

Докажем, что $U$ - векторное подпространство $V$. $\forall u_1, u_2 \in U \,\,\,\, \exists b_1, b_2 \in \Gamma(Q): \,\,\,\, u_1 = \overline{ab_1}$ и $u_2 = \overline{ab_2}$. Так как любая точка - вершина $b_1 + <\overline{b_1b_2}> \subset \Gamma(Q) \Rightarrow c = b_1 + \lambda \overline{b_1b_2} \in \Gamma(Q) \Rightarrow \overline{ac} = \overline{ab_1} + \lambda \overline{b_1b_2} \in \Gamma(Q) \Rightarrow$
$\Rightarrow u_1 + \lambda(u_2 - u_1) \in \Gamma(Q) \,\,\,\,\blacksquare$

## Пропорциональные аффинно-квадратичные функции и квадрики

---

**Теорема:**<a name="theorem-1"></a> Пусть $\Gamma = \Gamma(Q_1) = \Gamma(Q_2)$, $\Gamma$ - [квадрика](https://mech-math-msu.github.io/lections/linear-algebra/lection-25#definition-2), $Q_1, Q_2$ - [аффинно-квадратичные](https://mech-math-msu.github.io/lections/linear-algebra/lection-29.04.23#definition-1) функции на аффинном пространстве над бесконечным полем характеристики отличной от $2$. Тогда $Q_1$ пропорциональна $Q_2$.

*Доказательство:*

фуу

**Определение:**<a name="definition-5"></a> [Квадрики](https://mech-math-msu.github.io/lections/linear-algebra/lection-25#definition-2) $\Gamma_1$ и $\Gamma_2$ *аффинно-эквивалентны* ($\operatorname{GA}$-*эквивалентны*), если существует [аффинный оператор](https://mech-math-msu.github.io/lections/linear-algebra/lection-17.04.23#definition-1) $\Phi$, такой, что $\Phi(\Gamma_1) = \Gamma_2$.

**Теорема:**<a name="theorem-2"></a> Пусть $Q_1, Q_2$ - [аффинно-квадратичные функции](https://mech-math-msu.github.io/lections/linear-algebra/lection-29.04.23#definition-1) на аффинном пространстве над бесконечным полем характеристики отличной от $2$. $Q_1$ и $Q_2$ задают [аффинно-эквивалентные](https://mech-math-msu.github.io/lections/linear-algebra/lection-25#definition-5) квадрики $\Leftrightarrow$ $Q_1$ пропорциональна $Q_2$ в некоторых системах координат.

*Доказательство:* 

**Определение:**<a name="definition-6"></a> [Квадрики](https://mech-math-msu.github.io/lections/linear-algebra/lection-25#definition-2) $\Gamma_1$ и $\Gamma_2$ *изометрически эквивалентны* ($\operatorname{Isom}$-*эквивалентны*), если существует [ортогональный аффинный оператор](https://mech-math-msu.github.io/lections/linear-algebra/lection-24.04.23#definition-1) $\Phi$, такой, что $\Phi(\Gamma_1) = \Gamma_2$.

**Теорема:**<a name="theorem-3"></a> Пусть $Q_1, Q_2$ - [аффинно-квадратичные функции](https://mech-math-msu.github.io/lections/linear-algebra/lection-29.04.23#definition-1) на аффинном пространстве над бесконечным полем характеристики отличной от $2$. $Q_1$ и $Q_2$ задают [изометрически эквивалентные](https://mech-math-msu.github.io/lections/linear-algebra/lection-25#definition-6) квадрики $\Leftrightarrow$ $Q_1$ пропорциональна $Q_2$ в некоторых [прямоугольных](https://mech-math-msu.github.io/lections/linear-algebra/lection-25#definition-0) системах координат.

*Доказательство:*

