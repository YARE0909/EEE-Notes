# Electrical And Electronics Engineering

<hr>

## **Basic Terminologies**

**Electric Voltage**
The force that pushes electrons through a conductor is known as electric voltage. AKA the potential energy of an electric supply stored in the form of electric charge

**Potential Difference**
The difference in electric voltage between two points
**Unit: Volts(V)**

**Current**
The rate of flow of charge
**Unit: Ampere(A)**

**Resistance**
Measure of opposition to current flow in an electrical circuit
**Unit: Ohm(&#x2126)**

**Power**
The rate at which electrical energy is converted to another form
In alternating current(AC there are 3 types of power:
- **Apparent Power**
	Total amount of power generated
	S = VI
	**Unit: Volt Ampere(VI)**
- **Reactive Power**
	 Corresponds to storage and retrieval of energy rather than consumption
	 Q = VIsin$\theta$
	 **Unit: Volt Ampere Reactive(VAR)**
- **Real Power**
	The amount of power that is actually used by the load
	 P = VIcos$\theta$
	 **Unit: Watt(W)**
	 	 
<hr>

## **Ohm's Law**
At constant temperature the current flowing through a conductor is directly proportional to the potential difference across the conductor

I &#8733 V
I = GV, where G is conductance
I = $\frac{1}{R}$V
V = IR, where R is proportionality constant

## **Resistance In Series**
When resistors are connected in series combination
the total resistance of the circuit is the sum of the individual resistances. This is because current remains constant throughout the circuit but the voltage varies

![[Pasted image 20230120204951.png]]

In the above circuit let the voltage at R<sub>1</sub>, R<sub>2</sub>, R<sub>3</sub> be V<sub>1</sub>, V<sub>2</sub>, V<sub>3</sub>
Let the total potential difference of the circuit by V<sub>eff</sub>

V<sub>eff</sub> = V<sub>1</sub> + V<sub>2</sub> + V<sub>3</sub>

According to Ohm's law
V<sub>eff</sub> = IR<sub>eff</sub>

Therefore,
V<sub>1</sub>, = IR<sub>1</sub>
V<sub>2</sub>, = IR<sub>2</sub>
V<sub>3</sub> = IR<sub>3</sub>

V<sub>eff</sub> = V<sub>1</sub> + V<sub>2</sub> + V<sub>3</sub>
IR<sub>eff</sub> = IR<sub>1</sub> + IR<sub>2</sub> + IR<sub>3</sub>

Taking I common and cancelling it we get

R<sub>eff</sub> = R<sub>1</sub> + R<sub>2</sub> + R<sub>3</sub>

## **Resistance In Parallel**
When resistors are connected in parallel combination the total resistance of the circuit is the sum of the reciprocal of the individual resistances. This is because the voltage remains constant throughout the circuit but the current varies

![[Pasted image 20230120210007.png]]

In the above circuit let the current at R<sub>1</sub>, R<sub>2</sub>, R<sub>3</sub> be I<sub>1</sub>, I<sub>2</sub>, I<sub>3</sub>
Let the total potential difference of the circuit by V<sub>eff</sub>

I<sub>eff</sub> = I<sub>1</sub> + I<sub>2</sub> + I<sub>3</sub>

According to Ohm's law

I<sub>eff</sub> = $\frac{V}{R_{eff}}$

Therefore
 I<sub>1</sub> = $\frac{V}{R_{1}}$
 I<sub>2</sub> = $\frac{V}{R_{2}}$
 I<sub>3</sub> = $\frac{V}{R_{3}}$

I<sub>eff</sub> = I<sub>1</sub> + I<sub>2</sub> + I<sub>3</sub>
$\frac{V}{R_{eff}}$ = $\frac{V}{R_{1}}$ + $\frac{V}{R_{2}}$ + $\frac{V}{R_{3}}$

Taking V common and cancelling it we get

$\frac{1}{R_{eff}}$ = $\frac{1}{R_{1}}$ + $\frac{1}{R_{2}}$ + $\frac{1}{R_{3}}$

<hr>

## **Voltage Division Rule**

V<sub>1</sub> = $\frac{R_{1}}{R_{1} + R_{2}}$V
V<sub>2</sub> = $\frac{R_{2}}{R_{1} + R_{2}}$V

<hr>

## **Current Division Rule**

I<sub>1</sub> = $\frac{R_{2}}{R_{1} + R_{2}}$I
I<sub>2</sub> = $\frac{R_{1}}{R_{1} + R_{2}}$I

<hr>

## **Kirchhoff's Current Law**

The total current entering a junction or a node is equal to the charge leaving the node as no charge is lost. Put differently, the algebraic sum of every current entering and leaving the node has to be null.

![[Pasted image 20230120211257.png]]

## **Kirchhoff's Voltage Law**

If you travel around any loop in a circuit, the voltages across the elements add up to zero

![[Pasted image 20230120211404.png]]

<hr>