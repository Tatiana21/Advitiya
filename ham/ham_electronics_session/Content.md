# Electronics Required For HAM

Just for the sake of completio and to have a well structured flow of content, we will start from ver elementary concepts. 

## Atmoic Structure

### Valence Electrons

- **Conductor**
- **Insulator** 
- **Semi Conductors**

**Note** : The classification of materials into the above mentioned sections as we all know based on the band gap energy and not valence electrons. They are closely related and in layman language we can use them to explain the classification. 

#### List of very elementary concepts with which we extremely comfortable with. 
- Conductance
- Current
- Electromotive Force
- Voltage
- Ohms Law 

#### Electrical Components
- **Resistor**
	- Resistance
	- Specific Resistane
	- Standard Colour Code 

- **Capacitor**
	- Capacitance
	- Fixed and variable Capacitors

- **Inductor**
	- Inductane
	- Self and Mutual Inductance

##### Transformer

###### Auto Transformer  

###### Audio Transformer 
Used to increase the voltage of audio frequency signals.

###### Intermediate Frequency Transformer

These are mainly used to increase the voltage of IF frequency signals. They are used in IF circuits
as coupling devices and operate at frequency ranging between 450 to 460 KHz.

###### Radio Frequency Transformer 
These are used for coupling one stage of RF amplification to another.

###### Impedance Matching [Important Application of Transformer]
In the transfer of power from any electrical source of its load, the impedance of the load must be
equal to or match the internal impedance of the source for maximum transfer of power. The
transformer is a useful device for matching the impedance of a generator to that of its load. 


### AC Fundamentals 

#### Frequency 
#### Wavelength
#### Phase
#### Average and RMS value
#### Impedance
#### Power Factor
#### Resonance

**Note** : __"For a series circuit at resonance, frequencies becoming far removed from resonance see an ever
increasing impedance. For a parallel circuit at resonance, frequencies becoming far removed from
resonance see an ever decreasing impedance".__ 

### Rectifier

#### Half Wave Rectifier
#### Full Wave Rectifier
#### Bridge Rectifier
#### Smoothing or Filter Circuit
#### Capacitive Input Filter

### Electronic Voltage Regulation

When extremely low ripple is required or when the supply voltage must be constant with large fluctuations of load
current and line voltage, a closed loop amplifier is used to regulate the supply.
</br> 
There are two main categories of electronic regulators:
- Linear regulators, in which the condition of the control element is varied in direct proportion to the line
voltage or load current;

- Switching regulators, in which the control device is switched ON and OFF, with the duty cycle proportion to the line or load conditions.

#### IC Voltage Regulators
Inside each regulator is a reference, a high gain error amplifier, temperature compensated voltage sensing resistors and transistors and a pass element. 

#### Switching Regulators

#### Voltage Stabilization (Zener Diode Regulation)

### Transistor
- Emitter 
- Collector 
-Base

#### Current Amplifier 


### Amplifier

#### Class A Amplifiers

Class A amplifiers are those in which the grid bias and plate voltage are so chosen that the tube
operates over the linear portion of dynamic curve or it is an amplifier in which plate current flows
over the entire cycle.

