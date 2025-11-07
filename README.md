# Pomodoroman
Hello! Pomodoroman is a mini Pomodoro timer web application. I wanted to make something I would use, and this is the improved version for everyone.
Features: 
  * Timer modes: Choose between 25min work/5min break, 50/10 or 90/30.
  * Companion widgets that add a little life to your work sessions by talking to you (or scolding you!)
  * (Don't try to find all their dialogue bubbles, it will take too long)
  * Music/Ambient sound choice: "Eldrum: Ryke Valley", "Waves", "Library" and "Medieval"!

# How to use:
1) Download the zip file
2) EXTRACT the files to a folder
3) Run "RUN.bat"

Switch the widget character by clicking the tiny white button next to the widget.
   ## Note: If you run Pomodoroman.html directly from the zip file, the background and other stuff will not load, and you will be sad :(




### What is the .bat file for?
For the audio files to play. The audio is played from YouTube via IFrame API, which requires the current page to have a valid origin (local files have origin null).
Running the .bat file will create a local server.
# (*) You can also use "RUN.bat" as a shortcut for the timer! Just make sure it's in the same directory as the folder.
Eg: Desktop
    ├─ Projects                             // general folder
    │   └─ Pomodoroman 
            └─ Pomodoroman.html
    └─ RUN.bat                             //on desktop

