# Alarm Clock In Python

A Very Awesome Python Project using Tkinter and time liblary in Python To Create A Alarm Clock

# Prerequisites

A Very Good Knowledge Of Tkinter Liblary and Basic Python Fundamentals 

# Explanation:

To Initialize tkinter, we pass a command under the name clock as Tk().

The dialog box has the title as DataFlair Alarm Clock with a geometry of (400*200). We pass on the heading to mention the time format for 24 hours using time_format.

The second heading is given above the user input boxes for the labeling to be “Hour Min Sec” using addTime.

Just to make the dialog box look funkier, adding another label as “when to wake you up” using setYourAlarm.

As we have already converted the current time in the string before (actual time), the variables we initialize for the user input dialog boxes are in StringVar().

Finally make the input boxes such as hourTime, minTime, and secTime which takes the entry of the time the user wants to set the alarm on in 24-hour format.

Submit takes the command of the defined function actual_time and executes the clock as it acts as a set button to start the program.

Clock.mainloop() is the basic and the last command was given to compile all the previous commands with their basic settings of color, font, width, axis, etc. and displays the window as soon as the program is run


