# EmbeddedThermal

A project to broker data between a MLX90640 (https://www.sparkfun.com/products/14844) and an Arduino Uno or similarly sized microprocessor. The example code provided by the vendor require an initial struct that is too large for the Uno, so it will likely need to just proxy data to a Windows computer in the car.

The sensor will ultimately relay data to the computer in a format that can be then turned into a video and recorded alongside other video devices. This may additionally in later iterations additionally provide a CANbus gateway and use a larger microprocessor than the Uno so that some processing can occur in the microcontroller. This would allow other live dashboards (e.g. race capture app) to display the data as well and feed to other sources.
