---
layout: post
title:  LaTeX Test
date:   2014-12-11 15:25:00
categories: latex

equations:
- a^2
- a_2
- 10^{30} a^{2+2}
- a_{i,j} b_{f'}
- x_2^3
- "{x_2}^3"
- 10^{10^{8}}
- \sideset{_1^2}{_3^4}\prod_a^b
- "{}_1^2\\!\\Omega_3^4"
- \overset{\alpha}{\omega}
- \underset{\alpha}{\omega}
- \overset{\alpha}{\underset{\gamma}{\omega}}
- \stackrel{\alpha}{\omega}
- x', y'', f', f''
- x^\prime, y^{\prime\prime}
- \dot{x}, \ddot{x}
- \hat a \ \bar b \ \vec c
- \overrightarrow{a b} \ \overleftarrow{c d} \ \widehat{d e f}
- \overline{g h i} \ \underline{j k l}
- \overset{\frown} {AB}
- A \xleftarrow{n+\mu-1} B \xrightarrow[T]{n\pm i-1} C
- \overbrace{ 1+2+\cdots+100 }^{5050}
- \underbrace{ a+b+\cdots+z }_{26}
- \sum_{k=1}^N k^2
- \textstyle \sum_{k=1}^N k^2
- \frac{\sum_{k=1}^N k^2}{a}
- \frac{\displaystyle \sum_{k=1}^N k^2}{a}
- \frac{\sum\limits^{^N}_{k=1} k^2}{a}
- \prod_{i=1}^N x_i
- \textstyle \prod_{i=1}^N x_i
- \coprod_{i=1}^N x_i
- \textstyle \coprod_{i=1}^N x_i
- \lim_{n \to \infty}x_n
- \textstyle \lim_{n \to \infty}x_n
- \int\limits_{1}^{3}\frac{e^3/x}{x^2}\, dx
- \int_{1}^{3}\frac{e^3/x}{x^2}\, dx
- \textstyle \int\limits_{-N}^{N} e^x\, dx
- \textstyle \int_{-N}^{N} e^x\, dx
- \iint\limits_D \, dx\,dy
- \iiint\limits_E \, dx\,dy\,dz
- \iiiint\limits_F \, dx\,dy\,dz\,dt
- \iint_D \, dx\,dy
- \iiint_E \, dx\,dy\,dz
- \iiiint_F \, dx\,dy\,dz\,dt
- \int_{(x,y)\in C} x^3\, dx + 4y^2\, dy
- \oint_{(x,y)\in C} x^3\, dx + 4y^2\, dy
- \bigcap_{i=_1}^n E_i
- \bigcup_{i=_1}^n E_i
- \left ( \frac{1}{2} \right )
---

|---
| Equation | Rendered
|:- :-{% for equation in page.equations %}
|`{{equation}}`|$$\displaystyle{ {{equation}} }$$  {% endfor %}
