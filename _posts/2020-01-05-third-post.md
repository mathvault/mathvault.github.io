---
title: "Third Post: Default Layout"
layout: default
author: Math Vault
permalink: /third-post/
category: Posts
toc: true
---

Just checking.

{% include toc %}

## A Dummy Section

[Download PDF](#){: .btn .btn--success .btn--large} [Primary Button](#){: .btn .btn--x-large} [Warning Button](#){: .btn .btn--warning} [Danger Button](#){: .btn .btn--danger} [Info Button](#){: .btn .btn--info}

## Math Symbols Extravaganza

### Math Mode

Dollar sign, slash-parenthesis: $a+b=c$, \( a+b=c \)

Double dollar-sign, slash-bracket: $$a+b=c$$, \[ a+b=c \] 

### New Commands / Environments

\R and \ddx commands: $\newcommand{\R}{\mathbb{R}} \newcommand{\ddx}{\dfrac{d}{dx}} \R  \ddx$

King environment: $\newenvironment{king}{\text{King environment starts with this}}{\text{... and ends with this}} \begin{king}\end{king}$

$$ Spacing with \\ and \newline

Line breaking doesn't work in single-line math mode. Stripslash with double \

\\: $a \\ b$

\newline: $a \newline b$

\[ abc \\ def \]

\[ abc \newline def \]

### Color package

\color{blue}: ${\color{blue} Blue}$

Colorbox: $\colorbox{red}{This should be red.}$

\textcolor: $\textcolor{brown}{\text{Textcolor command is here}}$

Fcolorbox: $\fcolorbox{5em}{brown}{There's a box around this}$

Definecolor: $\definecolor{navyblue}{RGB}{13,55, 212} {\color{navyblue} navyblue}$

### Bbox / Cancel / Boldsymbol / Enclose extensions

Require extension/command not needed.

\bbox: $\bbox[pink, 5em]{E=mc^2}$

\cancel: $\cancel{\text{This should be cancelled.}}$

\boldsymbol: $\boldsymbol{x=y+2}$

\enclose: $\enclose{longdiv}[mathcolor="red"]{1234567890}$

### Trig function commands

$\arcsin$, $\arccos$, $\arctan$

Commands from physic extension: $\require{physics} \arccsc$, $\arcsec$, $\arccot$, $\csch$, $\sech$

### Special Symbols

$\LaTeX, \TeX$

### Big Operators

$\displaystyle \sum, \prod, \frac{1}{2}, \tfrac{111}{222}, \int, \iiint, \binom{123}{456}, \dbinom{aaa}{222}, \tbinom{aaa}{bbb}$

### Operators

$\sqrt[5]{x^2+1}, \pm,$

\DeclareMathOperator: $\DeclareMathOperator{span}{span} \span(A)$

\operatorname: $\operatorname{Hom}$

### Relations

$\ge, \le$

### Dots

$\dot{u}$, $\dots$, $\cdot$, $\cdots$, $\ldots$, $\ddddot{ABC}$

### Ornaments

$\stackrel{ff}{aa}, \vec{v}, \underline{hehehe}, \overline{hehehe}, \overbrace{It's on the top}, \underbrace{At the bottom}, \xleftarrow{Very looooooooooooooooooooooooooog} \xrightarrow[Dooooooooooooown there]{}$

$\implies, \impliedby, \mapsto, \overleftrightarrow{Left Right Arrow}, \overset{top}{ggg}$

$\sideset{aaa}{aaaa}, \sum_{\substack{fff \\ fff}}, \underparen{it's under}, \overparen{It's over}, \widehat{fffffff}, \widetilde{ffffff}$

Boxed command: $\boxed{E=mc^2}$

### Verbatim

$\verb,Everything in verbatim...,$

### Table / Array /Matrix / Pmatrix / Bmatrix / Vmatrix / vmatrix/ Smallmatrix
Equations

\begin{equation} 1 + 2 + \cdots + (n-1) + n = \dfrac{n (n+1)}{2} \label{cat} \end{equation}

\eqref and \ref: In the equation \eqref{cat}, we mentioned that \ref{cat}...

### Align / Multline / Gather / Flalign / Cases
Align

\begin{align} 1 + 2 & = 2 + 1 & \text{(Commutativity of addition)} \\ & = 3 & (\text{Magic!}) \end{align}

### Gather

\begin{gather} abc \\ def \end{gather}


