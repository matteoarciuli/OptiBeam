# OptiBeam:
![original](https://user-images.githubusercontent.com/123570619/215446237-7766246c-6f76-4af5-ad99-504d51ebd536.png)
# Introduction:
OptiBeam is an innovative planning tool able to select the optimal deployment of B5G base stations balancing capital expenditures, EMF levels and user throughput. The information on the users position provided by the 5G architecture plays a central role in our tool, which allows us to optimize the synthesis of the beams on the territory for all the simulated antennas  Intuitively, the user localization precision allows tuning steer and tilt angles for each beam towards the served users. Our planning tool takes as input the candidate positions for the installationof B5G base stations, together with the localization accuracy levels for the users that need
to be served. The multi-objective function is evaluated iteratively by increasing both the number of antennas evaluated each time and the combination of installed base stations. Then, for a given user localization accuracy level (uncertainty area), as output is provided the winner deployment of gNB site positions.

## Requirements:
- Matlab: widely tested on R2022b (9.13.0.2049777), 64-bit (win64) 
- Matlab Toolbox List:
    * Image Processing Toolbox                             
    * Signal Processing Toolbox                          
    * Automated Driving Toolbox                            
    * Statistics and Machine Learning Toolbox           
    * MATLAB Compiler                           
    * MATLAB Support for MinGW-w64 C/C++ Compiler   
    * Computer Vision Toolbox                          
    * Mapping Toolbox       
- RAM: minimum 4 GBs

## Flowchart :
![block_diagram_optibeam_2 (1)](https://user-images.githubusercontent.com/123570619/215499084-4fb3c086-3062-4dfb-81a0-189faf890b84.png)

## Developer :
- Matteo Arciuli -> [Reach me on LinkedIn](https://www.linkedin.com/in/matteo-arciuli-0733b4136/).

## Other Contributors :
Huge thanks to the collegues of the 5GPENCIL Team:
- Simone Rossetti <simone.rossetti@cnit.it>
- Sara Saida <sara.saida@cnit.it>

For the support functions :
- Sisi Ma (2023). find_pareto_frontier (https://www.mathworks.com/matlabcentral/fileexchange/45885-find_pareto_frontier), MATLAB Central File Exchange. Retrieved January 30, 2023. 
- Amy Farris (2023). read_kml (https://www.mathworks.com/matlabcentral/fileexchange/13026-read_kml), MATLAB Central File Exchange. Retrieved January 30, 2023. 

For the GUI icons designers :
-[Unicons Font](https://iconscout.com/contributors/unicons). 
-[Rank Sol](https://iconscout.com/contributors/promotion-king). 

## Acknowledgment :
Special thanks to professor Luca chiaraviglio.
- Luca Chiaraviglio <luca.chiaraviglio@uniroma2.it>

