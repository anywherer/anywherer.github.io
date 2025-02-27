---
title: 
description: 
aliases: [unit circle]
tags: []
created: 2024-11-19T21:16:10
modified: 2025-02-25T17:07:23
permalink:
---

## unit circle

in trigonometry, the unit circle has the equation $x^2+y^2=1$

figure: the unit circle graphed
![[unit circle 2024-07-09 14.14.59.excalidraw.svg|396]]
%%[[unit circle 2024-07-09 14.14.59.excalidraw.md|🖋 Edit in Excalidraw]]%%






Figure: It's too much, I know.
![[Unit-circle_sin_cos_tan_cot_exsec_excsc_versin_vercos_coversin_covercos.svg]]

the unit circle is useful in trigonometry because it visualizes the outputs of the [[trigonometric functions|trig functions]] given an angle $\theta$

by the way when we measure angles, we use either degrees or radians. if an angle has no units, it's in radians

for how to evaluate the sine and cosine, see [[how to evaluate trig functions]]



here are just some more values you should ignore

| radians           | degrees | cos - x value        | sin - y value        |
| ----------------- | ------- | -------------------- | -------------------- |
| 0                 | 0       | 1                    | 0                    |
| $\dfrac{1}{6}\pi$ | 30      | $\dfrac{\sqrt3}{2}$  | $\dfrac{1}{2}$       |
| $\dfrac{1}{4}\pi$ | 45      | $\dfrac{\sqrt2}{2}$  | $\dfrac{\sqrt2}{2}$  |
| $\dfrac{1}{3}\pi$ | 60      | $\dfrac{1}{2}$       | $\dfrac{\sqrt3}{2}$  |
| $\dfrac{1}{2}\pi$ | 90      | 0                    | 1                    |
| $\dfrac{2}{3}\pi$ | 120     | $\dfrac{-1}{2}$      | $\dfrac{\sqrt3}{2}$  |
| $\dfrac{3}{4}\pi$ | 135     | $-\dfrac{\sqrt2}{2}$ | $\dfrac{\sqrt2}{2}$  |
| $\dfrac{5}{6}\pi$ | 150     | $\dfrac{-\sqrt3}{2}$ | $\dfrac{1}{2}$       |
| $\pi$             | 180     | -1                   | 0                    |
| $\dfrac{5}{4}\pi$ | 225     | $-\dfrac{\sqrt2}{2}$ | $-\dfrac{\sqrt2}{2}$ |
| $\dfrac{6}{4}\pi$ | 270     | 0                    | -1                   |
| $\dfrac{7}{6}\pi$ | 210     | $\dfrac{-\sqrt3}{2}$ | $\dfrac{-1}{2}$      |
| $\dfrac{7}{2}\pi$ | 315     | $\dfrac{\sqrt2}{2}$  | $-\dfrac{\sqrt2}{2}$ |
| $\dfrac{4}{3}\pi$ | 240     | $\dfrac{-1}{2}$      | $\dfrac{-\sqrt3}{2}$ |
| $\dfrac{9}{4}\pi$ | 360     | 1                    | 0                    |

In mathematics, the trigonometric functions are functions which relate an angle of a right-angled triangle to ratios of two side lengths.

The unit circle is used to visualize the outputs of the trig functions.

In case you are wondering why trig functions are important, we use them a lot in geometric problems and calculus.

### introduction

some easy applications of basic trigonometry is in [[introduction to trigonometry]]

figure: we should be familiar with triangle stuff
![[trigonometric functions 2024-07-09 12.38.35.excalidraw.svg|316]]
%%[[trigonometric functions 2024-07-09 12.38.35.excalidraw.md|🖋 Edit in Excalidraw]]%%

We probably know soh cah toa already

sine
$\sin(\theta)=\dfrac{\text{opposite}}{\text{hypotenuse}}$

cosine
$\cos(\theta)=\dfrac{\text{adjacent}}{\text{hypotenuse}}$

tangent
$\tan(\theta)=\dfrac{\text{opposite}}{\text{adjacent}}$
$\tan(\theta)=\dfrac{\sin(\theta)}{\cos(\theta)}$


[[how to solve equations with trig functions]]

[[how to evaluate trig functions]]
[[how to graph trig functions]]

### notation

trig functions can leave out the brackets where appropriate, like depicting $\sin(x)$ as $\sin x$

a superscript right after the name of a trig function denotes exponentiation, for example, $\sin^2(x)=(\sin(x))^2$
this is different to [[function composition]] where $f^2(x)=(f\circ f)(x)=f(f(x))$

### reciprocal trig functions

sine, cosine and tangent trig functions have their [[multiplicative inverse|reciprocals]]

related
- [[how to evaluate reciprocal trig functions]]
- [[how to graph reciprocal trig functions]]


cosecant
$\csc(\theta)=\dfrac{1}{\sin(\theta)}$

secant
$\sec(\theta)=\dfrac{1}{\cos(\theta)}$

