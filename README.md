# Switching-Processes-in-AC-curcits-1ph-3ph-
This is a Matlab-App Model to analyse switching processes in AC curcuits, that allows to choose between one- and threephase analysis and different loads.

The main purpose to build this App was to create a learning enviroment, where students in Electrical Engineering are able to comprehend complex current and voltage characteristics during switching on and off processes in AC curcuits. The user should be able to change the experimental setup at some points and plot the results afterwards. The setup is based on a test bed at the "Hochschule Darmstadt". The App was tested on a Windows 10 (64 Bit) Operating System. After installing the App on Matlab, a new icon should be visible in the App-List.

To run the Model you will need the following Matlab-Packeges:
  - Simulink
  - Simscape
  - Simscape Electrical
  - Matlab Coder

The following changes can be made:
  - selecting the setup: ON/OFF
  - turning loads ON/OFF
  - for researches in three-phase-current: Star connection on loadside grounded/isolated
  - adjust the switching angle
      - 3ph => same angle for all three phases
      - 1ph => individual switching angle for each phase
  - Selecting the diagrammed measurement results 

The Simulation can be started by clicking on the "Ein" Button at the top right corner. The red light bulb should turn on for a few seconds and the plot should be visualized as configured. By first clicking on the axis and then on the "Home" button at the right top corner above the plot, the scale can be set back. The plot also can be stored as a Matlab figure, image or vector graphic. 
Furthermore, it has to be pointed out that, the switching on and off time of the second capacitor (bottom right corner) varies statistically. Differnt plot-results may be possible by repeating the simulation with the same settings. 
