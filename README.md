# STOP WATCH USING PYTHON
The code provided is a Python application that creates a simple stopwatch using the Tkinter library, which is a standard GUI library for Python. The application consists of a window with three buttons (Start, Stop, and Reset) and a label to display the time on the stopwatch.

The stopwatch starts at 00:00:00 and can be controlled using the buttons. The Start button begins the timer, updating the time on the label every second. The Stop button pauses the timer, and the Reset button resets the stopwatch to 00:00:00.

The counter_label function is responsible for updating the time on the label. It uses the datetime module to convert the elapsed time in seconds to hours, minutes, and seconds, and updates the label text with the formatted time. The function is called repeatedly every second using the label.after() method.

The Start function is triggered when the Start button is clicked. It sets a global variable running to True, which indicates that the stopwatch is running. It then calls the counter_label function to start updating the time on the label, and disables the Start button while enabling the Stop and Reset buttons.

The Stop function is triggered when the Stop button is clicked. It sets the global variable running to False, indicating that the stopwatch is paused. It also enables the Start and Reset buttons while disabling the Stop button.

The Reset function is triggered when the Reset button is clicked. It resets the stopwatch by setting the counter variable back to 66600, which represents 00:00:00 time. It updates the label text to "Welcome!" if the stopwatch is not running, or "Starting..." if the stopwatch is running. It also enables or disables the buttons accordingly.

Overall, this code implements a simple stopwatch with basic start, stop, and reset functionality using Tkinter in Python.
