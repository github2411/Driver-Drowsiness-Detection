# Driver Drowsiness Detection

Driver Drowsiness Detection is a Python-based project employing Dlib and OpenCV. The project leverages the capabilities of Dlib's 68 facial landmark detector and face detector to identify key points on the human face. Specifically, the 68 facial landmark detector, a highly trained and efficient tool, is used to discern whether the eyes are open or closed.



## Operational Flow

The operational flow of the project involves the direct interaction with the landmark detector, as depicted in the provided screenshot.

(![Active](https://github.com/github2411/Driver-Drowsiness-Detection/assets/67455073/75497800-2c8a-41e5-8854-eca3663357f0)
)
![Drowsy](https://github.com/github2411/Driver-Drowsiness-Detection/assets/67455073/a1897c7d-2d31-480d-98c7-7ebeb479928f)
![Sleeping](https://github.com/github2411/Driver-Drowsiness-Detection/assets/67455073/dc392275-a051-4ed6-ab58-cd416891c75f)


In the images above, landmarks are identified using the detector. Subsequently, a ratio is computed, defined as the 'Sum of distances of vertical landmarks divided by twice the distance between horizontal landmarks.' This ratio is adaptable to your system, allowing you to configure thresholds for states such as sleeping, drowsy, and active.

