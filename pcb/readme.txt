Part number:  	JAGCGA
Revision:	0

Table of Contents:

1) File Manifest
2) PCB Requirements
3) Assembly Requirements

1) List of files in JAGCGA.ZIP:

	jagcga.top - Gerber/RS274X format top copper layer (component side/layer 1)
	jagcga.sst - Gerber/RS274X format top silk screen (component side)
	jagcga.smt - Gerber/RS274X format top solder mask (component side)
	jagcga.spt - Gerber/RS274X format top solder paste (component side)

	jagcga.in1 - Gerber/RS274X format inner layer 1 (GND/layer 2)
	jagcga.in2 - Gerber/RS274X format inner layer 2 (VCC/layer 3)

	jagcga.bot - Gerber/RS274X format bottom copper layer (secondary side/layer 4)
	jagcga.smb - Gerber/RS274X format bottom solder mask (secondary side)

	jagcga.fab - Gerber/RS274X format board outline (for routing)

	thruhole.tap - NC Drill File
		NOTE:  Specified drill sizes are for Finished/Plated Hole sizes

	assembly.pdf - PDF format assembly drawing
	bom.csv - Excel format Bill of Materials
	centroid.csv - XYRS/comma-delimited pick-and-place file for SMD components
		NOTE:  XY IN MILLIMETERS, Clockwise Rotation, Excel Compatible
	
2) PCB Requirements

	Min copper line/space:	0.2mm/0.2mm	(7.875mil)
	Min copper thickness:	0.5 ounce outer layers, 1 ounce inner layers

	Finished hole sizes:	0.020", 0.039", 0.090"

	Board stack-up:		4 layer, .062" thick, standard construction
				NOTE:  Layer ID text is located near 1.3"x1.15"

	Board size:		82mm x 37.5 mm 	(3.228" x 1.476")
				NOTE:  See jagcga.fab for outline -- one notch is present

	Board finish:		Silver Immersion
				NOTE:  Edge connector does NOT require finishing for wear resistance
	
	
3) Assembly Requirements

	Double-sided:		NO
	RoHS compliant:		NO -- some thru-hole parts are leaded

	Standard SMD parts:	25
	Fine pitch SMD parts:	3 (U1-U3), all 0.5mm pitch
	Thru-hole parts:	3 (J1, J2, J4) to be hand soldered
	Manual SMD placements:	1 (J3, MINI-USB B RCPT) is an irregularly shaped connector
