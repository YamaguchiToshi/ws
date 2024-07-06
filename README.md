# WebSensory

This application WebSensory is a web application that allows users to experience sound and animation effects using a pointing device.
It also has a function to record the mouse pointer's trajectory and analyse it.


## Try it out here

https://yamaguchitoshi.github.io/ws/


## Main features

Sensory: 
Animation and sound effects accompany the mouse pointer
This feature is suitable for young children starting to practise pointing devices to learn cause-and-effect relationships

Heat map: 
This function analyses the trajectory of the mouse pointer
The places where the mouse pointer stays are painted blue, green, yellow, orange or red, depending on the time spent.
The closer the colour is to red, the longer the mouse pointer stays in the area.

Trajectory plot: 
If the mouse stays at a certain location (within 60 pixels) for a certain amount of time (300 ms), a circular symbol will be displayed at the coordinates.
The diameter of the circle changes according to the time spent, and the time spent is displayed in ms.
Each circle is connected by a line and numbered in the order in which they stayed.

![heatmap_export (5) (1)](https://github.com/YamaguchiToshi/ws/assets/1419375/bb805d60-fbaf-4832-9757-11c0ccdde804)


## Pointing device

Any pointing device can be used, as long as it is correctly set up on the operating system on which the browser is running.
This means you can use a mouse, trackball, joystick or eye tracker.
