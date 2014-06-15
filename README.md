microsaccade
============

A matlab function for detecting microsaccades (small rapid eye movements). 

About the Detection Algorithm:  
The algorithm defines an eye movement to be a microsaccade when the speed crosses 8 deg/s, is between 10 and 300 ms in duration, starts at least 20 ms after any previous microsaccade, has a minimum length of 0.05 degrees, and the eye direction exceeds no more than 30 degrees for each 5 ms cut of the total time period of the microsaccade.

The algorithm also computes peak velocity and amplitude of the microsaccades.

Haider Riaz - haider.riaz@mail.mcgill.ca  
McIntyre Medical Building Room 1225  
Department of Physiology, McGill University

