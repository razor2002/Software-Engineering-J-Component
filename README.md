# Software-Engineering-J-Component
Drowsiness Detection using Machine Learning Technique made for my Software Engineering Project Component

# Working
In the project we have used the popular OpenCV package to facilitate the detection of the User's face in the picture clicked through the embedded camera module. Further we use the EAR function to detect the eye aspect ratio and based on the aspect ratio and the dimensions of the segmenteed eye we use a model which checks the value of the ratio against the pre-calculated values, to give the final output declaring whether the user is dorwsy or not.

After clicking the image through the embedded camera module the output would look something like this - 

![Output](https://imgur.com/iyboGgg.png)

The result will either be **Drowsy** or **Not Drowsy** depending on the image.

# Usage
The project has limitless applications in the modern real word and the project can be used further in the future for the development of such applications. Below I have listed 2 such use cases, one menial and just provides convinience to the user and the other indispensable as it can even save lives.
- The menial used case would be something simple like, pausing a video if the user has slept off while consuming entertainment off of websites and apps like Netflix, Youtube etc.
- A more important use case would be, using this project for truck drivers. A recent statistic shows that around 13% of the road accidents occur due to sleep deprived truck drivers. In this case, when it's detected that the truck driver is drowsy an SOS message can be sent to a predetrmined contact & an alarm can be sounded to help the driver wake up.
