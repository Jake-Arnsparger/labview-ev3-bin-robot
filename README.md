# labview-ev3-bin-robot
Lego EV3 robot programmed in LabVIEW that follows a line, finds bins with an ultrasonic sensor, and sorts them by weight. Built as a team project. 

Hardware and Software: LEGO EV3, Lego Sensors, Lego Motors, and used LabVIEW 2016 with the Lego Mindstorms module. 

How it works:
- Line Following: One line and dashed lines, used two light sensors that find the color black and steer the robot     using sensorlogic
- Bin detection: the ultrasonic sensor finds a bin ahead
- Sorting: The robot measures/senses the bins weight and if it is organic(lighter) or metal(heavier) it moves to the corresponding dropo-ff marked by the matching color
  
How to Run: 
1. Open "13 Robot.1vrbt" in Labview 2016 with the Mindstorms module installed.
2. The VIS in Robo_Programs call each, so the program runs as one linked set instead of from a single main file.
3. Connect the EV3 and check that the sensor and motor ports match the front panel.
4. Run the top-level VI

Worked in testing; the issue at demo time was likely hardware. 

Credits: 
Jake Arnsparger: Code Base, Hardware and Documentation
Logan: Code base, Hardware, Documentation
Dillion: Hardware, and Testing

