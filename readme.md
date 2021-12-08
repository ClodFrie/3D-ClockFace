# ReadMe

Create a clock with LaTeX expressions as numerals. 

## Generate SVGs based on LaTeX expressions

https://viereck.ch/latex-to-svg/


### Primary Numbers
12 = \int_{1}^{e^2}\frac{6}{x} \, \textrm{d}x
3 = \approx \frac{\pi+e}{2}
6 = 3!
9 = \sqrt[\leftroot{2}\uproot{3}2]{81} || 1001_2 || \sum_{k=0}^{2}3\,k
### Secondary Numbers
* unused expressions: lim, inf, sup, sin(),cos(),tan()
1 = -e^{-i\,\pi}
2 = \sum_{k=0}^{\infty}\left(\frac{1}{2}\right)^k
4 = 100_2
5 = \sqrt{3^2+4^2}
7 = \sqrt{42+7}
8 = 10_8
10 = \ln\left(e^{10}\right)
11 = B_{16}

## SVG in FreeCAD

Import and create an object (https://www.youtube.com/watch?v=Aqz6TFfOjiQ) and export to stl.

## PrusaSlicer

Scale up 7x in XY and to 10mm in Z and slice in "Vase Mode". Print each item separately, no top, no bottom layer

* character 100%
* exponent 65% 
* exponent of exponent 50%
