---
title: "Voltage and Current Source"
draft: false
mathjax : true
categories : ["EDC"]
author : adhithya
---

# Voltage source

## Ideal voltage source
- It produces and output voltage that does not depend on the value of load resistance. Simplest example is ideal battery. 

- It has zero internal resistance since current should pass through it. 

## Real Voltage source

- If load resistance approaches zero the current will be infinite, No voltage source will produce infinite current. Real voltage source will have internal resistance few of them are given below. 

- Internal resistance of a battery appears in series with load resistance.

- The maximum load current that the real voltage source can deliver is called shorted load current.

$$I_L = \frac{V_S}{R_S+R_L}$$

Where,

$I_L$ - Load current

$V_S$ - Source voltage

$R_L$ - Load resistance

$R_S$ - Internal resistance

|Component|Internal resistance|
|-|-|
|Flashlight battery|< $1 \Omega$|
|Car battery|< $0.1\Omega$|
|Electronic voltage source|< $0.01\Omega$|

---

# Current source

## Ideal current source

- Unlike voltage source, It has large internal resistance, furthermore, a current source produces an output current that does not depend on value of load resistance.

### Hypothetical example

- The simplest example of current source is combination of a battery (say $12 V$) and large source resistor (say $10M\Omega$).

$$I_L = \frac{V_S}{R_S+R_L}$$

#### When load resistance $R_L$ is zero, the current is 

$$I_L = \frac{12}{10M\Omega+0} = 1.2\mu A$$ 


#### When $R_L = 10K\Omega$

[$1000\;k\Omega  = 1 M\Omega$]

$$I_L = \frac{12}{10M\Omega+0.01M\Omega} = 1.1988\mu A$$ 

#### When $R_L = 100K\Omega$

$$I_L = \frac{12}{10M\Omega+0.1M\Omega} = 1.188\mu A$$

As we can see all the currents for various load resistance are very close to $1.2\mu A$.

**Practical current sources** are rarely built with battery and resistor because the large series resistance makes getting enough current for practical application is impossible. Instead, transistors and other devices are connected in such a way as to produce stiff current sources that can deliver amperes of load current.


Book I referred 
---

[Electronic principles MALVINO](https://1lib.net/dl/2829641/9c72b9)