# OpenGL-AnimatedTimer-Tool
An openGL ES 2.0 Android timer animation tool that draws a timer based on the number of milliseconds that are provided to its constructor function. Also can be easily started and stopped, and the number of iterations can be stored to save the current state of the timer animation for pausing. 

To use the timer, a custom openGL view must be included. Use the myGLSurfaceView class provided in this repository to do so. 

Also, add the following line to the android manifest file:
<uses-feature android:glEsVersion="0x00020000" android:required="true" /> 

