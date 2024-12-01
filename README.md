# Digital-clock
The provided code is a simple Python program that creates a digital clock using the tkinter library for GUI development. Here's a brief explanation:

Imports:

1. tkinter and ttk are imported for GUI components.
2. strftime from the time module is used to fetch the current time.

Window Setup:

1. A Tk window is created and given the title "Clock".

Time Function:

1. The time() function retrieves the current time in the format HH:MM:SS AM/PM using strftime.
2. It updates the text of the Label widget (label.config) with the current time.
3. The function calls itself every 1000 milliseconds (1 second) using after.

Clock Display:

1. A Label widget (label) is created to display the time.
2. It uses a custom font ("ds-digital") and has a black background with cyan text.
3. The label is packed into the window and centered.
