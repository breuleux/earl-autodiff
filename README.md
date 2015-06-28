
earl-autodiff
=============

Autodiff macros for Earl Grey.

This wraps the [ad.js](https://github.com/iffsid/ad.js) package.

Usage:

    require-macros:
       earl-autodiff -> autodiff

    autodiff cube(x) =
       x ** 3

    print cube(10)                            ;; 1000
    print cube.derivative-f(10)               ;; 300
    print cube.derivative-f.derivative-f(10)  ;; 60