cotangent
$\cot(\theta)=\dfrac{1}{\tan(\theta)}$
$\cot(\theta)=\dfrac{\cos(\theta)}{\sin(\theta)}$

### inverse trig functions

related
- [[how to evaluate inverse trig functions]]
- [[how to graph inverse trig functions]]

the inverse trig functions are not the same as trig functions

whereas in trig function you input an angle and get a ratio, with inverse trig functions you input a ratio and get an angle

since the trig functions are not one-to-one (see [[relation]]), the inverse trig functions have to restrict their domain

inverse sine is only a segment of the sine function, the $[-\dfrac{\pi}{2},\dfrac{\pi}{2}]$ segment, and it's the inverse function of this segment
remember the range and how the output of inverse tan always has the same sign as the input

$\sin(x)$
domain: $\mathbb{R}$
range: $[-1,1]$

$\sin^{-1}(x)$
domain: $[-1,1]$
range: $[-\dfrac{\pi}{2},\dfrac{\pi}{2}]$

the inverse cosine is similar
remember the range and how the output of inverse cosine is always non-negative

$\cos(x)$
domain: $\mathbb{R}$
range: $[-1,1]$

$\cos^{-1}(x)$
domain: $[-1,1]$
range: $[0,\pi]$

the inverse tan has the same range as inverse sine
remember the range and how the output of inverse tan always has the same sign as the input

$\tan(x)$
domain: $\mathbb{R}$
range: $\mathbb{R}$

$\tan^{-1}(x)$
domain: $\mathbb{R}$
range: $[-\dfrac{\pi}{2},\dfrac{\pi}{2}]$

## trig function

In mathematics, the trigonometric functions are functions which relate an angle of a right-angled triangle to ratios of two side lengths.

The unit circle is used to visualize the outputs of the trig functions.

In case you are wondering why trig functions are important, we use them a lot in geometric problems and calculus.

### introduction

some easy applications of basic trigonometry is in [[introduction to trigonometry]]

figure: we should be familiar with triangle stuff
![[trigonometric functions 2024-07-09 12.38.35.excalidraw.svg|316]]
%%[[trigonometric functions 2024-07-09 12.38.35.excalidraw.md|🖋 Edit in Excalidraw]]%%

We probably know soh cah toa already

sine
$\sin(\theta)=\dfrac{\text{opposite}}{\text{hypotenuse}}$

cosine
$\cos(\theta)=\dfrac{\text{adjacent}}{\text{hypotenuse}}$

tangent
$\tan(\theta)=\dfrac{\text{opposite}}{\text{adjacent}}$
$\tan(\theta)=\dfrac{\sin(\theta)}{\cos(\theta)}$


[[how to solve equations with trig functions]]

[[how to evaluate trig functions]]
[[how to graph trig functions]]

### notation

trig functions can leave out the brackets where appropriate, like depicting $\sin(x)$ as $\sin x$

a superscript right after the name of a trig function denotes exponentiation, for example, $\sin^2(x)=(\sin(x))^2$
this is different to [[function composition]] where $f^2(x)=(f\circ f)(x)=f(f(x))$

### reciprocal trig functions

sine, cosine and tangent trig functions have their [[multiplicative inverse|reciprocals]]

related
- [[how to evaluate reciprocal trig functions]]
- [[how to graph reciprocal trig functions]]


cosecant
$\csc(\theta)=\dfrac{1}{\sin(\theta)}$

secant
$\sec(\theta)=\dfrac{1}{\cos(\theta)}$

cotangent
$\cot(\theta)=\dfrac{1}{\tan(\theta)}$
$\cot(\theta)=\dfrac{\cos(\theta)}{\sin(\theta)}$

### inverse trig functions

related
- [[how to evaluate inverse trig functions]]
- [[how to graph inverse trig functions]]

the inverse trig functions are not the same as trig functions

whereas in trig function you input an angle and get a ratio, with inverse trig functions you input a ratio and get an angle

since the trig functions are not one-to-one (see [[relation]]), the inverse trig functions have to restrict their domain

inverse sine is only a segment of the sine function, the $[-\dfrac{\pi}{2},\dfrac{\pi}{2}]$ segment, and it's the inverse function of this segment
remember the range and how the output of inverse tan always has the same sign as the input

$\sin(x)$
domain: $\mathbb{R}$
range: $[-1,1]$

$\sin^{-1}(x)$
domain: $[-1,1]$
range: $[-\dfrac{\pi}{2},\dfrac{\pi}{2}]$

the inverse cosine is similar
remember the range and how the output of inverse cosine is always non-negative

$\cos(x)$
domain: $\mathbb{R}$
range: $[-1,1]$

$\cos^{-1}(x)$
domain: $[-1,1]$
range: $[0,\pi]$

the inverse tan has the same range as inverse sine
remember the range and how the output of inverse tan always has the same sign as the input

$\tan(x)$
domain: $\mathbb{R}$
range: $\mathbb{R}$

$\tan^{-1}(x)$
domain: $\mathbb{R}$
range: $[-\dfrac{\pi}{2},\dfrac{\pi}{2}]$
