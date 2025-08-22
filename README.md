# 2-bit-and-4-bit-Multiplier

2 bit Multiplier

This repository discusses the implementation of 2 bit and 4 bit multiplier in Cadence Virtuoso.

The 2 bit multiplier multiplies two 2 bit operands: B1 B0 and A1 A0 and yields a 4 bit output or product (P3 P2 P1 P0). The operation of a multiplier is shown below.

<img width="278" height="301" alt="image" src="https://github.com/user-attachments/assets/937d0313-878f-45e1-9251-c6d1847dca5a" />

Based on the operation, the circuit diagram of the 2-bit multiplier is:

<img width="565" height="430" alt="image" src="https://github.com/user-attachments/assets/49b91ba3-59c1-48ea-9a49-5c0da2d4eecf" />

Using this circuit diagram, the schematic of 2 bit multiplier is implemented in Cadence Virtuoso.

<img width="638" height="326" alt="image" src="https://github.com/user-attachments/assets/8f705b98-01f7-47b7-b0e5-2e2e09e8ce7e" />

Pulse sources were applied at the input ports: B1 B0, A1 A0 and transient analysis was conducted and the below output was obtained.

<img width="940" height="441" alt="image" src="https://github.com/user-attachments/assets/d48cea30-4882-43f4-bd0e-0bea25255334" />

The 2 bit multiplier consumed an average power of 344.3 uW and has a delay of 0.589 nanoseconds.

4 bit Multiplier

4 bit multiplier multiplies two 4 bit operands: B3 B2 B1 B0,A3 A2 A1 A0 and yields 8 bit output (P0 P1… P7). A 4 bit array multiplier can be designed using full adders and half adders as shown below. 

<img width="670" height="591" alt="image" src="https://github.com/user-attachments/assets/c8244752-da94-4ab5-b8dc-00a6df095de1" />

On implementing this circuit in Cadence, the schematic looks like this:

<img width="790" height="497" alt="image" src="https://github.com/user-attachments/assets/17f47447-33b3-472a-ba3a-84c5a673bb77" />

Pulse sources are applied to the 8 input bits: B3 B2 B1 B0, A3 A2 A1 A0 in the testbench circuit.

<img width="940" height="318" alt="image" src="https://github.com/user-attachments/assets/df8ba5cc-9a9b-4892-9a21-b871d9bc02ce" />

The functioning of 4 bit array multiplier can be verified from the below output waveform.

<img width="940" height="423" alt="image" src="https://github.com/user-attachments/assets/868181e3-15e9-4746-8d51-7c9ef0f7cd74" />

The 4 bit array multiplier uses 2.441 mW power and has a delay of 0.96 nanoseconds.
