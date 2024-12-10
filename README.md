# Python Alarm Clock

## Description
This Python script functions as a simple alarm clock. 
It allows users to set an alarm for a specific time, and when that time is reached, it plays a sound to alert the user. 
This project demonstrates the use of the datetime module to handle time comparisons and the time module to manage delays.

## Requirements
- Python 3.x
- playsound library (for playing sound)

You can install the required library using pip. Use the line of code below to install playsound library in the terminal:

pip install playsound


## How to Use
1. Clone the repository to your local machine:

""""""""""""""""""
   git clone https://github.com/kayyy01/GO2COD_PY_03.git
   cd GO2COD_PY_03
   
"""""""""""""""""""   
   

2. Open the script file (clock.py) in your preferred text editor or IDE.

3. Set the desired alarm time in the format HH:MM:SS (24-hour format).

4. Run the Python script:

   """"""""
   python alarm_clock.py

   """"""""

5. The script will check the current time and play a sound when the alarm time is reached.

## Code Explanation
- **Imports**: The script imports the datetime and time modules to handle time functionalities and manage delays.
- **Setting the Alarm**: Users can define the alarm time, which is compared against the current time.
- **Time Checking**: The script uses time.sleep() to pause between checks, avoiding constant resource usage.
- **Sound Playback**: When the alarm time is reached, the script plays a sound using the playsound library.

## Sound File
Make sure to have a sound file (e.g., clock.mp3) in the same directory as the script, or specify the path to your sound file in the script.

## Contributions
Feel free to fork this repository and make improvements! If you encounter any issues or have suggestions, please open an issue in the repository.


