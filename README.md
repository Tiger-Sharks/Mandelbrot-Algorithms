# Mandelbrot-Algorithms

This repository contains codes for generating the Mandelbrot Set, a famous fractal that exibits complex and beautiful patterns, to stress test your system's CPU. The Mandelbrot Set is defined by the equation z^n + c = 0, where n is a complex number and c is a constant. The set consists of all the points (z, c) that do not escape to infinity after repeated iterations of the equation.

The repository will showcase algorithm to plot the Mandelbrot Set in various languages, such as Python, PHP, and Java.

If you are interested in learning more about the Mandelbrot Set and its properties, do check out some of the resources listed <a href="https://en.wikipedia.org/wiki/Plotting_algorithms_for_the_Mandelbrot_set"> on this topic page</a>.

You also can run the the code yourself by the given set of instructions and see how it works.

## Instructions
1) Open up the terminal in the current working directory of the code.

2) Type the following command in accordance to you Operating System (Considering you saved the file by the name of "Mandelbrot.py")

For Windows (Powershell):
```
Measure-Command { python .\ Mandelbrot.py 16000 }
```