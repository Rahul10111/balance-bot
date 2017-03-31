there are 2 codes for the project 

1. the code for balancing the bot 
2. the other code for joystick i.e to send command to the robot to traverse a path

test balance motion:
	
	here the code is written for sensors i.e 
		1.ADXL345	(acclerometer)
			// I2C device class (I2Cdev) demonstration Arduino sketch for ADXL345 class
			// 10/7/2011 by Jeff Rowberg <jeff@rowberg.net>
			// Updates should (hopefully) always be available at https://github.com/jrowberg/i2cdevlib
		2.L3G4200D	(gyroscope)
			// I2C device class (I2Cdev) demonstration Arduino sketch for L3G4200D class
			// 7/31/2013 by Jonathan Arnett <j3rn@j3rn.com>
			// Updates should (hopefully) always be available at https://github.com/jrowberg/i2cdevlib
	microcontroller
		1.atmega 2560(arduino mega) for balancing the robot
		2.atmega 32(arduino uno)    for reading data from joystic and sending it to balance bot
	
	xbee module used for communication between the joystick controller and the robot
	serialport1 is used to communicate through xbee

send data xbee:
	reading data from joystick
	for serial communication software serial is used to communicate throug xbee
