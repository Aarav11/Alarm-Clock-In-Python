# Alarm Clock In Python

It is no doubt that an alarm clock is always handy to alert us whenever we sleep, take a short nap, or to remind us about the work, we always get oblivious about.

Our ancestors have been using an alarm clock, going back to its 2,000 years long history but over time, the new advancements in technologies allow us to keep an alarm clock without it containing a dial, gear trains, etc. How? Let’s find out further.

# About The Project

The objective of our project is to implement an alarm clock using Python. Python consists of some very innovative libraries such as datetime and tkinter which help us to build the project using the current date and time as well as to provide a user interface to set the alarm according to the requirement in 24-hour format.

# Project File Structre

First, let’s check the steps to build an Alarm Clock program in Python:

Importing all the libraries and modules required
Putting forward a while loop which takes the argument of the time, the user wants to set the alarm on and automatically breaks when the time is up, with sound
Create a display window for user input.

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


