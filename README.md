# Real-time face recognition and intrusion alertion
We implement a Real Time Face Recognition algorithm to a live feed delivered by our android app CCTV Cam. This feed is analysed for recognizable faces and output is delivered in the form of IoT controlled lights and buzzers

## Our model
- We developed an Android app called CCTV Cam that relays the feed from the camera of the android phone to our python client which runs the Face Recognition module.
- Using OpenCV in Python, we implemented Real Time Face Recognition using the Linear Binary Patterns Histogram (LBPH) algorithm. 
- We process the images from the frames in the live feed and use them to recognize the faces. The model will need to be trained on student faces before it can correctly identify them to a certain degree of certainty.
- Output through an Arduino, that controls buzzers and lights, determine whether the person is a verified individual or not.

With a successful real time working model, security clearance can be granted to students, without the need to show identification cards.

## Language
- Python
- Java
- C++

## Frameworks and tools
- Jupyter Notebook
- Android Studio
- OpenCV
- Arduino IDE

## Data flow

<img width="600" alt="Capture" src="https://user-images.githubusercontent.com/29833297/56853506-a0540980-6946-11e9-9992-2083ecab24f9.PNG">


<img width="600" alt="Capture" src="https://user-images.githubusercontent.com/29833297/56853510-b366d980-6946-11e9-8ef8-3b82ed61e931.PNG">


## Results

<img width="700" alt="recognizing" src="https://user-images.githubusercontent.com/29833297/56853514-bfeb3200-6946-11e9-9077-b9461fa1c3fd.PNG">
