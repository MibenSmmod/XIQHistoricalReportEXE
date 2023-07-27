# XIQHistoricalreportEXE

This is a compiled version of the Python script HistoricalClient_CsvToExcel.py: https://github.com/ExtremeNetworksSA/XIQ_Client_Report_CSV

# Running an EXE to make this process more simple
### Option 1
Download the EXE to your Windows machine and put the CSV file in the same folder and follow the prompts

### Option 2
Run the EXE on a Mac utilizing an application called CrossOver ($): https://www.codeweavers.com/crossover
1) Download the EXE to your downloads folder
2) Open CrossOver app
3) Press:  Install - bottom left corner
4) Click "Install an unlisted application" since this is not a native supported EXE we're trying to run
5) Press Edit: "You will need to provide the installer file or disk in order to install this software using CrossOver"
    - Browse and select:  XIQHistoricalReport.exe
    - Press: Choose Installer
6) Press Edit:  "You will need to select the bottle to install this software into"
    - This will be in a New Bottle...
    - New Bottle Name:  XIQ Client Report
    - Choose New Bottle Type:  Windows 10 64-bit
    - Press:  DONE
7) Press:  Install

An application window will popup and run the script...

8) Press X to close the application window and CrossOver will complete the install
9) Your new XIQ Client Report bottle is listed on the left column; it should be selected
10) Press:  Open C: Drive
11) Copy your EXE into the root of the C: drive of your bottle
12) Rename the file to XIQ.exe for simplicity
13) Copy your XIQ Report into the root of the C: drive and rename to XIQ.csv

Both the EXE and CVS should be in the root of the C: drive in your XIQ Client Report Bottle

14) Go back to CrossOver app > press:  Run Command
15) Type:  c:\XIQ.exe
16) Press:  Save Command as a Launcher
17) Press X to close Run Command window
18) Double left click XIQ icon to launch script
Prompts:
- Please enter Location name:  My Library
- Please enter the name of the Statistics Summary file:  XIQ.csv  <- This file can't be touched by Excel or it will error
- Window should close after it completes
19) Go back to the drive_c Finder window and find your XIQ.xlsx

Copy that file out of the bottle and you're complete
