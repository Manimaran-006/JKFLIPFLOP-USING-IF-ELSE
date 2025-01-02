## NAME:MANIMARAN V
## REG.NO:24008541
# EXPERIMENT 5:IMPLEMENTATION OF JK FLIPFLOP

# AIM:

To implement  JK flipflop using verilog and validating their functionality using their functional tables

# SOFTWARE REQUIRED:

Quartus prime

# THEORY

# JK FLIP-FLOP

JK flip-flop is the modified version of SR flip-flop. It operates with only positive clock transitions or negative clock transitions. The circuit diagram of JK flip-flop is shown in the following figure.

![image](https://github.com/naavaneetha/JKFLIPFLOP-USING-IF-ELSE/assets/154305477/a649c30b-232b-4558-b188-fd6c09845180)


This circuit has two inputs J & K and two outputs Qtt & Qtt’. The operation of JK flip-flop is similar to SR flip-flop. Here, we considered the inputs of SR flip-flop as S = J Qtt’ and R = KQtt in order to utilize the modified SR flip-flop for 4 combinations of inputs. The following table shows the state table of JK flip-flop.

![image](https://github.com/naavaneetha/JKFLIPFLOP-USING-IF-ELSE/assets/154305477/c4360742-e8a8-4937-b089-c46c0433f9a3)

 
Here, Qtt & Qt+1t+1 are present state & next state respectively. So, JK flip-flop can be used for one of these four functions such as Hold, Reset, Set & Complement of present state based on the input conditions, when positive transition of clock signal is applied. The following table shows the characteristic table of JK flip-flop. Present Inputs Present State Next State
 
![image](https://github.com/naavaneetha/JKFLIPFLOP-USING-IF-ELSE/assets/154305477/6c275261-a6d5-4c37-a3a7-1e88ca11c4cd)

By using three variable K-Map, we can get the simplified expression for next state, Qt+1t+1. Three variable K-Map for next state, Qt+1t+1 is shown in the following figure.
 
![image](https://github.com/naavaneetha/JKFLIPFLOP-USING-IF-ELSE/assets/154305477/5174f41b-0ce0-4329-a372-6d1943ea6673)

The maximum possible groupings of adjacent ones are already shown in the figure. Therefore, the simplified expression for next state Qt+1t+1 is Q(t+1)=JQ(t)′+K′Q(t)Q(t+1)=JQ(t)′+K′Q(t)

# PROEDURE

/* write all the steps invloved */

# PROGRAM

![Screenshot 2025-01-02 140716](https://github.com/user-attachments/assets/1181489c-7347-44ab-ad1f-96749f078214)



# RTL LOGIC FOR FLIPFLOPS
![Screenshot 2025-01-02 140725](https://github.com/user-attachments/assets/3e2dd5e2-4dce-4f48-aad7-c67a070edefc)


# TIMING DIGRAMS FOR FLIP FLOPS
![Screenshot 2025-01-02 140736](https://github.com/user-attachments/assets/7d2a2756-0a16-472f-81d8-d476d12927bb)

# RESULTS

Thus the JK flipflop using verilog and validating their functionality using
their functional tables is implemented
