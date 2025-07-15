👥 Team Members
Meet the brilliant minds behind KillBot X:

Kathiusca Arcia

Sofia Barrias

Estyfen Adames

You can find both formal and fun photos of our team in the /t-photos folder.

🚗 Vehicle Overview
Our autonomous vehicle is designed to perform consistent, high-speed laps using precise sensor feedback and efficient motor control.
Photos from all angles are located in the /v-photos folder for better understanding of the design.

Chassis: Custom-built using LEGO Technic components

Controller: LEGO Mindstorms EV3

Main Sensor: Gyroscope

Drive System: Two-motor differential drive

🎥 Video Demonstration
The robot in action!
Watch our autonomous run in the qualifying round via this YouTube link:
📹 KillBot X in Action

Link is included in the video/video.txt file.

🔌 Electromechanical Schematics
The /schemes folder contains detailed diagrams showing:

All electronic components

Motor connections

Sensor integration

Power distribution
These diagrams help understand how the hardware integrates with our EV3 controller.

🧠 Programming with LEGO Mindstorms EV3
We used the LEGO Mindstorms app to develop our control algorithm. The gyroscope sensor is central to our navigation system.

🔁 Block Sequence Used:
Start Block (Play):

Initializes the program.

Gyroscope Sensor Block:

Reads the robot’s orientation.

Sound Block:

Robot says “Okey-Dokey” to confirm start.

Motor A Block:

Set to -100 power/sec for forward movement.

Motor D Blocks (Steering):

Initial position: 0 degrees

Adjusted: -100 power, -23 degrees
(Varies slightly depending on track quadrant)

Double Loop Structure:

Inner Loop:

Controls motor A at -100 power.

Sets desired lap count (e.g., 3 laps).

Outer Loop:

Exit condition based on gyroscope reading.

Uses comparison: > 3 and value 1060

Adjusted from 360° x 3 = 1080 for tuning.

🔧 This loop allows dynamic lap control and fine-tuning of stop position.

You can find the actual program in the /src folder, compatible with LEGO Mindstorms EV3.

🏁 Project Highlights
✅ Reliable lap detection using gyroscope

✅ efficient motor control

✅ Public video documentation

✅ Full team collaboration
