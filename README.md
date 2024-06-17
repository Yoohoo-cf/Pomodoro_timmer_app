## Pomodoro Timer

A simple Pomodoro Timer application built using Python's Tkinter library. 
The Pomodoro Technique is a time management method that uses a timer to break work into intervals, traditionally 25 minutes in length, separated by short breaks.

### Features

<strong>Work Sessions<strong>: 25 minutes of focused work.
Short Breaks: 5 minutes to rest.
Long Breaks: 20 minutes after every 4 work sessions.
Visual Timer: Displays the time left in the current session.
Session Tracking: Shows check marks for completed work sessions.

### Installation

Clone the repository:

git clone https://github.com/your-username/pomodoro-timer.git
cd pomodoro-timer

Install dependencies:
Ensure you have Python installed. You can download it from here.

Install Tkinter if it is not already installed:

pip install tk

Add the image:
Place a tomato.png image in the same directory as the script. You can download one from the internet or use any 200x224 pixels image.

Usage
Run the pomodoro.py script:

`python pomodoro.py`

How to Use

Start the Timer: Click the start button to begin the first work session.
Reset the Timer: Click the reset button to stop the timer and reset all settings.
View Progress: After each work session, a check mark will appear at the bottom to track your progress.

Constants
PINK, RED, GREEN, YELLOW: Color constants for UI elements.
FONT_NAME: Font used for text in the UI.
WORK_MIN, SHORT_BREAK_MIN, LONG_BREAK_MIN: Duration of work, short break, and long break in minutes.

Timer Reset
The reset_timer function stops the current timer, resets the timer text to "00:00", resets the timer label to "Timer", and clears the check marks.

Timer Mechanism
The start_timer function increases the repetition count and starts the appropriate timer based on the current repetition count.

Countdown Mechanism
The count_down function handles the countdown of the timer, updating the UI every second, and switches to the next session when the countdown reaches zero.

UI Setup
The UI is set up using Tkinter widgets.
A Canvas widget is used to display the timer and an image.
Label widgets display the timer label and check marks.
Button widgets start and reset the timer.

### Contributing

Fork the repository.
Create your feature branch (git checkout -b feature/feature-name).
Commit your changes (git commit -m 'Add some feature').
Push to the branch (git push origin feature/feature-name).
Open a pull request.
License
This project is licensed under the MIT License. See the LICENSE file for details.

Feel free to customize this README file according to your needs. Happy coding!
