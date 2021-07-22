# Gesture Controlled car
I am working on a hand gesture controlled car

                             | Engineer    |        School        |    Area of Interest    |       Grade       |
                                                         
                             | Daniel Wong | Berkeley High School | Electrical Engineering | Incoming Freshman | 
             
![Headstone Image](https://user-images.githubusercontent.com/87200410/126531426-57424211-d1bd-4591-8b19-f3d52ecbad05.jpg)
  
# Final Milestone
My final milestone was to have a functioning car that could spin and move in different directions. I did a lot of coding and trial and error to get the motors to spin and go different directions. A problem that I faced during this was that not all four of my motors were spinning becaue my 9 volt battery because it wasn't strong enough to ppower all four, so I swithced from the battery to plugging into a outlet in my wall through my arduino uno.
 else if (message == "Righ") {
 
                                     Serial.println("Right");
                                     digitalWrite(motor1Pin1, LOW);
                                     digitalWrite(motor1Pin2, HIGH);
                                     analogWrite(enable1Pin, 220);
                                     digitalWrite(motor2pin1, HIGH);
                                     digitalWrite(motor2pin2, LOW);
                                     analogWrite(enable2pin, 220);
                                                            

[![Final Milestone](https://res.cloudinary.com/marcomontalbano/image/upload/v1612573869/video_to_markdown/images/youtube--F7M7imOVGug-c05b58ac6eb4c4700831b2b3070cd403.jpg )](https://www.youtube.com/watch?v=F7M7imOVGug&feature=emb_logo "Final Milestone")

# Second Milestone

My second milstone was to get the accelerometer to start printing values like velocity,tempature, and XYZ. In order to do this I would input a line of code that would track the X,Y, and Z axis of the accelerometer. For my project I focused on the Y axis, next I connected my two ESPs through a MAC adress so the accelerometer values would connect to the motors. uring this part of my project I faced many issues eith ther accelerometer and the ESPs, sometimes when I tried to get values I would instead get weird gibberish to show up. Here are some exmaples of my schematics and values.
<p float="left">
  <img src="https://user-images.githubusercontent.com/87200410/126537875-4e5be1fb-e9c5-44cc-ad04-6a87a548ebb5.png" width="500" />
  <img src="https://user-images.githubusercontent.com/87200410/126529318-a3518841-7929-412a-bc69-7075557a8c79.png" width="500" /> 
</p>

[![Milestone 2](https://res.cloudinary.com/marcomontalbano/image/upload/v1626978558/video_to_markdown/images/youtube--IZBxwmPVjPQ-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://www.youtube.com/watch?v=IZBxwmPVjPQ "Milestone 2")

My first milestone was putting together the outside of the car chassis and screwing the supports onto it and setting up the motors. Next I did some side projects to get used to using the ESP32 and learned more about coding on Arduino. I had to download some libraries into Arduino like TwoWayESP and TwoWayJSON to make sure my Arduino code would connect to the ESP32. Ardunio is a coding app which uses C++. I had a lot of trouble getting the ESP32 to connect to my code and get my motors running but I eventually got them fixed. After I got all that set up I got to working on my motor drivers and connecting the motors to them. Along the way I had lots of issues with securely attaching the wires or plugging into the wrong ports. I plugged in all the wires and got all four motors to spin.

(Here's an example of some of the coding I did):


                                                  void loop() {
                                                  // Move the DC motor (A, B) forward at maximum speed
                                                  Serial.println("Moving Forward");
                                                  digitalWrite(motor1Pin1, LOW);
                                                  digitalWrite(motor1Pin2, HIGH);
                                                  
                                               
 [![Milestone 1](https://res.cloudinary.com/marcomontalbano/image/upload/v1626886081/video_to_markdown/images/youtube--bFIKQoxqm6g-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://youtu.be/bFIKQoxqm6g "Milestone 1") 

