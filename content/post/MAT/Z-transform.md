---
title: "Z Transform"
draft: false
mathjax : true
categories : ["MATHS"]
author : adhithya
---

1. What is $Z$ ?

$Z$ is a complex variable. 

Where $Z = e^{iwn}\hspace{0.2cm}$ but leave this for now. Just remember Z is a complex variable (since it has $i$ term in it's power).

---

2. What is sequence ?

A sequence just list of numbers. Some examples are given below, 

- $\\{1 , 2 , 3 , 4 , 5 ...\\}$ 

- $\\{500 , 1000 , 1500 , ...\\}$ 

- $\\{1, 1, 2, 3, 5, 8, 13, 21, 34, ...\\}$

Continuation dots ... at the end of each sequence are used to imply that the sequence does not end. Such a sequence is called an infinite
sequence to distinguish it from finite or terminating sequences.

The above sequences are [discrete](https://en.wikipedia.org/wiki/Discrete_time_and_continuous_time) sequences.
 

---

3. What Z-transform will do ?

Let us consider this sequence $\\{1 , 2 , 3 , 4 , 5 ...\\}$ as $U_n$

By definition of Z-Transform

$$Z\\{U_n\\} = \sum_{n=0}^\infty U_n z^{-n}$$

Let's substitute $U_n$ L.H.S. and R.H.S. 

$$Z\\{1 , 2 , 3 , 4 , 5 ...\\} = \sum_{n=0}^\infty \hspace{0.1cm} \\{1 , 2 , 3 , 4 , 5 ...\\} \hspace{0.1cm} z^{-n}$$

subs n = 0, 1 , 2 ...

$$Z\\{1 , 2 , 3 , 4 , 5 ...\\} = \frac{1}{z^0} + \frac{2}{z^1} + \frac{3}{z^2} + ...$$

$$Z\\{1 , 2 , 3 , 4 , 5 ...\\} = 1+ \frac{2}{z^1} + \frac{3}{z^2} + ...$$

Here is the important part,

Z-transform takes our sequence[of real numbers] in L.H.S and in R.H.S we get $\large\frac{2}{z}$ $\large\frac{3}{z^2}$ in the denominator there is $z$ which is complex variable so our Z-transform converted Real number sequence into *Z domain* (complex frequency-domain representation).

---


#### Our math sir recommended book for Z transform 

[Engineering mathematics](https://1lib.net/dl/6464649/7af324)

#### Further reading on Z transform

[Richard Baraniuk](https://cnx.org/contents/d2CEAGW5@15.4:Fs51m7cT@5/Z-Transform)

[Glyn James](https://1lib.net/dl/1204739/d62f94) Pg - 403

[Wikipedia](https://en.wikipedia.org/wiki/Z-transform)

---

