# Gesture Controlled car
I am working on a hand gesture controlled car

                             | Engineer    |        School        |    Area of Interest    |       Grade       |
                                                         
                             | Daniel Wong | Berkeley High School | Electrical Engineering | Incoming Freshman | 
             
![Headstone Image](https://user-images.githubusercontent.com/87200410/126531426-57424211-d1bd-4591-8b19-f3d52ecbad05.jpg)
  
# Final Milestone
My final milestone is the increased reliability and accuracy of my robot. I ameliorated the sagging and fixed the reliability of the finger. As discussed in my second milestone, the arm sags because of weight. I put in a block of wood at the base to hold up the upper arm; this has reverberating positive effects throughout the arm. I also realized that the forearm was getting disconnected from the elbow servo’s horn because of the weight stress on the joint. Now, I make sure to constantly tighten the screws at that joint. 

[![Final Milestone](https://res.cloudinary.com/marcomontalbano/image/upload/v1612573869/video_to_markdown/images/youtube--F7M7imOVGug-c05b58ac6eb4c4700831b2b3070cd403.jpg )](https://www.youtube.com/watch?v=F7M7imOVGug&feature=emb_logo "Final Milestone")

# Second Milestone

My second milstone was to get the accelerometer to start printing values like velocity,tempature, and XYZ. In order to do this I would input a line of code that would track the X,Y, and Z axis of the accelerometer. For my project I focused on the Y axis, next I connected my two ESPs through a MAC adress so the accelerometer values would connect to the motors. uring this part of my project I faced many issues eith ther accelerometer and the ESPs, sometimes when I tried to get values I would instead get weird gibberish to show up. Here are some exmaples of my schematics and values.
<p float="left">
  <img src="https://user-images.githubusercontent.com/87200410/126537875-4e5be1fb-e9c5-44cc-ad04-6a87a548ebb5.png" width="500" />
  <img src="https://user-images.githubusercontent.com/87200410/126529318-a3518841-7929-412a-bc69-7075557a8c79.png" width="500" /> 
</p>

[![Third Milestone](https://res.cloudinary.com/marcomontalbano/image/upload/v1612574014/video_to_markdown/images/youtube--y3VAmNlER5Y-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://www.youtube.com/watch?v=y3VAmNlER5Y&feature=emb_logo "Second Milestone")
# First Milestone

My first milestone was putting together the outside of the car chassis and screwing the supports onto it and setting up the motors. Next I did some side projects to get used to using the ESP32 and learned more about coding on Arduino. I had to download some libraries into Arduino like TwoWayESP and TwoWayJSON to make sure my Arduino code would connect to the ESP32. Ardunio is a coding app which uses C++. I had a lot of trouble getting the ESP32 to connect to my code and get my motors running but I eventually got them fixed. After I got all that set up I got to working on my motor drivers and connecting the motors to them. Along the way I had lots of issues with securely attaching the wires or plugging into the wrong ports. I plugged in all the wires and got all four motors to spin.

(Here's an example of some of the coding I did):


                                                  void loop() {
                                                  // Move the DC motor (A, B) forward at maximum speed
                                                  Serial.println("Moving Forward");
                                                  digitalWrite(motor1Pin1, LOW);
                                                  digitalWrite(motor1Pin2, HIGH);
                                                  
                                               
 [![Milestone 1](https://res.cloudinary.com/marcomontalbano/image/upload/v1626886081/video_to_markdown/images/youtube--bFIKQoxqm6g-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://youtu.be/bFIKQoxqm6g "Milestone 1") 

