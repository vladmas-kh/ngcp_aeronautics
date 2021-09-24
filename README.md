# ngcp_aeronautics
Pogramm to match ecalc results for multicopter to performance requirments

Function 1
Inputs:

Tables:
	range vs airspeed
	time of flight vs airspeed
	vehicle energy capacity
	
	
Outputs:
	Cost of transoprt : Energy from the batery spend per meter vs ground speed and wind speed
	Power required    : Energy from the batery spend per second vs ground speed and wind speed  
	


Function 2
Inputs:
	Cost of transport
	Power required
	Mission segments 
		One segment consisting of: (loiter time or distance to cover , vehicle weight)
	
Outputs:
	Energy spend on each segment

	
Notes:
An option is to get range and air speed tables from ecalc graphs with third party tools.
Say with 
https://physlets.org/tracker/
or this
https://automeris.io/WebPlotDigitizer/
