# Robotics-Arm
Start
|
|--> Initialize Servos and Ports
|
|--> Initialize Encoder Motors
|
|--> Define Interrupt Service Routines (ISR) for each Encoder
|
|--> Define movement functions (move, moveDegrees)
|
|--> Define arm and clamp control functions (armup, armdown, unclamp, clamp)
|
|--> Setup
|    |
|    |--> Set PWM
|    |
|    |--> Attach Interrupts
|    |
|    |--> Set Encoder Parameters
|    |
|    |--> Execute Robot Steps
|         |
|         |--> Move Forward
|         |
|         |--> Move Backward
|         |
|         |--> Move Right
|         |
|         |--> Move Left
|         |
|         |--> Clamp
|         |
|         |--> Unclamp
|         |
|         |--> Arm Up
|         |
|         |--> Arm Down
|
|--> Loop
     |
     |--> Loop through Encoders
     |
     |--> Check if Encoder has reached target position
|
End
