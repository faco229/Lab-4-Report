# Lab-4-Report

**Names of People Involved (Group Members):**  
Faith Cox & Quinn Rison 

**Date Submitted:**  
2/24/2025

---

## Introduction / Summary

The purpose of this lab is to learn how to use operational amplifiers (Op Amps) to construct basic amplifier and signal conditioning circuits, and to explore the performance limitations of these devices. Various circuits will be built, including inverting amplifiers, low, moderate, and high gain circuits, a voltage follower, and integrating and differentiating circuits. Important characteristics of these circuits will be measured, and signals will be observed using an oscilloscope.

### Project Goal
---

## Methods / Tests

First, to repeat the lab, the following equipment will be needed:
•	A Bread Board
•	Two DC Power supplies
•	A Digital Multimeter
•	A Function Generator
•	An Oscilloscope
•	Resistors: 1 kΩ, 4.7 kΩ, 8.2 kΩ, 22 kΩ, two 68 kΩ, 220 kΩ, 330 kΩ, 1.5 MΩ
•	Capacitors: 1nF and 100 nF
•	An LM741 Op Amp
•	A 10 kΩ trimmer potentiometer

Before we begin, Op amps must be properly powered. The operational amplifiers in this lab will need positive and negative power voltages to work correctly. This will be achieved by using two separate power supplies where the positive output of one is connected to the ground. Check the polarity of power supplies before connecting to the op-amps. Be sure to measure the actual values of all resistors and capacitors to use in theoretical calculations. This practice should be followed for all components throughout the rest of the semester. The measurements are compiled below:

**Table 1:** Expected Resistance vs. Measured Resistance
| Expected Resistance | Measured Resistance |
|---------------------|---------------------|
| 1 kΩ                | 0.981k              |
| 4.7 kΩ              | 4.65k               |
| 8.2 kΩ              | 8.04k               |
| 22 kΩ               | 21.48k              |
| First 68 kΩ         | 66.8k               |
| Second 68 kΩ        | 66.9k               |
| 220 kΩ              | 217.5k              |
| 330 kΩ              | 326k                |
| 1.5 MΩ              | 1.5M                |

**Table 2:** Expected Capacitance vs. Measured Capacitance
| Expected Capacitance | Measured Capacitance |
|----------------------|----------------------|
| 1nF                  | 1.3nF                |
| 100 nF               | 106.6 nF             |

The first circuit that will be built in the lab should look like this:

<p align="center">
  <img src="https://github.com/faco229/Lab-4-Report/blob/main/Fig1.Circuit1.jpg" width="500">
  <br>
  <b>Figure 1:</b> Circuit 1
</p>


Now that the circuit is built, take the voltage divider with both positive and negative voltage supplies and begin collecting Vo and Vi data by adjusting the potentiometer to change the input voltage. When doing so, record a minimum of nine Vi values ranging from  negative to positive saturation points. To do so, turn the potentiometer until Vi = -15, -14, -12, -5, 0, 5, 12, 14, 15, and measure Vo at each of those spots as well. Keep in mind, these Vi values are what are referred to as "Goal Vi" values in Table 3. Compare the results in a table and demonstrate them on a graph. When illustrating the graph, include the R^2 value as a strength indicator. The closer to one the better.

**Table 3:** Vi vs. Vo data
| Goal Vi | Vi Actual | Vo (V) |
|---------|-----------|--------|
| -15     | -15.01    | 14.26  |
| -14     | -14.03    | 14.08  |
| -12     | -12.03    | 12.08  |
| -5      | -5.006    | 5.031  |
| 0       | 0.015     | -0.015 |
| 5       | 4.998     | -5.01  |
| 12      | 12.01     | -12.05 |
| 14      | 13.99     | -13.64 |
| 15      | 14.98     | -13.63 |

<p align="center">
  <img src="https://github.com/faco229/Lab-4-Report/blob/main/VivsVo%20graph.jpg" width="500">
  <br>
  <b>Figure 3:</b> Vo vs. Vi Graph
</p>

Now that data has been collected, the expected gain can be calculated given the resistor values in the circuit in Figure 1. Gain is calculated as follows:

<p align="center">
  <img src="https://github.com/faco229/Lab-4-Report/blob/main/Eq.1.jpg" width="500">
  <br>
  <b>Equation 1:</b> Gain for Circuit 1
</p>

Having calculated the expected gain from the first circuit and compared it to the graph now it is okay to move on to the next circuit. The next circuit should look as follows:

<p align="center">
  <img src="https://github.com/faco229/Lab-4-Report/blob/main/Fig2.Circuit2.jpg" width="500">
  <br>
  <b>Figure 2:</b> Circuit 2
</p>

Once the circuit is constructed, set the function generator to 100 mV and 2kHz and connect the nodes to Vi. With the oscilloscope, plot Vi in channel 1 and Vo in channel 2. The results should look as follows:

<p align="center">
  <img src="https://github.com/faco229/Lab-4-Report/blob/main/Fig3%20Circuit2%20Wave.jpg" width="500">
  <br>
  <b>Figure 3:</b> Circuit 2 Oscilloscope Reading
</p>

Like the last circuit, the gain is trying to be measured. This time with the oscilloscope. As follows:

<p align="center">
  <img src="https://github.com/faco229/Lab-4-Report/blob/main/Equation%202%20Gain.jpg" width="500">
  <br>
  <b>Equation 2:</b> Gain for Circuit 2
