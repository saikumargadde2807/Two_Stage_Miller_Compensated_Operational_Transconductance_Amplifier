# Two_Stage_Miller_Compensated_Operational_Transconductance_Amplifier
Problem Statement:
You are tasked with designing a two-stage Miller compensated opamp that takes in a differential input and provides
a single-ended output. This opamp will be used eventually in a unity feedback loop driving a load RL = 10kW, and
CL = 5pF.
a) When a step input is applied to the closed-loop system, the output must settle to the desired value with less than 1%
error.
b) The closed-loop frequency response must not exhibit any peaking.
c) The closed-loop 3-dB bandwidth must not be smaller than 25MHz (if you are doing it in 180 nm PDK) and
45 MHz (if done in 130 nm PDK)
For designing the OTA, you are given the following ideal components:
Two ideal voltage sources: one with the value Vdd and another with the value Vcm = Vdd/2. an ideal ground, a reference
current source of 0.1μA for biasing. All the other bias voltages/currents need to be derived from these.
The load can be modeled using an ideal resistor and a capacitor. You can also use one ideal resistor and a capacitor
for compensation.
All the other components must be made using transistors. No other ideal components are allowed to be used in the
OTA design. After all, such ideal components are not available in the real world! Note that for running loop gain and
other related simulations to characterize the OTA, you can use ideal components.
Read the sections below carefully for instructions regarding the technology library and the type of input stage that you
should use.
