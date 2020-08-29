# **Google Meet Automation**
An Automation script to automatically join a scheduled google-meet meeting at a specific time without manual labour. This one's for all the lazy people like me who don't like waking up early morning for online classes.



#### Requirements
1. Python 3.5 and above
> To install Python ([click here](https://www.python.org/downloads/))
2. python pyautogui, webbrowser, time, datetime packages
```python
pip install pyautogui
```
```python
pip install webbrowser
```
```python
pip install time
```
```python
pip install datetime
```
3. Any Web Browser (preferably Google Chrome)


#### Install Packages
- To [Download Python](https://www.python.org/downloads/)
- `pip install pyautogui`
- `pip install schedule`
- To [Download Zoom Software](https://zoom.us/download#client_4meeting)

#### How to run the program ?
- At first, clone the repository.
- Now locate *automeet.py* and open it using any text editors like Sublime Text / Brackets / Notepad ++ or IDEs like PyCharm (here I have used PyCharm).
- You need to make 3 major changes in order to personalise the script, the changes are as follows ..
- Go to line 10 `if now.strftime("%H%M") == "time":` and replace *time* with your Meeting Start Time.
- Go to line no 12 `webbrowser.get("path").open_new("link")` and replace *path* with the Google Chrome Browser's path in your pc and *link* with your Google-Meet Meeting Link.
- If you are using IDEs like PyCharm then run the program there itself, else follow the following steps.
- After doing so, open up command prompt in the same folder 
	HELP : go to the address bar and type in **cmd***(lowercase)* and press enter, command prompt oppens up in the same folder
- Now, type `python automeet.py` and press enter.