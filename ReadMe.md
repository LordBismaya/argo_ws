July 25th:
Tested that encoders are working with ros_arduino_bridge. Few things to keep in mind.
1. One of the motor drivers has to be switched on for the encoders to give proper data.
2. This has to be changed later on so that the uC doesnt have any floating voltage.
3. The wheel_radius and wheel_base information still has to be updated properly.
4. The servo Pin has to be configured properly.
5. Today, the testing was done using an independant UNO. It would be great if there are 4 interrupt pins on the original ATmega. Have to verify. 
