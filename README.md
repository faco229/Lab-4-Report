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

Before we begin, Op amps must be properly powered. The operational amplifiers in this lab will need positive and negative power voltages to work correctly. This will be achieved by using two separate power supplies where the positive output of one is connected to the ground. Check the polarity of power supplies before connecting to the op-amps. Be sure to measure the actual values of all resistors and capacitors to use in theoretical calculations. This practice should be followed for all components throughout the rest of the semester. 

The first circuit that will be built in the lab should look like this:

**FIG1.CIRC1**

Now that the circuit is built, take the voltage divider with both positive and negative voltage supplies and begin collecting Vo and Vi data by adjusting the potentiometer to change the input voltage. When doing so, record a minimum of nine Vi values from going to negative to positive saturation points. To do so, turn the potentiometer until Vi = -15, -14, -12, -5, 0, 5, 12, 14, 15, and measure Vo at each of those spots as well. Compare the results in a table and demonstrate them on a graph. When illustrating the graph, include the R^2 value as a strength indicator. The closer to one the better.

Now that data has been collected, the expected gain can be calculated given the resistor values in the circuit above. Gain is calculated as follows:
**EQ1**

Having calculated the expected gain from the first circuit and compared it to the graph now it is okay to move on to the next circuit. The next circuit should look as follows:

**FIG.2CIRCUIT2**

### Schematics
*Include schematics, diagrams, or links to schematic files.*

### Drawings
*Add drawings or sketches that illustrate the design and process.*

### Pictures
*Embed or link to pictures documenting the lab setup, process, or equipment used.*

---

## Results

This section shows the data and outcomes obtained during the lab work.

### Data and Outcome

#### Tables
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




#### Drawings
*Include annotated drawings or additional diagrams if needed.*

#### Pictures
*Embed or link to images that illustrate the results.*

---

## Discussion
**Part 1**
a.	Compare the performance of each amplifier circuit to its expected theoretical performance with regard to gain.
b.	Comment on the limits of op-amp circuits with respect to maximum output voltage.
c.	Are the LM741 op amps symmetric i.e. does the positive voltage performance equal the negative voltage performance?


**Part 2**
Did the integrating and differentiating circuits perform the mathematical operations expected?  Explain. 




---

## Conclusion

Summarize the most important things learned from the lab. Provide one or two paragraphs that encapsulate:
- The key findings.
- Lessons derived from the work.
- Implications for future work or further investigation.

---

*End of Lab Report*
