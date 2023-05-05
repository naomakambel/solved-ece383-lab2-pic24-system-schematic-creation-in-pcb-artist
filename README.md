Download Link: https://assignmentchef.com/product/solved-ece383-lab2-pic24-system-schematic-creation-in-pcb-artist
<br>
<em>Goals: The goals of this lab are to introduce students to the creation of a partial PIC24-based schematic and printed circuit board layout in PCB Artist.</em>

<h1>1.     Introduction</h1>

The purpose of this lab is to increase student familiarity with the PCB Artist software. Students will design the PIC24 power circuitry that will be used in later labs as well as create a printed circuit board layout of the design.

This lab requires you to capture portions of the screen. The lab computers use the Windows 10 operating system. This includes the “Snipping Tool” that may be used to capture portions of the screen. As always, read through the entire lab and scan any supplied files before starting work.

<strong>Figure 1. PIC24HJ128GP502 and Partial Power Circuitry</strong>

<h1>2.     PRELAB</h1>

For this lab assignment, all tasks should be completed as a pre-lab assignment prior to your assigned lab time.

<strong>TA check: As soon as you enter lab, provide the TA with a pre-lab report that includes the PIC24 schematic, and the PCB layout. Lab time will be devoted to correcting any errors in the PIC24 schematic and PCB noted by the lab instructor. Make sure your group member names and date are on the pre-lab report.</strong>

<h1>3.     TASK 1: Basic PIC24 Power Circuit</h1>

Using PCB Artist, create a basic power circuit for a PIC24 system. Your schematic should closely resemble the schematic shown in Figure 1. The ECE383 component libraries available on the class website include the PIC24HJ128GP502 microprocessor and the LM2937-3.3 voltage regulator components. The <em>Vdd </em>and <em>GND </em>components are located in the <em>schema </em>library. The capacitor (C) components, labeled C1-C5, are available in the <em>discrete </em>library. You will use multiple instances of the capacitor (C) component in this design. Note carefully that the capacitors have differing values and these values should be displayed in your circuit. The values for individual capacitors may be changed by right clicking on the component, selecting <em>Properties-&gt;Values </em>and setting the “Value=…” entry to the appropriate value. The capacitor’s value is displayed in the circuit diagram if the radio checkbox for the “Value=…” entry is checked.

For the PIC24 we will also enter Manufacturer and Distributor information and part numbers. The values for individual components may be changed by right clicking on the component, selecting <em>Properties-&gt;Values </em>and setting the “Value=…” entry to the appropriate value. For the PIC24, the manufacturer will be “Microchip” and the Manufacturer part number will be PIC24HJ128GP502-I/SP. Use Digikey as the distributor and, using the Digikey website, find and enter the Digikey part number for the processor. Create a new value called “Website” and enter the Website URL for the Digikey website for the PIC24HJ128GP502-I/SP processor.




<strong>TA check: Show the TA the schematic design. Use a screen capture tool to capture the schematic window and include it in your lab report.</strong>

<h1>4.     TASK 2: Creation of a Printed Circuit Board Layout with PCB Artist</h1>

For this task we will create a printed circuit board layout from the PIC24 schematic created as a part of task 1.

The board size should be 60mm x 60mm. The board part number should be “ECE383-LAB2” and the Revision Number should be “001”. These parameters can be set through the PCB wizard. Use your experience from previous labs to create a PCB similar to the diagram shown in Figure 2 below.

Figure 2. PIC24HJ128GP502 and Partial Power Circuitry Printed Circuit Board

<strong>TA check: Show the TA the printed circuit board you completed. Include a printout of your PCB in your lab report.</strong>

<h1>5.     TASK 3: Basic PIC24 System Schematic</h1>

Using PCB Artist, create a basic PIC24 system as shown in Figure 3 below. You may use your schematic from the previous task as a starting point for this design. The resistor (RA) components, labeled R1-R2, are available in the <em>discrete </em>library. Use will also use the SW_FSM2JH component for the pushbutton and the LED component for the single LED in the system. These components are also available in the <em>discrete </em>library.

<sub> </sub>Figure 3. Basic PIC24 System Schematic




<strong>TA check</strong>: <strong>Show the TA the schematic design. Use a screen capture tool to capture the schematic window and include it in your lab report.</strong>

<h1>6.     TASK 4: PIC24 System Printed Circuit Board Layout</h1>

For this task we will create a printed circuit board layout from the PIC24 schematic created as a part of task 3. The board size should be 60mm x 60mm. The board part number should be “ECE383-LAB2” and the Revision Number should be “002”. These parameters can be set through the PCB wizard. Use your experience from previous labs to create a PCB similar to the diagram shown in Figure 4 below.




<strong>Figure 4. PIC24 System Printed Circuit Board</strong>













<strong>TA check</strong>: <strong>Show the TA the printed circuit board you completed. Include a printout of your PCB in your lab report.</strong>

<h1>7.     Laboratory Report</h1>

No later than a week from the day the lab is performed, provide the TA a printed copy of the lab report following the ECE383 Lab report Template given on the class website. Each lab group will submit one joint lab report to the TA. Your report should have the reporting requirements needed for Tasks 1, 2, 3, and 4.