</p>

With this much gain, it is apparent that there is an error in the measurement somewhere. Anyway, the next circuit that will be built is like the previous however instead of the 8.2k resistor it will be replaced with a 1k resistor and should look as follows:

<p align="center">
  <img src="https://github.com/faco229/Lab-4-Report/blob/main/Fig4%20Circuit%203.jpg" width="500">
  <br>
  <b>Figure 4:</b> Circuit 3
</p>

This circuit is a high gain op amp circuit. For this part of the experiment the function generator should be set to 10 mv and 2kHz. Calculate the gain using the oscilloscope.

<p align="center">
  <img src="https://github.com/faco229/Lab-4-Report/blob/main/Equation%203.jpg" width="500">
  <br>
  <b>Equation 3:</b> Gain for Circuit 3
</p>

Again, with this much gain, it is apparent that there is an error in the measurement somehow. Gain shouldn’t be this high. 

Next, construct the voltage follower seen below. Should look as follows:

<p align="center">
  <img src="https://github.com/faco229/Lab-4-Report/blob/main/Fig.5%20Circuit%204.jpg" width="500">
  <br>
  <b>Figure 5:</b> Circuit 4: Voltage Follower
</p>

<p align="center">
  <img src="https://github.com/faco229/Lab-4-Report/blob/main/Circuit%204%20built.jpg" width="500">
  <br>
  <b>Figure 6:</b> Circuit 4: Built
</p>


Once the circuit is built, set the function generator to an amplitude of 1V and a frequency of 2kHz. The goal is to see that the input voltage on the circuit is equal to the output voltage. With the oscilloscope, this can be checked. Record the findings. Estimate the gain. After, increase the frequency to its limit and record the results. 

The next circuit that will be constructed is an integrating op amp. It should look as follows:

<p align="center">
  <img src="https://github.com/faco229/Lab-4-Report/blob/main/Fig6%20Circuit%205.jpg" width="500">
  <br>
  <b>Figure 7:</b> Circuit 5: Integrating Op Amp
</p>


<p align="center">
  <img src="https://github.com/faco229/Lab-4-Report/blob/main/Circuit%205%20built.jpg" width="500">
  <br>
  <b>Figure 8:</b> Circuit 5: Built
</p>


Once this circuit is constructed, connect the function generator to the circuit and take pictures for the input waveforms of 4kHz, 1Vp-p, sine, square, and triangle waves. Change the voltage and repeat the process. Note any differences found while conducting the experiment. 

<p align="center">
  <img src="https://github.com/faco229/Lab-4-Report/blob/main/Fig6%20Circuit%205%20reading.jpg" width="500">
  <br>
  <b>Figure 9:</b> Oscilloscope reading for Circuit 5
</p>

The last circuit that will be built is a differentiating op amp circuit. This circuit should look as follows:

<p align="center">
  <img src="https://github.com/faco229/Lab-4-Report/blob/main/Fig8%20Circuit%206.jpg" width="500">
  <br>
  <b>Figure 10:</b> Circuit 6: Differentiating op-amp Circuit
</p>

<p align="center">
  <img src="https://github.com/faco229/Lab-4-Report/blob/main/Circuit%206%20built.jpg" width="500">
  <br>
  <b>Figure 11:</b> Circuit 6: Built
</p>

To complete this lab, connect the function generator to the circuit and take photos of the input and output waveforms for the 1kHz, 2Vp-p, sine, square, and triangle waves. Like the last circuit, change the voltage and note any changes. Also with this circuit, change the frequency and note any changes. 

---

## Results

This section shows the data and outcomes obtained during the lab work.

### Data and Outcome


---

## Discussion
**Part 1**
a.	Compare the performance of each amplifier circuit to its expected theoretical performance with regard to gain.
The theoretical performance of a non-inverting op-amp circuit is expected to be -1, while the gain of the first circuit was -0.9985.

b.	Comment on the limits of op-amp circuits with respect to maximum output voltage.
Once an op-amp circuit reaches its maximum output voltage, the op-amp enters saturation and starts to output its maximum voltage. At this point, it no longer amplifies the input voltage exponentially.

c.	Are the LM741 op amps symmetric i.e. does the positive voltage performance equal the negative voltage performance?
The LM741 op-amps are symmetric, displaying equal performance for both positive and negative voltages in the first circuit. On the other hand, when the voltage drops below -12V or rises above 12V, the input voltage (Vi) no longer equals the output voltage (Vo).

**Part 2**
**Did the integrating and differentiating circuits perform the mathematical operations expected?  Explain. **

Yes, the integrating and differentiating circuits behaved as expected. Comparing the square wave to the triangular wave, it is clear that integrating the square wave returns a triangular wave. Furthermore, the integral of the triangular wave is a more traditional sinusoidal wave. When functioning as integrators, a square wave input results in a triangular wave output. Conversely, when used as differentiators, a triangular wave input produces a square wave output. Additionally, with appropriate circuit design, an op amp can also amplify and display the shape of a sinusoidal wave input.

---

## Conclusion

Summarize the most important things learned from the lab. Provide one or two paragraphs that encapsulate:
- The key findings.
- Lessons derived from the work.
- Implications for future work or further investigation.

---

*End of Lab Report*
