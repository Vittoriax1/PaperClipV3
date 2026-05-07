# PaperClipV3
This is the 3rd iteration of the Python script to monitor the contents of a user's clipboard.

In this iteration, I've added the functionality for the user to be able to clear the contents of the clipboard. This also clears the contents of the GUI. The data that was captured and saved to the log file remains intact.

To make this script executable, ensure that PyInstaller is installed in the Python environment. Then, run the following command:

pyinstaller --noconsole --onefile PaperClip3.py

This command will create a single executable file and will hide the console window. If you need the console window for debugging purposes, remove the "--noconsole" portion of the command. 
