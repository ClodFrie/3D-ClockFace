# ReadMe

Create a clock with LaTeX expressions as numerals. 

## Generate SVGs based on LaTeX expressions

https://viereck.ch/latex-to-svg/

### Primary Numbers
<img src="https://render.githubusercontent.com/render/math?math=\color{red}12=\int_{1}^{e^2}\frac{6}{x}\,\textrm{d}x">
<img src="https://render.githubusercontent.com/render/math?math=\color{red}3=\approx\frac{\pi+e}{2}">
<img src="https://render.githubusercontent.com/render/math?math=\color{red}\prod_{1}^3=k">
<img src="https://render.githubusercontent.com/render/math?math=\color{red}9=\sqrt[\leftroot{2}\uproot{3}2]{81}\, ||\, 1001_2\, ||\, \sum_{k=0}^{2}3\,k">
### Secondary Numbers
* unused expressions: lim, inf, sup, sin(),cos(),tan()
<img src="https://render.githubusercontent.com/render/math?math=\color{red}1=-e^{-i\,\pi}">
<img src="https://render.githubusercontent.com/render/math?math=\color{red}2 = \sum_{k=0}^{\infty}\left(\frac{1}{2}\right)^k">
<img src="https://render.githubusercontent.com/render/math?math=\color{red}4 = 100_2">
<img src="https://render.githubusercontent.com/render/math?math=\color{red}5 = \sqrt{3^2+4^2}">
<img src="https://render.githubusercontent.com/render/math?math=\color{red}7 = \sqrt{42+7}">
<img src="https://render.githubusercontent.com/render/math?math=\color{red}8 = 10_8">
<img src="https://render.githubusercontent.com/render/math?math=\color{red}10 = \ln\left(e^{10}\right)">
<img src="https://render.githubusercontent.com/render/math?math=\color{red}11 = B_{16}">

## SVG in FreeCAD

Import and create an object (https://www.youtube.com/watch?v=Aqz6TFfOjiQ) and export to stl.

## PrusaSlicer

Scale up 7x in XY and to 10mm in Z and slice in "Vase Mode". Print each item separately, no top, no bottom layer

* character 100%
* exponent 65% 
* exponent of exponent 50%
