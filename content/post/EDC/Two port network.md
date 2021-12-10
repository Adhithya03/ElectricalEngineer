---
title: "Two Port Network"
draft: true
mathjax : true
categories : ["EDC"]
author : adhithya
---

In order to predict the behaviour small signal transistor amplifier it is important to know the input impedance, output impedance, voltage gain etc. We can determine these parameters using *circuit resistance*, 
*$\beta$ $\left(\frac{I_C}{I_B}\right)$.*

> Since CE amplifier is most commonly used $\beta$ shown above.

This approach has following *advantages*
    
1. Easy.
    
2. Values are readily available.

Major *drawbacks*

- We can't get accurate results because input and output circuit of transistor are not completely independent. For eg. Rather input current being constant $\beta I_B$ it is affected by load resistance which is not taken into account in this approach.

- Output voltage $IR_L$ has effect on input circuit. So changes in output causes changes in input which is also not taken into account here.

One of the methods that takes into account all the effects of are **hybrid parameter** approach. In this there are 4 parameters 
    
    - One measured in OHM

    - One measured in MHO

    - Other two are dimensionless

These are called **h** or **hybrid parameters**, Since these parameters are of mixed dimensions they are called "Hybrid" which means mixed. 

Once these parameters are known formula can be developed for the input impedance, output impedance, voltage gain etc.

This approach has following *advantages*

1. It yields exact result since all the intereffects of the input and output circuit are taken into account.

2. These parameters can be easily measured.

## Hybrid parameters

<br>

*A Linear circuit is one in which resistances, inductances and capacitances remain fixed when voltage across them changes.*

Consider the Linear circuit shown below, This circuit has input voltage and current labelled $v_1$ and $i_1$.
This circuit also has output voltage and output current labelled $v_2$ and $i_2$. 

![Linear Circuit](/EDC/Linear_circuit.png)

- Note both current are assumed to flow *into* the box and voltage is +ve at upper terminal. These are standard convention and *do not necessarily* correspond to actual direction and polarity.

- When we analyse the circuit in which the voltage  


