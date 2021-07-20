This is a newtonian Many-Body solver written in python (please find attached jupyter notebook.)  

Input Parameters : 
	1.No. of Bodies
	2.Simulation Time (Seconds)
	3.TimeSteps 
	4.Masses or Mass Limits (for random initialisation)
	5.Initial Positions or Position Limits (for random initialisation)
	6.Initial Velocities or Velocity Limits (for random initialisation)
	7.Gravitation constant (customisable, default = 6.67x10e-11)
	8.Softning parameter 	

Outputs: 
	1.Position, Velocity and Acceleration data at each timestep.
	2.Optionally a video rendering of the same. 

Improvement Scopes:
1.Merger of bodies not included
2.Conversion to relativistic simulation