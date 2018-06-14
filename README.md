# unigen-benchmarks
Benchmarks employed in our DAC-14 and TACAS-15 Papers

This repository consists of benchmarks employed in our DAC-14 and TACAS-15 papers. 

The format of these files follow DIMACS format. We extend DIMACS format to allow specification of "Sampling Set" as follows. 

Every benchmark has few lines with "c ind" prefix to specify sampling set. 
For example if the sampling set is {10, 13, 15, 16, 25, 28, 39, 41, 43, 45, 5, 53, 6, 69, 78, 9, 93}

c ind 10 13 15 16 25 28 39 41 43 45 0  
c ind 5 53 6 69 78 9 93 0

Note that each "c ind" line lists only 10 variables at most, followed by a closing '0'.
