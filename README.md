## Experiment No: 2
## NON-INVERTING AMPLIFIER USING OP-AMP (μA741)
## Aim
To design and simulate a Non-Inverting Amplifier using μA741 in Proteus Design Suite and verify its voltage gain.
## Apparatus Required
•	μA741 Op-Amp
•	Resistor R1 = 10 kΩ
•	Resistor Rf = 100 kΩ
•	Signal Generator (1 kHz sine wave)
•	Dual Power Supply (±15V)
•	CRO / Oscilloscope
•	Connecting wires
## Circuit Diagram
<img width="1919" height="1019" alt="Screenshot 2026-02-23 091132" src="https://github.com/user-attachments/assets/33fd85b8-0267-4167-9809-abb56886b931" />

(Draw neatly in record OR paste Proteus circuit screenshot)
Pin Configuration:
•	Pin 3 → Input (Non-inverting)
•	Pin 2 → Feedback network
•	Pin 6 → Output
•	Pin 7 → +15V
•	Pin 4 → −15V
## Theory
A Non-Inverting Amplifier is a closed-loop amplifier configuration in which the input is applied to the non-inverting terminal (+) of the op-amp.
The output signal is amplified and remains in phase with the input signal.
## Procedure
1.	Open Proteus software.
2.	Select μA741, resistors, signal generator, and CRO.
3.	Connect circuit in non-inverting configuration.
4.	Set R1 = 10kΩ and Rf = 100kΩ.
5.	Apply ±15V supply.
6.	Give input sine wave of 1V, 1kHz.
7.	Run simulation.
8.	Observe input and output waveforms.
## Waveform
<img width="1919" height="1019" alt="Screenshot 2026-01-23 093421" src="https://github.com/user-attachments/assets/423fdbb3-92a3-442f-a6ba-2a54f82be6da" />

## Tabulation

| Sl. No | Input Voltage (Vin) | Output Voltage (Vout = 11Vin) |
| ------ | ------------------- | ----------------------------- |
| 1      | +0.1 V              | +1.1 V                        |
| 2      | +0.2 V              | +2.2 V                        |
| 3      | +0.5 V              | +5.5 V                        |
| 4      | 0 V                 | 0 V                           |
| 5      | –0.1 V              | –1.1 V                        |
| 6      | –0.2 V              | –2.2 V                        |
| 7      | –0.5 V              | –5.5 V                        |

S.No	Vin (V)	Theoretical Gain	Theoretical Vout (V)	Practical Vout (V)
## Result
The Non-Inverting Amplifier using μA741 Op-Amp was designed and simulated successfully.
The voltage gain obtained is approximately 11.
The output waveform is in phase with the input waveform.
## Conclusion
•	Gain depends on resistor ratio (Rf/R1).
•	Output is amplified without phase reversal.
•	Practical values are close to theoretical values.
## Viva Questions
1.	What is a Non-Inverting Amplifier?

  	 A non-inverting amplifier is an op-amp configuration where the input signal is applied to the non-inverting (+) terminal, and the output is fed back to the inverting (–) terminal through a feedback network. The output voltage is an amplified version of the input without phase reversal.
2.	What is the gain formula?
 <img width="262" height="121" alt="Screenshot 2026-02-23 091714" src="https://github.com/user-attachments/assets/54d93972-ff17-4f78-a568-05de9695f1af" />

3.	Why is output in phase?

Because the input is applied to the non-inverting terminal, the op-amp amplifies the signal without inversion, so the output waveform has the same phase as the input.

4.	What happens if Rf increases?

The voltage gain increases, since gain is directly proportional to R𝑓.

5.	What is the input impedance of non-inverting amplifier?

   It is very high (ideally infinite), because the input is connected directly to the op-amp input which draws negligible current.

