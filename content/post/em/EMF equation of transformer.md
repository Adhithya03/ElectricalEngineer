---
title: "EMF Equation of Transformer"
draft: false
mathjax : true
categories : ["EM"]
author : adhithya
---

When sinusoidal voltage is applied to primary winding of the transformer a sinusoidal flux is produced in the iron core (as shown in figure below), Which links with primary and secondary winding.

![Flux](/EM/SinFlux.png)

---


Let , $\phi_m$ = Maximum flux produced in $Wb$;

$f$ = frequency of supply;

$N_1$ = number of turns of primary; 

$N_2$ = number of turns of secondary;

By faraday's law,

$$e = {d\lambda\over{dt}}$$

$$e = {N \hspace{0.1cm} d\phi\over{dt}}$$
$d\phi$ = $\phi_m-(-\phi_m)$

Since it take the flux a time of $\Large{t\over {2}}$or $\left(\Large{1\over {2f}}\right)$ seconds, to go from $\phi_m-(-\phi_m)$    

$dt = \Large{1\over {2f}}$

**Average emf** induced e is 

$$e = {N  \hspace{0.1cm}  2\phi_m\over{1\over {2f}}}$$

$$e = N \hspace{0.1cm} 4f\phi_m  \hspace{0.1cm}  volt$$
[[RMS-Average FormFactor]]


Since , $$Form \hspace{0.1cm} Factor = \frac{V_{rms}}{V_{av}} = 1.11$$
$$V_{rms}  = Form \hspace{0.1cm} Factor \times  V_{av} $$
$$V_{rms}  = 1.11 \times  V_{av} $$
$$V_{rms}  = 1.11 \times  N \hspace{0.1cm} 4f\phi_m  \hspace{0.1cm}  volt $$
$$V_{rms}= 4.44 N \hspace{0.1cm} f\phi_m$$
R.M.S. value of emf induced in primary, 

$$E_{1}= 4.44  \hspace{0.1cm}  N_1  \hspace{0.1cm} f\phi_m$$
$|||^{ly}$  R.M.S. value of emf induced in secondary,
$$E_{2}= 4.44  \hspace{0.1cm} N_2  \hspace{0.1cm} f\phi_m$$

References : S.K. Sahdev

