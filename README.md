Gesture-Recognition
===================
This project was done as a part of MIT media labs workshop held in India.

Programming Language: Python

Description: This is an application for controlling functionalities of a device or software by gesture recognition.

Setup:

1.Get 4 sensors placed at  four corners of a square

2.Connect these 4 sensors to aurdino board

3.Connect aurdino to laptop through usb

Working:

1.If you are running on ubuntu the device will be detected in /dev/tty0

2.The sensor readings are read from /dev/tty0

3.Consider a,b,c,d as 4 sensors.

4.sensors are set to 1 or 0 based on some threshold reading.

5.If a=1,b=1,c=1,d=1 -> perform operation A,
  If a=1,b=1,c=1,d=1 -> perform operation B,
  Like this different combinations are taken and accordingly specify operations are peformed.

Use cases:

1.Controlling any device by simple hand gestures.

2.Control the operation of a software.For example, if vlc media player is considered, play,pause,stop or do any media player operaions just by simple hand gestures.
