Screen Time Tracker:

This project is a macOS script that tracks the user's total screen time based on their activity 
and sends notifications after a specific duration to remind them to take a break.

Features:
~ Monitors screen usage in real-time.
~ Sends a voice alert and displays a notification when the total screen time reaches the specified limit.
~ Repeats the alert every hour if the user continues using the system without taking a break.

Requirements:
~ macOS
~ Python 3
~Quartz library (pip install pyobjc-framework-Quartz)
 
How It Works:
The script checks the idle time (time since the last input) every minute.
If the idle time is less than the check interval, the system is considered active, and the screen time counter increases.
Once the total screen time reaches 1 hours (3600 seconds), an alert is triggered:
A voice notification reminds the user to take a break.
A pop-up alert displays on the screen, encouraging the user to prioritize their health.
The alert repeats every hour if the user continues to use the system without a break.

Author
Karan Raj











C
