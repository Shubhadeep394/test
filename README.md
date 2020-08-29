# **Google Meet Automation**
An Automation script to automatically join a scheduled google-meet meeting at a specific time without manual labour. This one's for all the lazy people like me who don't like waking up early morning for online classes.

## Requirements 
- [x] Installed python version above 3.5
- [x] Installed pyautogui package
- [x] Installed schedule package
- [x] Updated Zoom Software (Signed in)

#### To install the above packages :
+ To [Download Python](https://www.python.org/downloads/)
+ `pip install pyautogui`
+ `pip install schedule`
+ To [Download Zoom Software](https://zoom.us/download#client_4meeting)

##### How to run the program ?
 Clone this repository and unzip it
* Open the run.bat and set the paths
  * First Path - "Path to where python is located"
  * Second Path - "Path to where the main.py is located"
* Make sure the `joinING.png` is located in the same folder as `main.py` and `run.bat`
* Run the `run.bat` to run the batch file
  * Alternatively you can also run the `main.py` for the same result but `run.bat` is preferred
* *Finally after the cmd is opened read the instructions thoroughly and proceed by entering your zoom meeting info*
* *Make sure you enter the "Meeting ID and Meeting Password" correctly or else the program would crash*
* Format for the Recurring Meeting Time should be in 24 Hour format
  * Eg: `09:30` for 9:30am and `15:30` for 3:30pm 
* Total Meeting time is entered in `minutes` format
  *Eg: `20` for 20mins