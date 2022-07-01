# Facial Recognition Door Lock
A door lock that only opens if it recognizes the guest. It utilizes Raspberry Pi and Arduino in order to process the data, and it uses the data collected from the camera in order to determine if it should open the lock.

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Angela Qian | Basis Independent Silicon Valley | Computer Science | Incoming Senior

![Headstone Image](https://i.imgur.com/yruTXYJ.png)
  
# Final Milestone
My final milestone was adding two things. The first was a special type of guest where the door would still open for them, but it would still send me an email of their picture. The second was two LED's, one red and one green. When the camera detects a face after taking a picture, the red LED quickly flashes two times. If the face is someone that should be allowed through, the green light flashes for five seconds, and if the face is someone that shouldn't be allowed through, the red light flashes for five seconds. I did this by adding a few more lines to my Arduino code.
![third thing](https://i.imgur.com/NkHwyxZ.png)
[![Final Milestone](https://res.cloudinary.com/marcomontalbano/image/upload/v1612573869/video_to_markdown/images/youtube--F7M7imOVGug-c05b58ac6eb4c4700831b2b3070cd403.jpg )](https://www.youtube.com/watch?v=F7M7imOVGug&feature=emb_logo "Final Milestone")

# Second Milestone
My second milestone was finishing the software, making it be able to recognize a face, and open and close the door based on if the face it saw was stored in the database. If it doesn't recognize the face, it sends an email of the person's picture to me. It does this by storing the pictures of people I want to let in into AWS's S3, and saving the face ID's of the photos on DynamoDB, and if the face ID of the person captured by the camera matches the face ID of someone that was stored in DynamoDB, then the door unlocks for five seconds. 
![second thing](https://i.imgur.com/OaX4dbc.png)
[![Second Milestone](https://img.youtube.com/vi/jp6as7RJs-g/maxresdefault.jpg)](https://www.youtube.com/watch?v=jp6as7RJs-g "Second Milestone")
# First Milestone
  

My first milestone was hooking the servo to the Arduino, and making it move. I wired the Arduino to the Raspberry Pi and wrote a quick program to move the servo. I attached the servo to a gear that would be able to slide the door lock open and close. I have attached the wiring chart below
![Fabulous Bombul](https://user-images.githubusercontent.com/107577606/175604084-d2da880f-609b-4c51-8834-3e7a746f9182.png)

[![First Milestone](https://img.youtube.com/vi/HKv7XRAH6as/maxresdefault.jpg)](https://www.youtube.com/watch?v=HKv7XRAH6as "First Milestone")
# Starter Project
  

My starter project was a Useless Machine, which, as suggested by the name, does absolutely nothing of use. It's a box with a switch on it, so that when you switch the machine on, an arm comes out and switches it off again. To make it, I first attached the arm to a motor, then I soldered two switches onto the board. I attached the motor with the arm to the board, then hooked both the motor and the board to a battery, and arranged it so when the arm goes up it flips the top switch, and when the arm comes down again it presses on the other switch. Then I place it in the box provided. Since I finished early, I wanted to add an extra part so that it could count the number of times the switch has been flipped. However, it seems like when I was soldering something I may have burned one of the wires, since it didn't work when I attached it to the machine.

[![Starter Project](https://img.youtube.com/vi/3kA291cp7fM/maxresdefault.jpg)](https://www.youtube.com/watch?v=3kA291cp7fM "Starter Project")
