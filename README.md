# Pomodoro Timer – Tkinter Desktop App

A simple productivity timer application based on the Pomodoro technique.
It cycles through Work Sessions, Short Breaks, and a Long Break, showing progress visually and playing audio alerts using pygame.

### Features

Pomodoro timing system:

* 25-minute work sessions
* 5-minute short breaks
* 35-minute long break
* Automatic cycle progression
* Audio alerts using pygame
* Completion checkmarks displayed below timer
* Reset button to restart cycle

Timer runs continuously — when one period finishes, the next starts automatically.

### Requirements

Python 3.8+ recommended

Install dependencies:

`pip install -r requirements.txt`


### Assets Required (Files That Must Exist)

Place these files in the same directory as the script:
* tomato.png
* tomato.ico
* alert.mp3

### Running the Application

From terminal or inside PyCharm:
`python main.py`