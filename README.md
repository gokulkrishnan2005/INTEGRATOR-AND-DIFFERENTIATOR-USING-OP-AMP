![734508e2-65f5-4efe-a9b6-23b2b5c0d8b2](https://github.com/user-attachments/assets/61776c79-64ff-4836-b775-73b769c7f4fa)# DESIGN OF INTEGRATOR-AND-DIFFERENTIATOR-USING-OP-AMP
# AIM: 
To design and test the performance of integrator and differentiator circuits using Op-amp 741.

# APPARATUS REQUIRED:
<img width="992" height="272" alt="image" src="https://github.com/user-attachments/assets/d8b53c15-71e0-4acf-9611-92083a57e93a" />

# THEORY:
# INTEGRATOR
A circuit in which the output voltage waveform is the integral of the input voltage waveform is the integrator. Such a circuit is obtained by using a basic inverting amplifier configuration if the feedback resistor Rf is replaced by a capacitor Cf . The expression for the output voltage is given as,
                Vo = -(1/Rf C1 )∫ Vi dt

Here the negative sign indicates that the output voltage is 180 0 out of phase with the input signal. Normally between fa and fb the circuit acts as an integrator. Generally, the value of fa < fb . The input signal will be integrated properly if the Time period T of the signal is larger than or equal to Rf Cf . That is,
                  T ≥ Rf Cf

The integrator is most commonly used in analog computers and ADC and signal-wave shaping circuits.

# DESIGN:
![8694b98a-9d3c-49ae-9de5-70cf5fa49f51](https://github.com/user-attachments/assets/db9573b7-89d0-49e9-a528-81a2b32b4cd5)

# INTEGRATOR CIRCUIT DIAGRAM
<img width="446" height="270" alt="image" src="https://github.com/user-attachments/assets/521ab839-8846-49d0-bc6d-d8b2105934f3" />

# MODEL GRAPH:
# i) SINE WAVE INPUT:
<img width="353" height="243" alt="image" src="https://github.com/user-attachments/assets/a9639775-1bfb-4cab-99c4-3d66e7dd5907" />

# ii) SQUARE WAVE INPUT
<img width="678" height="358" alt="image" src="https://github.com/user-attachments/assets/3a9d9a97-3057-49e5-8622-3d4862b8a053" />

# TABULATION:
![f65f9392-e4bd-4bd8-a2bc-40557b8022ac](https://github.com/user-attachments/assets/9acbd98d-2e28-4bbd-95c6-c2e8c81e0b0b)

# THEORY:
# DIFFEERENTIATOR:
The differentiator circuit performs the mathematical operation of differentiation; that is, the output waveform is the derivative of the input waveform. The differentiator may be constructed from a basic inverting amplifier if an input resistor R1 is replaced by a capacitor C1 . The expression for the output voltage is given as,
                                          Vo = -Rf C1(dVi/dt )

Here the negative sign indicates that the output voltage is 180 0 out of phase with the input signal. A resistor Rcomp = Rf is normally connected to the non-inverting input terminal of the op-amp to compensate for the input bias current. A workable differentiator can be designed by implementing the following steps:

1. Select fa equal to the highest frequency of the input signal to be differentiated. Then, assuming a value of C1 < 1 μF, calculate the value of Rf.
2. Choose fb = 20 fa and calculate the values of R1 and Cf so that R1C1 = Rf Cf.
The differentiator is most commonly used in wave shaping circuits to detect high frequency components in an input signal and also as a rate–of–change detector in FM modulators.

# DESIGN:
![095fb501-59bf-47bb-b0a3-ea6908f40d77](https://github.com/user-attachments/assets/6b59348b-8033-4d5e-ba37-ec6602c3803e)

# DIFFERENTIATOR CIRCUIT DIAGRAM
<img width="485" height="264" alt="image" src="https://github.com/user-attachments/assets/f5242bb4-723a-447c-85a9-02798491222b" />

# MODEL GRAPH:
# i) SINE WAVE INPUT:
<img width="635" height="306" alt="image" src="https://github.com/user-attachments/assets/5c0d742f-20fe-45d7-8cb3-d065c98dd595" />

# ii) SQUARE WAVE INPUT
<img width="614" height="285" alt="image" src="https://github.com/user-attachments/assets/af0e1a53-56c7-4af2-a5a4-859c7c2e842e" />


# TABULATION:
![f7732e85-60e1-4e9a-85b0-ae6b7b5b44e9](https://github.com/user-attachments/assets/ea3f71cd-fe6f-4704-a1eb-2400e602b725)

# PROCEDURE:
1. Connections are given as per the circuit diagram
2. + Vcc and - Vcc supply is given to the power supply terminal of the Op-Amp IC.
3. By adjusting the amplitude and frequency knobs of the function generator, appropriate input voltage is applied to the inverting input terminal of the Op- Amp.
4. The output voltage is obtained in the CRO and the input and output voltage waveforms are plotted in a graph sheet.
RESULT:
Thus an Integrator and Differentiator using op-amp are designed and their performance was successfully tested using op-amp IC 741.

# INTEGRATOR GRAPH
![734508e2-65f5-4efe-a9b6-23b2b5c0d8b2](https://github.com/user-attachments/assets/186e5974-c0c1-4e49-bb39-ff6366a4b256)

# DIFFERENTIATOR GRAPH
![96bd599b-ed99-4c0b-a99f-8d18fdf5b79c](https://github.com/user-attachments/assets/953cf6ed-4293-412c-a754-6f3a6489e7b5)


# RESULT:
![cc5fbbe6-570a-4cb7-933f-c797e401c809](https://github.com/user-attachments/assets/586f274c-d02a-44d7-b272-733c74ad0149)






