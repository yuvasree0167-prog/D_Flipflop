# D_Flipflop
AIM:

To implement D flipflop using verilog and validating their functionality using their functional tables

SOFTWARE REQUIRED:

Quartus prime

THEORY

D Flip-Flop

D flip-flop operates with only positive clock transitions or negative clock transitions. Whereas, D latch operates with enable signal. That means, the output of D flip-flop is insensitive to the changes in the input, D except for active transition of the clock signal. The circuit diagram of D flip-flop is shown in the following figure.
<img width="725" height="354" alt="Screenshot 2025-12-14 214452" src="https://github.com/user-attachments/assets/85ed8ab2-1090-4ed2-b0bc-57a212cbf323" />



This circuit has single input D and two outputs Qtt & Qtt’. The operation of D flip-flop is similar to D Latch. But, this flip-flop affects the outputs only when positive transition of the clock signal is applied instead of active enable. The following table shows the state table of D flip-flop.
<img width="500" height="188" alt="Screenshot 2025-12-14 214501" src="https://github.com/user-attachments/assets/81777157-c7e1-4f0f-8200-214f5f0a8177" />



Therefore, D flip-flop always Hold the information, which is available on data input, D of earlier positive transition of clock signal. From the above state table, we can directly write the next state equation as Qt+1t+1 = D

<img width="495" height="270" alt="Screenshot 2025-12-14 214510" src="https://github.com/user-attachments/assets/886ce600-222d-48b6-beb4-018039506879" />


Next state of D flip-flop is always equal to data input, D for every positive transition of the clock signal. Hence, D flip-flops can be used in registers, shift registers and some of the counters.

Procedure

/* write all the steps invloved */

PROGRAM

/* Program for flipflops and verify its truth table in quartus using Verilog programming. Developed by:YUVASREE S RegisterNumber:25014102 */

RTL LOGIC FOR FLIPFLOPS

TIMING DIGRAMS FOR FLIP FLOPS

RESULTS:Thus the D flipflop using verilog and validating their functionality using their functional tables is implemented and verified.
