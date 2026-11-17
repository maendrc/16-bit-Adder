# 16-bit-Adder
• Design a 16-bit CMOS adder circuit 
• Measure delay and power 
• Perform the corner simulations to verify mismatch 
• Design layout and perform post-layout simulation. Compare pre- and post- layout simulation and briefly  analyze the results. 
• Investigate the impact of power-supply voltage on power-delay-product

Specifications
• Global power supply = 1.2 V
• Input signal rise/fall time: 100ps each
• You can use standard cells from tcbn65gplus library
• Use a buffer after each input signal in testbench (BUFFD0 from tcbn65gplus)
• Output load : 10 fF
• 17 total output signals including 16 Sum outputs and 1 carry-out 
• Addition time (tadd) ≤ 700ps for all corner/temp combinations (Pre-layout, 3temp (-25, 27, 85), 3corners(TT,FF,SS))

DELIVERABLES
• Provide description and simulation results of TWO different 16-bit adder,ripple carry and carry look ahead, show block diagrams, schematics, and simulation results.
• Assume initially, all sum and carry bits are zero. 

Perform testing of the following 3 vectors
• Vector A = 1111 1111 1111 1111 + 0000 0000 0000 0001 
• Vector B = 1111 1111 1111 1111 + 1111 1111 1111 1111 
• Vector C = 1010 1010 1010 1010 + 1010 1010 1010 1010

• Provide a table to show delay/power/PDP of the three vectors under FF_(-25°C), TT_27° C and SS_85°C.
• Perform power-supply variation and plot PDP vs. power supply voltage with vector A under TT, 27°C. Discuss about the findings.
• Perform post-layout simulation (ripple carry) with vector A under TT and 27°C. Compare delay/power/PDP with pre-layout simulation result and briefly analyze.

THE STRUCTURE OF THE REPORT
1. Introduction
2. Review simulation results of two different adder architectures\
1. Functional waveforms (different test vectors)
2. Global mis-match: corner/temperature
3. PDP vs. power-supply voltage
3. Comparative analysis of both two architectures, and provide justification 
for the chosen architecture
4. Layout & Post-layout Simulation
5. Conclusion

