# ART OF ELECTRONICS - microNotes

## Chapter 1 - Foundation

### Introduction
- Spark Gap Transmitter and Cat's Whiskers Detector to Vacuum Tube Electronics.
- Communication, Navigation, Instrumentation, Control, Computation.
- Then **IBM 650** - 300k USD - 2.7 tons - 126 lamps, Now energy efficient lamp - more capable computer - 10 USD
- Foster good intuitive understanding along with mathematics
- Practice Circuits important

### Voltage
- Potential Difference, Electromotive Force
- If 1 joule work done to move 1 coulomb charge from one point to another, the potential difference between the two point is said to be 1 volt.
- uV, mV, V, kV, MV

### Current 
- Rate of flow of electric charge
- uA, mA, A

Oscilloscope and other tools like multimeter help in visualizing voltage and current. Other engineers envious of visualization tools we poses.

### Simple rules on Voltage and Current
- Kirchhoff's Current Law
    - Sum of current entering a node is equal to the sum of current leaving the node.
- Kirchhoff's Voltage Law
    - Sum of voltage drops around any closed circuit is zero.
- Power = Voltage x Current (instantaneous, average, power factor)

**Note: *The Game is I vs V Characteristics***

### Resistor
- Ohm's Law - R = V/I
- Resistor Series and Parallel
- Mind Calculation or "back-of-the-envelope" design
    - To trim up add small R in series.
    - To trim low add large R in parallel.
    - 1 10k parallel with 1 5k consider it as 3 10k in parallel.
    - develop techniques like this to do mind calculations
- No need of pinpoint calculations. Why?
    - Components are of finite precision
    - One character of good circuit is insensitivity to precise component values

### Conductance
- Inverse of Resistance
- Not generally used but good to build intuitions
- Millman's Theorem - Vo = Sum(Vi x Gi)/Sum of Gi
- unit siemens aka mho

**Note: *Input - Output - Transfer Function***

### Voltage Divider
- Vo = Vi x (R2/(R1+R2))
- Develop skill to identify voltage divider which is indirectly present make use of thevenin's Theorem.

**Note: *Negative Incremental Resistance - Tunnel Diode - Negative Impedance Converter***

### Voltage Source
- Ensures a steady voltage
- Current Compliance
- Likes open circuit Load and hates short circuit loads
- Every real life voltage source = Ideal Source with a series resistance

### Current Source
- Ensures steady current with varying voltage
- Output Voltage Compliance
- No direct analog for current source
- hates open circuit and likes short circuit

### Thevenin's Theorem
- Two terminal network of resistance and voltage sources is equivalent to a voltage source with a series resistance
- Norton's Theorem - is equivalent to a current source with a parallel resistor
- Vth is open circuit voltage and Rth is can be found by estimated short-circuiting

**Note: *Rth of Voltage divider is R1 and R2 parallel making it a bad choice of power source***

### Equivalent Source Resistance and Circuit Loading
- 








