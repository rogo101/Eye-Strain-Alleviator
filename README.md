# Senior-Design

To run, make sure all dependencies in requirements.txt are satisfied. 
Then, type python3 main.py into command line.

The GUI uses the form mainWindow.ui to create the layout, and is then converted to mainWindow.py via the commands in runGui.txt file. The form can be edited in Qt Designer. 

main.py: initializes the GUI and wires up all components of the project to the GUI.
blinkDetection.py: records and analyzes the video to get blink rate
eyeStrainAlleviator.py: Takes blink rate and modifies display brightness accordingly (works only for a mac).
