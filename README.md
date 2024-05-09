# EX NO:7
<P align='center'> <b>JKFLIPFLOP-USING-IF-ELSE</b>

**DATE:**

**AIM:** 

To implement  JK flipflop using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:**

Quartus prime

**THEORY**

**JK Flip-Flop**

JK flip-flop is the modified version of SR flip-flop. It operates with only positive clock transitions or negative clock transitions. The circuit diagram of JK flip-flop is shown in the following figure.

![image](https://github.com/naavaneetha/JKFLIPFLOP-USING-IF-ELSE/assets/154305477/a649c30b-232b-4558-b188-fd6c09845180)


This circuit has two inputs J & K and two outputs Qtt & Qtt’. The operation of JK flip-flop is similar to SR flip-flop. Here, we considered the inputs of SR flip-flop as S = J Qtt’ and R = KQtt in order to utilize the modified SR flip-flop for 4 combinations of inputs. The following table shows the state table of JK flip-flop.

![image](https://github.com/naavaneetha/JKFLIPFLOP-USING-IF-ELSE/assets/154305477/c4360742-e8a8-4937-b089-c46c0433f9a3)

 
Here, Qtt & Qt+1t+1 are present state & next state respectively. So, JK flip-flop can be used for one of these four functions such as Hold, Reset, Set & Complement of present state based on the input conditions, when positive transition of clock signal is applied. The following table shows the characteristic table of JK flip-flop. Present Inputs Present State Next State
 
![image](https://github.com/naavaneetha/JKFLIPFLOP-USING-IF-ELSE/assets/154305477/6c275261-a6d5-4c37-a3a7-1e88ca11c4cd)

By using three variable K-Map, we can get the simplified expression for next state, Qt+1t+1. Three variable K-Map for next state, Qt+1t+1 is shown in the following figure.
 
![image](https://github.com/naavaneetha/JKFLIPFLOP-USING-IF-ELSE/assets/154305477/5174f41b-0ce0-4329-a372-6d1943ea6673)

The maximum possible groupings of adjacent ones are already shown in the figure. Therefore, the simplified expression for next state Qt+1t+1 is Q(t+1)=JQ(t)′+K′Q(t)Q(t+1)=JQ(t)′+K′Q(t)

**Procedure**

step-1 Go to quartus software.

step-2 Set new environment.

step-3 Type the code to implement SR flipflop using verilog and validating their functionality using their functional tables.

step-4 Run the program.

step-5 Give inputs in the waveform table .

step-6 Run the program.

**Program for flipflops and verify its truth table in quartus using Verilog programming.**

**Developed by:MONISH R**

**RegisterNumber:212223050031**

**PROGRAM**

![328088425-5a389273-3283-4fb9-840d-aeb885a94841](https://github.com/monish1545/JKFLIPFLOP-USING-IF-ELSE/assets/166646660/6011809e-a93d-4203-83b6-e2d70e7b7808)


**RTL LOGIC FOR FLIPFLOPS**

![328088431-8c1f60dc-9aca-4a58-bc6b-f0d9ab2d89c3](https://github.com/monish1545/JKFLIPFLOP-USING-IF-ELSE/assets/166646660/650131a7-6ca8-4a9f-b8b5-64264956f46f)


**TIMING DIGRAMS FOR FLIP FLOPS**

![328088434-124bfc38-545f-469a-a796-338469f157f8](https://github.com/monish1545/JKFLIPFLOP-USING-IF-ELSE/assets/166646660/12674fda-2465-4c34-aecc-88e11d9a8177)


**RESULTS**

Thus,the code executed successfully.


