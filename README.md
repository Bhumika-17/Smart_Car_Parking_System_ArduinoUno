# Smart_Car_Parking_System_ArduinoUno

I’ve built a parking system using arduino which helps reducing the traffic on the roads and also prevent drivers from getting stuck in the areas due to the non-availability of parking. 

Components :
1. Arduino Uno 
2. IR Sensor
3. Servo Motor
4. 16x2 LCD i2c Display

Working : 
1. As we know, a parking lot always has a fixed number of slots. I placed an IR proximity sensor at every slot which detects whether a car is parked in that parking slot or not.
2. As soon as any car arrives at the parking gate, the LCD display displays the empty number of empty slots and the servo motor opens the gate only if any one or more parking slots are available.
3. The parking gate won’t open if the parking is fully occupied.

