Wro-2025-future-engineers--KillBot X


The folder we have uploaded contains: 

A folder named ¨t-photos¨ with a normal photo and a funny photo of the tree members of the team: Kathiusca Arcia, Sofia Barrias and Estyfen Adames.

A folder named ¨v-photos¨ with six vehicle photos from every side, from top and bottom.

A folder named ¨video¨ with a text file with the link to the video loaded on YouTube. the video is public and accessible by link. It shows the vehicle driving autonomously.

A folder named ¨schemes¨ that contains two shematic diagrams of the electromechanical components ilustrating all the elements (electronic components and motors) used in the vehicle and how they connect to each other.

A folder named ¨src¨ that contains the code used to control the vehicle during the qualifying round and the final round.

Two files named 
Programming with LEGO Mindstorms EV3
For this project, we used the LEGO Mindstorms application, which is compatible with the EV3 brain, and we worked with the gyroscope sensor as the main control element. Below are the steps followed in the programming process:

Block Sequence:
Start Block (Play):

Marks the beginning of the program.

Gyroscope Sensor Block:

Added to read the robot’s orientation.

Sound Block:

The robot plays the message “Okey-Dokey” to indicate that it has started the process.

Motor Blocks:

Three blocks are used to control the robot's movement:

Motor A: Set to -100 power per second.

Motor D (directional): Set to 0 degrees initially.

Motor D (again): Set to -100 power and -23 degrees (degrees may vary depending on the quadrant of the track).

Double Loop:

An inner loop and an outer loop are used to control the number of laps the robot must complete.

Inner loop:

Contains a motor A block configured to -100 power to allow the robot to keep moving forward.

The number of desired laps is set here, in this case: 3 laps.

Outer loop:

Uses the gyroscope sensor as the exit condition.

A comparison is set: greater than ( > ) 3 and value 1060.

The value 1060 comes from multiplying the 360° of a full lap by the 3 desired laps (360 x 3 = 1080, adjusted to 1060 for better accuracy).

This value can be modified if the robot finishes before or after the starting point, allowing fine-tuning of the circuit.
