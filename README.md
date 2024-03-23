# Smart-glove
Embedded Gesture Recognition Device
 
This project consists of two modules 

 1.Hand mounted device for Voice communication and home automation.
 
 2.Wearable device for analysis of hand performance in hand rehabilitation.
<details>
  <summary>Hand Mounted device for voice communication and home automation.</summary>
  <br>
  In this proposed system, the user creates a gesture and holds for recognition.
Each gesture consists of a certain bending of all sensors angles accordingly.
Each finger bend creates a unique ADC value so that when various hand
gestures are made, different ADC values are produced accordingly. Below table
shows the gestures and the corresponding words were heard. Hand gesturing
taken into the prototype can be easily modified using the concept of the number
of ADCs according to user convenience. IN at the same time, the voice output
can be easily changed recording provides the flexibility to change the language
according to different regions. When the mode is changed the flex sensor values
are transmitted and according to the gesture made the home appliances are
controlled.

Here is the block diagram of transmitter section and receiver section:
![transmitter](https://github.com/KumarKarthikeya/Smart-glove/assets/72381320/a9e08dc9-08d3-45d7-8e88-96d419ce6f51)

![receiver](https://github.com/KumarKarthikeya/Smart-glove/assets/72381320/1e6f20f7-f2cb-4546-beac-9768bf64711d)

Algorithm used for this project:
Step1: Take values from flux sensors.
Step2: Check if the glove is in default state.
Step3: If glove is in default state do nothing else check mode.
Step4: Match the values of flex sensors with Threshold values.
Step5: Check if gesture is made to change mode.
Step6: If mode is 0 then the glove is in communication mode.
Step7: Check if the gesture is assigned to any voice message.
Step8: If gesture is assigned to message then output the voice and go to step1.
Step9: If mode is 1 then glove is in automation mode.
Step10: Transmit the flex sensor values encoded through RF transmitter.
Step11: Receive and decode flex sensor values from RF receiver.
Step12: Match the gesture to control the devices connected and go to step1

![flow](https://github.com/KumarKarthikeya/Smart-glove/assets/72381320/f4d69826-0923-4ddd-8def-39e7ba0bfbf6)

This is the report of the project:
[project_report-3.pdf](https://github.com/KumarKarthikeya/Smart-glove/files/14730740/project_report-3.pdf)


</details>

<details>
  <summary> Wearable device for analysis of hand performance in hand rehabilitation.</summary>
  <br>
The aim of this project is to develop a prototype of a hand glove which is useful in physiotherapy sessions of wrist rehabilitation and helps to analyze the finger movements and grasping
power of a person. Flex sensors are used to detect finger movements. The data is stored in a
cloud platform and a graphical representation of his progress is shown to the user. This assistance will enable medical professionals to either better provide for patients with severe injuries
or treat more patients. It also translates into financial assistance as well in the long run. Furthermore, this assessment can be sent to a medical professional for supervision. The results can
be observed through an IoT platform. This non-invasive glove provides real-time feedback and
objective assessment of finger flexion values, enabling personalized rehabilitation and remote
monitoring.
  
![sys](https://github.com/KumarKarthikeya/Smart-glove/assets/72381320/f2ce080c-b8e7-4c13-82d8-ea55c0fcc9ce)

We can use this device with or without doctor presence if we are aware of this before.Firstly patient had wear the glove and perform flexion action to get the reference value of finger movement,While performing exercises described by physician data of finger movements will be stored in cloud and it will used to refer for the medication and see the progress of the rehabilitation process.

  ![blo](https://github.com/KumarKarthikeya/Smart-glove/assets/72381320/97aa7795-a008-434f-b425-020ddf85c6c5)

  Here is full report of the project:
  
[Major_project_ (2).pdf](https://github.com/KumarKarthikeya/Smart-glove/files/14730802/Major_project_.2.pdf)

</details>
