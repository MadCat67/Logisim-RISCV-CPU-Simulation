A simulation for a 32 bit CPU designed in logisim

How to Download the Simulation:
Save the .circ file.  
You can then load the file as a library in your own project by navigating to Project > Load Library > Logisim Library....  
After loading, the circuits from the file will appear in a new folder in your component list, and they can now be viewed by you.  

Full Schematic:
<img width="1043" height="725" alt="Screenshot 2025-09-14 at 4 16 48 PM" src="https://github.com/user-attachments/assets/83ec3058-3421-4b7d-91ab-b3d00485dea8" />  

Project Summary:  
The design for this CPU follows the RISCV RV32I instruction set architecture.  
<img width="520" height="671" alt="Screenshot 2025-09-14 at 4 19 22 PM" src="https://github.com/user-attachments/assets/163c8d9d-41d3-430c-8457-35127e9b0c23" />  
RISC is a popular, new, instruction set architecture meant to be simplistic yet functional and efficient. Specifically, RV32I is meant to provide modern CPU features with as little complexity as possible.  

The CPU simulation is complete with program and data RAM, an instruction register, program counter, decoder, bit shifter, alu, and registers. The entire schematic is designed to have a four stage pipeline, in order to allow maximum CPU effeciency.
