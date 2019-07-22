# Py-Exe_Converter_Batch
Simple command to launch py-to-exe via Command Line. Must have py-to-exe installed via PIP prior to Batch use

Website Reference: https://bit.ly/2Xo4kQg

Auto PY to EXE is an amazing application for making .exe file out of your project 
  whether it is one .py file or any number of them.
  
Step 1. Installation

YOUTUBE: https://bit.ly/2Od3wcE
Installing using PyPI:

#1 To install the application run this line in cmd:
#2 pip install auto-py-to-exe
#3T o open the application run this line in cmd:
  auto-py-to-exe

Note: if you have problem installing this way or 
  you want to install it from GitHub go to the main page or 
  watch this instructional video by the developer of "Auto PY to EXE" himself.
  
  Step 2. Converting
There are few main options you need to choose:

#1 Pick your .py file
#2 Pick "One Directory" or "One File" option
#3 Pick additional files

2.1. "One Directory" option
alt text

Pretty simple. When choosing "One Directory" option "Auto PY to EXE" will put all 
  dependencies in one folder. You can choose Output directory in "Advanced" menu. 
  If you have media files like icons and backgrounds you should't have any problems using them inside your .exe 
  if you place media files/folders in Output directory.
  
  2.2. "One File" option
alt text

When choosing "One File" option "Auto PY to EXE" will create one .exe file 
containing all dependencies but NOT MEDIA FILES. 
If your program has only default Windows gui with no icons, backgrounds, media files or you are OK with 
placing media folder with .exe file feel free to skip the 
following explanation. For those who want to pack media files into .exe file itself read paragraph 3.


3. Pick additional files
There is a menu in "Auto PY to EXE" called "Additional Files" that lets you add files of your choice. 
There is a catch though. "Auto PY to EXE" uses pyinstaller which unpacks the data into a temporary folder, 
and stores this directory path in the _MEIPASS environment variable. 
Your project won't find necessary files because the path changed and it won't see the new path eather. 
In other words, if option "One File" is choosen picked files in the "Additional Files" menu will not be added to .exe file. 
To work around this you should use this code provided by Max in stackoverflow question

TO BE CONTINUED. You can go to the website linked above for the full documentationl












