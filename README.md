CREATE COUNTDOWN TIMER

How to create a countdown timer using python?

The code will take input from the user regarding the length of the
countdown in seconds. After that, a countdown will begin on the
screen of the format ‘minutes: seconds


COUNTDOWN CLOCK

The objective of this python project is to create a countdown timer
and display time. In this python project, the user sets the time and
by click on the start button, it starts the count from that time. When
the time gets over ie when the countdown timer finishes it plays a
sound.

This project build with basic concept of python and
libraries: Tkinter, time and message box

PROJECT PREREQUISITES

Tkinter is a standard GUI Python library from which we can build
GUI applications in the fastest and easiest ways.

The message box module is used when we want to play audio
files with a single line of code. This doesn’t have
any dependencies.


STEPS TO BUILDS COUNTDOWNTIMER

=>Import required Modules

=>Create a display window

=>Display current time

=>Create a countdown timer

=>Create a button


PLAN:-

Enhancement of code with import time to implement
code(eg.black)in output.

1. Importing Required Module

=>The first step in the program is to import
libraries. Here, we required three modules so
we need to import tkinter, time and message
modules.


2.Create a object display window

=>Tk() initializes tkinter to create the window

=>geometry() set the width and height of the
window

=>resizable(0,0) prohibit users to resize the
window

=>title() used to set the title of display window

=>bg used to set the color of background

=>Label() widget used to display one or more
than one line of text that users can’t modify

=>root is the name of our window

=>text which we display on the label

=>font in which the text is written

=>pack organizes widget in block

3.Display Current Time

=>strftime() method return the string
representing the time in given format

=>after() method used to give a delay of 1000
millisecond which is 1 sec

4.Create a Countdown Timer

=>times variable gets the hours value
multiplied by 3600 (1 h = 3600 sec),
mins value multiplied by 60 (1 min =
60 sec), and sec value.

=>‘//’ operator returns the result of the
division in a whole integer value

=>‘%’ operator used to returns the
remainder of the division

=>While time is greater then -1 the
countdown will run. When times
value become 0 then the
countdown stop and a sound play
that indicate your time is up.


5.Create a button

=>Button() widget used to display
a button on window

=>bd sets the size of the border

=>command calls the function
when we click on button

=>root.mainloop() is a method
which executes when we want
to run our program


SUMMARY

With this project in Python, we have successfully created the
countdown clock and timer python project. We used the python
tkinter library for graphics, time library to display current time, and
playsound library to play sound. We learned how to display the
current time and how to build a countdown timer.


CONCLUSION

Python Countdown Timer can be utilized to wait for a certain
duration of time in the idle state before reiterating the same piece
of code in the loop again as required. Python’s time library
contains a predefined sleep() function.

Program is implemented and executed successfully with color







