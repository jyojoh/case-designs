All case designs listed are derivatives of the "Standard" case. Unless otherwise noted, all case designs are tented by 5 degrees. 

## In this folder:
1. [Standard](/corne/5-column%20Choc/Standard): 5mm thick walls, 1-piece design suitable for CNC or 3D-printing. 
1. [Standard-Flat](/corne/5-column%20Choc/Standard-Flat): 5mm thick walls, non-tented. 1-piece design suitable for CNC or 3D-printing.
1. [Inset](/corne/5-column%20Choc/Inset): In all aspects the same as the Standard case, except 1mm shorter in height. Requires 3mm standoffs instead of the usual 4mm. Suitable for CNC or 3D-printing.
1. [Inset-Flat](/corne/5-column%20Choc/Inset-Flat): In all aspects the same as the Standard case, except 1mm shorter in height. Non-tented. Requires 3mm standoffs instead of the usual 4mm. Suitable for CNC or 3D-printing.
1. [Slim](/corne/5-column%20Choc/Slim): 3mm thick walls, 1-piece design suitable for CNC or 3D-printing. 
1. [Slim-Flat](/corne/5-column%20Choc/Slim-Flat): 3mm thick walls non-tented. 1-piece design suitable for CNC or 3D-printing. 
1. [Integrated](/corne/5-column%20Choc/Integrated): 5mm thick walls, integrated plate, 2-piece case design. Suitable for CNC machining. 
## CNC Data Preparation
When filling out the CNC manufacturing form through [PCBWay](https://pcbway.com), make sure to pay close attention to the following parameters:

1. Specify the desired surface finish. This will most likely be "bead-blasting". 
2. Specify that threaded holes are needed, and upload [threadDrawing.png](threadDrawing.png) to denote which holes need to be threaded for the M2 female/male standoffs.
3. If the surface finish of the part is of importance to you (it is for me), check the "Premium Finish" option. Note that this will result in a noticeable increase in price. 

## 3D-Printing Data Preparation
For a more budget-friendly version, you may choose to have the case along with the button and slider resin-printed instead through [JLCPCB](https://jlcpcb.com). Pay close attention to the follow parameters:

1. Specify the desired material. My choice for this would be SLA "Imagine Black".
2. You will notice that there is no "threading" option available on JLCPCB's 3D printing form. You will have to force-thread the standoffs yourself. This will almost certainly cause the holes to strip out first, an acceptable compromise as the friction should still hold the standoff firmly in place. 
3. Ensure that the sanding option is set to "Yes". This will greatly improve surface finish quality at little to no extra cost. 
