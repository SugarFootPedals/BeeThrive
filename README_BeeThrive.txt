BeeThrive is an Arduino-powered Bee Hive monitor system, based on the Atmega328 controller.

The circuit board is currently un-verified and arduino code has not been written.

It monitors the exterior temperature and humidity via a DHT11 sensor, plus the interior
temperature and humidity of three Bee Hives via  DHT11 remote sensors.
Data is displayed on an OLED Display.

Data is also logged (and time-stamped via the RTC circuit) onto a microSD card.

If temperature or humidity is too high for the Bee Hive, a tiny
25mm X 25mm fan, located on the remote sensor board, is turned on.

Remote sensors/fans connect to the main controller via RJ12 cables and connectors.

The entire system is Battery/Solar Powered and has a Battery Charging circuit.

The option to add an ESP01S module for wireless connectivity has been included.

Unused pins of the microcontroller are available for experimentation, such as adding 
tiny heating elements for winter months, adding more remote sensors, etc.



Optimum Hive Temperature is between 90-97*F.
Humidity of the Hive should be between 50-60%
Queen must maintain a body temp between 80-97*F during winter