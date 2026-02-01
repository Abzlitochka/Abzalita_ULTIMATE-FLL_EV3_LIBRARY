You will need 2gyro sensors for correct work with this library
Also the library contains the stallencounter functions like MoveSmart and RunMotorSmart,it runs until motor cant rotate the stallencounter number that you wrote


You will need the OFDL mods block for it link:https://github.com/ofdl-robotics-tw/EV3-CLEV3R-Modules

For the tuning lqr:
Find Static Friction,Find Velocity Constant
Robot Mass
Determine how aggressively the robot corrects errors
Normalize Start with simple values
Tune Position Accuracy
Tune Velocity Damping


For the Async motor run it is simple like it goes Thread the above program after the function starts
