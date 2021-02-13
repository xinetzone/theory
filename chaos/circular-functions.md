---
title: 三角函数
top: false
cover: false
toc: true
comments: true
lang: zh-CN
tags: 三角函数
categories: 数学
abbrlink: 5640f8b3
date: 2020-02-14 20:13:46
password:
summary:
---

## 1 基本公式

下面先介绍一些基本公式。

### 1.1 诱导公式

可以把 7 组诱导公式归结为 $k\cdot \frac \pi 2 \pm \alpha$（$k\in \mathbb{Z}$）的三角函数，用“奇变偶不变，符号看象限”记忆和理解。即 $k$ 为奇数时的三角函数值等于 $\alpha$ 的异名（正弦与余弦互换，正切与余切互换）函数值，前面加上把 $\alpha$ 看成锐角时原函数值的符号；$k$ 为偶数时的三角函数值等于 $\alpha$ 的同名函数值，前面加上把 $\alpha$ 看成锐角时原函数值的符号。

### 1.3 同角三角函数式的基本关系

1. 倒数关系：$\sin{\alpha} \cdot \csc{\alpha}=1$，$\cos{\alpha} \cdot \sec{\alpha}=1$，$\tan{\alpha} \cdot \cot{\alpha}=1$.
2. 商数关系：$\tan{\alpha} = \frac {\sin{\alpha}} {\cos{\alpha}}$.
3. 平方关系：$\sin^2{\alpha} + \cos^2{\alpha} = 1$，$1 + \tan^2{\alpha} = \sec^2{\alpha}$，$1 + \cot^2{\alpha} = \csc^2{\alpha}$.


### 1.4 周期性

$y=A\sin(\omega x + \varphi)$ 与 $y=A\cos(\omega x + \varphi)$ 的最小正周期是 $T = \frac{2\pi}{|\omega|}$；

$y=A\tan(\omega x + \varphi)$ 与 $y=A\cot(\omega x + \varphi)$ 的最小正周期是 $T = \frac{\pi}{|\omega|}$.

## 2 三角恒等式

1. $\sin{3\alpha} = 4\sin{\alpha} \sin(\frac{\pi} 3 - \alpha)  \sin(\frac{\pi} 3 + \alpha)$
2. $\cos{3\alpha} = 4\cos{\alpha} \cos(\frac{\pi} 3 - \alpha)  \cos(\frac{\pi} 3 + \alpha)$
3. $\tan{3\alpha} = 4\tan{\alpha} \tan(\frac{\pi} 3 - \alpha)  \tan(\frac{\pi} 3 + \alpha)$
4. $\tan{(\alpha + \beta + \gamma)} = \cfrac{\tan{\alpha}+ \tan{\beta} + \tan{\gamma} - \tan{\alpha} \tan{\beta} \tan{\gamma}}{1 - \tan{\alpha}\tan{\beta} - \tan{\beta}\tan{\gamma} - \tan{\gamma}\tan{\alpha}}$
5. $\sum_{k=0}^{n} \sin{(\alpha+ 2kd)} = \cfrac {\sin{((n+1)d)} \cdot \sin{(\alpha + nd)}} {\sin{d}}$
6. $\sum_{k=0}^{n} \cos{(\alpha+ 2kd)} = \cfrac {\sin{((n+1)d)} \cdot \cos{(\alpha + nd)}} {\sin{d}}$
7. $\arcsin(-x) = - \arcsin(x)$，$\arccos(-x) = \pi - \arccos(x)$，$x \in [-1,1]$
8. $\arctan(-x) = - \arctan(x)$，$arccot(-x) = \pi - arccot(x)$，$x \in \mathbb{R}$
9. $\arcsin{x} + \arccos{x} = \frac \pi 2$，$x\in [-1,1]$
10. $\arctan{x} + arccot{x} = \frac \pi 2$，$x\in \mathbb{R}$

## 3 三角形中的等式

$$
\begin{aligned}
&\tan{\alpha} + \tan{B} + \tan C = \tan A \cdot \tan B \cdot \tan C\\
&\cot A \cot B + \cot B \cot C + \cot C \cot A = 1\\
&\sin^2 A + \sin^2 B + \sin^2 C = 2(1+ \cos A \cos B \cos C)\\
&\cos^2 A + \cos^2 B + \cos^2 C = 1 - 2 \cos A \cos B \cos C\\
&\cfrac {\cot A + \cot B} {\tan A + \tan B} + \cfrac {\cot B + \cot C} {\tan B + \tan C} + \cfrac {\cot C + \cot A} {\tan C + \tan A} = 1
\end{aligned}
$$

## 4 三角形中的几个定理

设 $\triangle ABC$ 的边长为 $a, b, c$，所对的角为 $A, B, C$；$r, R$ 分别为其内切圆半径与外接圆半径，$p = \frac 1 2 (a + b+ c)$ 为半周长，$S$ 为其面积，则：

1. 正弦定理：

$$
\cfrac a {\sin{A}} = \cfrac b {\sin{B}} = \cfrac c {\sin{C}} = 2R
$$

2. 余弦定理：

$$
\begin{array}{c}
a^2 = b^2 + c^2 - 2bc \cos A\\
b^2 = c^2 + a^2 - 2ca \cos B\\
c^2 = a^2 + b^2 - 2ab \cos C
\end{array}
$$

3. 射影定理：

$$
\begin{array}{ccc}
a = b \cos C + c \cos B, &b = c \cos A + a \cos C, & c = a \cos B + b \cos A
\end{array}
$$

4. 欧拉（Euler）定理：

$OI^2 = R^2 - 2Rr$，其中 $O, I$ 分别为 $\triangle ABC$ 的外心与内心。

5. 半角公式：

$$
\begin{array}{c}
&\sin{\cfrac A 2} = \sqrt{\cfrac{(p-b)(p-c)}{bc}} \\
&\cos{\cfrac A 2} = \sqrt{\cfrac{p(p-a)}{bc}} 
\end{array}
$$

6. 几个等式：

$$
\begin{array}{c}
&\cfrac r R = 4 \sin{\cfrac A 2} \sin{\cfrac B 2} \sin{\cfrac C 2} = \cos A + \cos B + \cos C - 1\\
&\cfrac {r_a} R =  4 \sin{\cfrac A 2} \cos{\cfrac B 2} \cos{\cfrac C 2}
\end{array}
$$

其中 $r_a$ 为角 $\angle A$ 所对应的旁切圆半径。

7. 面积公式：

$$
\begin{aligned}
S &= \frac 1 2 ab \sin C\\
&= rp\\
&= \sqrt{p(p-a)(p-b)(p-c)}\\
&= 2R^2 \sin A \sin B \sin C\\
&= \cfrac {abc} {4R}\\
&= \frac 1 2 R^2 (\sin{2A} + \sin{2B}+ \sin{2C})\\
&= \cfrac{a^2 \sin B \sin C}{2 \sin(B+C)}
\end{aligned}
$$