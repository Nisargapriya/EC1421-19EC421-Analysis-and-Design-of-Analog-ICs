## EC1421-19EC421-Analysis-and-Design-of-Analog-ICs
## SIMULATION OF DIGITAL TO ANALOG CONVERTER

## AIM:
To Design and simulate the digital to analog converter (DAC) circuit using LT Spice
 
## SOFTWARE REQUIRED:
LT-Spice

## PROCEDURE:
1. Double click on LT Spice icon.

2. New schematic window open.

3. Pick and paste the required component from the library and draw the circuit diagram .

4. Complete the connection.

5. Select 1 voltage and select pulse width as 
Vinitial [V]: 5
       Von [V]: 0
       Tdelay [s]: 0
       Trise [s]: 1u
       Tfall [s]: 1u
               Ton [s]: 10m
        Tperiod [s]: 20m
        Ncycles: 100
Change the values of Ton = 20m , 40m, Tperiod  = 40m , 80m
For v2 and v3  keeping the other values constant.
6. Save the file by giving file name.

7. Click on the run option -->click advanced open -->select select transient analysis -->enter the amplitude time delay stop time value as (.tran 0 200 0 0.01).

8. Click on the run option -->simulation window opens-->place the probe -->output graph is obtained.

## CIRCUIT DIAGRAM:
### DAC:
<img width="459" height="257" alt="image" src="https://github.com/user-attachments/assets/2164331f-4a83-48df-8f91-4baf6e096373" />
<img width="509" height="247" alt="image" src="https://github.com/user-attachments/assets/92c1a41c-ae50-4c7e-8029-a5dea9ce23aa" />


## OUTPUT GRAPH:
### DAC:
<img width="460" height="381" alt="image" src="https://github.com/user-attachments/assets/f3c187c7-f4c1-41c4-9b62-33489db25b13" />
<img width="475" height="687" alt="image" src="https://github.com/user-attachments/assets/bb2f659a-44ee-4629-bdca-ec281c066c1b" />

## RESULT:
Thus the LT-SPICE tool has been studied and digital to analog converter (DAC) circuit is simulated.
