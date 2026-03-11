Instructions for Inverter Control Operation
1. Install CCS v8.3.1
2. Import the Buck_Boost_Inverter_PI_v0.3.2 project
3. Build and clean the project
4. Launch debug session
5. Input expression variables for monitoring and control some examples of interest would be: Inv_OPMode, AC_Mag, AC_Freq_Fund, Sys_En, V_DCin
6. Launch Typhoon HIL following the instructions provided in the accompanying book chapter
7. Set the desired inverter operation mode in the expressions list. The operating mode can be changed by modifying the InvOpMode variable (0 = Passive Rectifier; 1 = Islanded; 2 = Grid-Forming; 3 = Grid-Feeding; 4 = Grid-Supporting).
8. Enable the PWN by setting the Sys_En variable to 3
9. Monitor output and check results in Typhoon HIL SCADA





   
*This code was modified and built for Typhoon HIL based on an example code developed by Dr. Chris Farnell.

Citation: 
A. Corbitt, W. G. Schwartz, C. Farnell, J. C. Balda, and H. A. Mantooth, "The National Center for Reliable Electric Power Transmission Test Facility," in IEEE Open Journal of Power Electronics, vol. 5, pp. 754-764, 2024, doi: 10.1109/OJPEL.2024.3405311.
keywords: {Power transformers;Test facilities;Voltage control;Medium voltage;Aerospace electronics;Transportation;Research and development;Cybersecurity;hardware-in-the-loop;high-power test facility;measurement;medium voltage;power and energy;testing;transportation electrification;safety},

