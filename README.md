# **Google Meet Automation**
An Automation script to automatically join a scheduled google-meet meeting at a specific time without manual labour. This one's for all the lazy people like me who don't like waking up early morning for online classes.

>**NB** : The automation script is made according to my intrests and needs, in order to satisfy your reqirements you mignt need to make changes to the code. To help you with the same I have attached few links in the References section of the README.md.


### Install the Required Softwares and Packages
1. Python 3.5 and above
> To install Python ([click here](https://www.python.org/downloads/))
2. Python pyautogui, webbrowser, time, datetime packages
```python
pip install pyautogui

pip install webbrowser

pip install time

pip install datetime
```
3. Any Web Browser (preferably Google Chrome)


### How to run the program ?
- At first, clone the repository.
- Now locate **automeet.py** and open it using any text editors like Sublime Text / Brackets / Notepad ++ or IDEs like PyCharm (here I have used PyCharm).
- You need to make 3 major changes in order to personalise the script, the changes are as follows ..
- Go to line 10 `if now.strftime("%H%M") == "time":` and replace **time** with your Meeting Start Time.
- Go to line no 12 `webbrowser.get("path").open_new("link")` and replace **path** with the Google Chrome Browser's path in your pc and **link** with your Google-Meet Meeting Link.
- If you are using IDEs like PyCharm then run the program there itself, else follow the following steps.
- After doing so, open up command prompt in the same folder 
	HELP : go to the address bar and type in **cmd** and press enter, command prompt oppens up in the same folder
- Now, type `python automeet.py` and press enter.

### References
> 1. https://pypi.org/project/PyAutoGUI/
> 2. https://pyautogui.readthedocs.io/en/latest/
> 3. https://pyautogui.readthedocs.io/en/latest/keyboard.html#keyboard-keys

Loved the work ? [Support Me](https://paypal.me/shubhadeepmandal394?locale.x=en_GB) for my next project 😇