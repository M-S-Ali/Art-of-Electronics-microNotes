# ART OF ELECTRONICS - microNotes

## Chapter 1 Part 2 - Capacitor

- Three linear passive 2 terminal circuit elements - resistor, capacitor, inductor
- Memristor - non linear element 

### Capacitor 
- Applications of Capacitor 
    - waveform generation
    - filtering
    - blocking or coupling (major)
    - bypass (major)
    - integrators
    - differentiators
- Condenser
- Q = CxV
- C = 8.85x10^-14 eA/d F 
- e - dielectric constant
- frequency dependent resistor
- Ideal Capacitor cannot dissipate power as voltage and current are 90 degrees
- I = C dV/dt - current proportional to change in voltage
- pF, nF, uF, mF
- U = 1/2 CV^2
- Capacitors in Series and Capacitors in Parallel
- Real Capacitor features causing issues in demanding Applications
    - series resistance (frequency dependent)
    - parallel resistance
    - series inductance
    - dielectric absorption or memory effect

**Note: *Varactors - Voltage variable capacitor made from a PN junction***

### RC circuit
- Time constant - RC - 37% - 63%
- 5 RC general rule of thumb for complete decay or complete charging 
- 10% to 90% - 2.2RC
- time taken to reach V = RC ln (Vf/Vf-V)
- Try to solve circuit using thevenin's as going for calculus not always worth it 
- example
    - time delay circuit
    - one minute power circuit 

### RC differentiators
- I = C dv/dt
- dVo/dt << dvi/dt
- RC very small but R big to avoid signal loading
- detecting leading edges and trailing edges
- converts transitions to spikes

**Note: *Slew Rate - dv/dt***

**Note: *Comparator output bounce around a bit when input crosses the reference***

**Note: *Bypass DC Supply generally with 0.1uF to 10uF***

### RC integrators  
- keep v<<vin
- RC large
- exponential to ramp

### Ramp Generator
- Applications
    - timing circuit
    - waveform and function generation
    - oscilloscope sweep circuits
    - analog digital conversion
- current source charging capacitor - ramp generation

### Inductors
- V = L dI/dt
- U = 1/2 LI^2
- Current produce magnetic field and Change in voltage produce voltage
- Lenz's Law
- Volt-Second balance rule
- Capacitors common as practical capacitor close to Ideal
- Winding resistance, Core loss, Self Capacitance
- L directly proportional to square of turns
- L = K ((d^2 x n^2)/(18d+40l))
- Solenoid
- Iron - Alloy, Lamination, Powder
- Ferrite
- Permeability
- Used in RF Chokes, RF Tuning, Power Supplies, Transformers
- Transformers
- Parallel inductance or Magnetizing inductance, Series Inductance or Leakage Inductance (test)




