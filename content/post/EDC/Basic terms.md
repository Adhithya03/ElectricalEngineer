---
title: "Some Basic Terms"
draft: false
mathjax : true
categories : ["EDC"]
author : adhithya
---


# Small signal

If input signal to be amplified doesn't disturb the *Q-point* (operating point) of the transistor, it is small signal. 

---
## Coupling capacitor and Bypass capacitor

![Coupling and bypass](/EDC/Transistor.png)


### Coupling capacitor

- Coupling capacitor *couples* one stage of transistor amplifier to another. 

- It has an important purpose of ***blocking** DC signal which will disturb the *Q-point* of transistor.   

>*Since capacitor will act as open circuit (infinite resitance) for DC signal. [Reason](https://www.electricaltechnology.org/2019/10/why-capacitor-block-dc-pass-ac.html)  

---

### Bypass capacitor

![Bypass](/EDC/Transistor_bypass.png)

> Why bypass capacitor ?


The goal of amplification is to, well, "Amplify" the given input signal. Let's say without bypass capacitor our amplified AC signal need to go through resistor $R_E$ which eats up some of our gain. 

To get most gain out of the amplifier, we need to channel our output signal to some other path out of resistor $R_E$ this is where bypass capacitor saves the day. We know capacitor offers *low reactance* to AC and very high(infinite) reactance to DC. Exploiting this concept we add capacitor parallel to resistor $R_E$.   

> Techinal explanation

- Since *capacitive reactance* is *much smaller* when compared to resistance $R_E$ and hence the AC signal will prefer going through bypass capacitor. Stated another way, this capacitor is effectively shorted to ground.

