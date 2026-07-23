# Step1. Create a new project
Create a new project
![Create_Project_1](images/Vivado_1.PNG)  

Click Next
![Create_Project_2](images/Vivado_2.PNG)  

Select your project name and locations
![Create_Project_3](images/Vivado_3.PNG)  

Click Next 
If you don't want to add source click "Do not specify sources at this time"
![Create_Project_4](images/Vivado_4.PNG)  

Add your design RTL here
Then click Next
Testbench recommend put in simulation source to avoid synthesis testbench
![Create_Project_5](images/Vivado_5.PNG)  

Add your design Constraints (.xdc)
Then click Next
![Create_Project_6](images/Vivado_6.PNG)  


Select Parts or Boards 
Here click PYNQ-Z2 Boards for instance
Then click Next
![Create_Project_7](images/Vivado_7.PNG)  

Click Finish
![Create_Project_8](images/Vivado_8.PNG)  

# Step2. Vivado Gui introduction
![Vivado_Gui_9](images/Vivado_9.PNG)  
1. Project Manager
Include : Settings, Add Sources, IP Catalog
2. IP Integrator
Block Design for your whole system，and cand add Xilinx or third party IP to create your design
3. Simulation
Simulation your design in Vivado
4. Synthesis
Synthesis your design by CLB, BRAM, DSP
5. Implementation & Generate Bitstream(below, not in the graph)
Put your design on FPGA (Floor & Plan) and generate completed design to bit files
6. Sources
Design Sources, Constraints, Simulation Sources
7.
- Tcl Console : type in instructions
- Message : any messages, warning, error will show here
- Log : log
- Reports : synthesis & implementation timimg, power, utilization...etc. informations。
- Design Runs : show your design stages
8. Project Summary
9. Synthesis & Implementation Summary
