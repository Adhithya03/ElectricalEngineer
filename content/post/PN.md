---
title: "PN diode"
date : 2021-11-30T11:07:34+05:30
draft: false
mathjax : true
categories : ["EDC"]
---


### General operation

&nbsp;

###### Under Forward bias

- +ve potential reples holes in P region and -ve reples electrons in N region.

- Eventually appiled voltage is greater than barrier, cut-in or threshold voltage so *depletion* layer dissappear.

###### Under reverse bias

- Electrons or attracted to +ve terminal of battery, and electron holes are attracted to -ve negative terminal of battery. Now all the free charge carriers are gone, so we are left with only immobile charge carriers, a.k.a depletion layer.

- Width of depetion increases. As the reverse bias voltage increases.

- Due to thermally generated charge carriers reverse saturation current $I_0$ in order of  $\mu$ amps starts flowing.


[Avalanche multiplication]({{< ref "/post/Avalanche multiplication.md" >}})


---

### VI characteristics
&nbsp;
###### Forward bias
&nbsp;
- With $V = 0$ no $I_F$ as you gradually increase the $V$ the $V_F$ and $I_F$ gradually increases. When $V_F$ is increased to a value where the voltage across the diode reaches approx $0.7  V$ (Barrier voltage) $I_F$ increase rapidly.

	
		
- As you continue to increase $V_F$ , the current continues to increase very rapidly , but the voltage across the diode increases only gradually above $0.7V$  . This small increase in diode voltage above the varrier potential is due to voltage drop across the internal [Dynamic resistance]({{<ref "/post/Dynamic resistance.md">}}) of semiconductor material. 
	
###### Reverse bias

- When $V_{rev}$ is applied across a diode , there is only an extremely small current $I_R$ through the pn junction.


- With 0 Volts across the diode , there is no reverse current . As you graduallt increase the $V_{rev}$ , there is a very small reverse current  and the voltage across the diode increases. When the applied voltage is increased to a value where the reverse voltage across the diode $V_{R}$ reaches the breakdown value $V_{BR}$ , the reverse current begins to increase rapidly. As you continue to increase the bias voltage , The current continues to increase very rapidly , but the voltage across the diode is increases very little above $V_{BR}$. Breakdown , with exceptions is not a normal mode of operation for most pn junction devices.

---

### Temprature effects

	
###### Forward bias
	

As temprature increased , The $I_F$ ,increases for given forward voltage . Also , for a given value of forward current , the forward voltage decreases,
	
###### Reverse bias 

As temperature is increases , the reverse current increases.

---
	
### Peak inverse voltage

It is defined as the maximimum **reverse voltage** that a diode can withstand without destroying the junction.


	
## Used in 

- [Half wave rectifier]({{<ref "/post/Half wave rectifier.md">}})
- [Full wave bridge rectifier]({{<ref "/post/Full wave bridge.md">}})
- [Full wave center tapped rectifier]({{<ref "/post/Full wave center tapped.md">}})