![class_A_amp](https://github.com/sabSAThai/Advitiya/blob/master/images/class_A_amp.png)

Characteristics: 
- Waveform at the output is exactly similar to that of input. Less distortion since operated in linear region. 
- High voltage amplification
-  In practice the power output is small because both current and voltage are restricted to comparatively small variations.

#### Class B Amplifiers
These amplifiers are biased to cut-off or approximately so, hence plate current flows during
positive half cycle of the input voltage.

![class_B_amp](https://github.com/sabSAThai/Advitiya/blob/master/images/class_B_amp.png)

Characteristics : 
- High distortions, Less amplification 
- High power output 


#### Class ‘AB’ Amplifier 

The grid bias and signal voltages are so adjusted that the plate current flows for more than half and
less than entire cycle. The characteristic of this amplifier lie in between those of class A’ and class
‘B amplifiers.

#### Class ‘D’ Amplifier

In these type of amplifiers the tube s biased beyond cut off point, the grid bias is as much as twice
the cut off value. Hence the plate current flows in pulses of less than one half cycle.

![class_C_amp](https://github.com/sabSAThai/Advitiya/blob/master/images/class_C_amp.png)

Characteristics :
- Very high distortion. Low amplification 
- Power output per tube is higher as compared to class B’ amplifier. 

**Note** : These amplifiers are not used as audio frequency amplifiers because of high distortion. But they are
used as radio frequency amplifiers for high power output.

#### Push-Pull Amplifier 

To increase power amplification, two transistors are used in push pull arrangements in the output stage. One transistor amplifies the +ve half cycle of the signal while the other transistor amplifies the -ve half cycle of the signal.
</br>
Push pull arrangement: when one Transistor is pushing (conduction), the other is pulling (stopping
conduction).

Characteristics: High power amplification. 

#### Distortions in amplifiers :

- Nonlinear Harmonic Distortion 
- Frequency Distortion 
- Phase Distortion 


### Transistor Amplifiers
Amplifier circuits used with transistors fall into one of three types, known as the common-base,
common-emitter and common-collector circuits. 

#### Common Base Circuit

![common_base.png](https://github.com/sabSAThai/Advitiya/blob/master/images/common_base.png)

Characteristics: 
- The input circuit of a common-base amplifier must be designed for low impedance. 
- The optimum output load impedance, RL may range from a few thousand ohms to 100,000.
-  In this circuit the phase of the output (collector) current is
the same as that of the input emitter) current.  


#### Common Emitter Circuit

![common_emitter.png](https://github.com/sabSAThai/Advitiya/blob/master/images/common_emitter.png)

Characteristics: 

- The base current is small and the input impedance is therefore fairly high- several thousand ohms in the average case. 
-  The collector resistance is some tens of thousands of ohms, depending on the signal source impedance.

#### Common Collector Circuit

![common_collector.png](https://github.com/sabSAThai/Advitiya/blob/master/images/common_collector.png)

Characteristics : 
- The input resistance depends on the load resistance.
-  The output and input currents are in phase.


### Oscillator

#### Hartley Oscillator, Colpitt's Oscillator
- Based on L-C oscillations. 

#### Piezoelectric Effect
- Certain crystalline materials when we apply an AC voltage across them, they vibrate at the frequency of the applied voltage. Conversely, when they are compressed or placed under mechanical strain to vibrate, they
produce an AC voltage. Of the various piezoelectric crystals, quartz is most commonly used because it is
inexpensive and readily available in nature.

#### Transistor Crystal Oscillator

![transistor_crystal.png](https://github.com/sabSAThai/Advitiya/blob/master/images/transistor_crystal.png)

A tank circuit L1-C1 is placed in the collector and the crystal is connected in the base circuit.
Feedback is obtained by coil L2 inductively coupled to coil Li. The crystal is connected in series
with the feedback winding. The natural frequency of L C circuit is made nearly equal to the natural
frequency of crystal.

**Advantages**
1) They have a high order of frequency stability.
2) The quality factor Q of the crystal is very high. It is high as 10,000 compared to about 100 of LC
tank.

**Disadvantages**
1) They are used in low power circuits.
2) The frequency of oscillators cannot be changed.



##  Modulation 

The audio frequency signals cannot be radiated out from the aerial directly because transmission at
audio frequencies is not practical. For this purpose oscillations of very high frequency or radio
frequency are produced with the help of oscillators. These electromagnetic waves so produced are
of constant amplitude and of extremely high frequencies. The audio frequency signal is then super
imposed on the RF waves which are known as Carrier waves (because they carry AF signals
through space to distant places). The process by which AF signal is super imposed on the Carrier
wave is known as Modulation.

There are three types of Modulations, namely

- Amplitude Modulation
- Frequency Modulation
- Phase Modulation


### Amplitude Modulation
A method of transmission and reception of radio waves in which the amplitude of the carrier wave
is made to vary in accordance with the audio frequency wave.

![AM.png](https://github.com/sabSAThai/Advitiya/blob/master/images/AM.png)

### Frequency Modulation 

In this method the carrier wave is modulated by changing its frequency in relation to the AF signal without changing its amplitude. This process is known as frequency modulation (FM).

![FM.png](https://github.com/sabSAThai/Advitiya/blob/master/images/FM.png)

#### Phase Modulation

A method of conveying information via radio frequency carrier waves in which the instantaneous
phase of the carrier is shifted in accordance with the audio frequency wave. Phase Modulation is
very similar to FM wave.

![PM.png](https://github.com/sabSAThai/Advitiya/blob/master/images/PM.png)



### Major Modulation Systems
The major types are:  
- Amplitude modulation
- Angle modulation 
- Pulse modulation


#### Angle Modulation
