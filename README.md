# obstacle_detecting_bot
The bot uses an ultrasonic sensor to measure the distance of the obstacle. It continuously measures the distance using the sensor, moves the bot forward if no obstacle is detected within the threshold distance(in the case it is 100cm), if any obstacle is identified below 100cm than the speed of the motor decreases as per the error calculated and speed of the motor is decreased by PID controller such that it stops smootly.
If obstacle is less than 100cm the lcd displays "OBSTACLE DETECTED" in first row and speed of the motor in second row.
If not it shows "OBSTACLE UNIDENTIFIED" in first row and speed of the motor in 2nd row.
Kp,Ki,Kd values are found out by testing the output of motor speed.
