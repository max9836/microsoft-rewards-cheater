# Microsoft reward cheater
This powerShell script (Microsoft-reward-cheater.ps1) automates Bing searches with random queries to potentially earn Microsoft Rewards points. It features:

* Random query generation for search variety.
* Keystroke simulation to perform searches automatically.
* Optional logging of search activity.
* User input for number of searches, browser loading time, and optional log file path.

> [!WARNING]
> **DO NOT USE OTHER APPLICATION WHILE THIS SCRIPT IS RUNNING.** <br>
> This script uses keyboard typing to avoid getting noticed by the browser, using other application while this script will warning will cause the text typed in the wrong place, and finally cause a big mess.

# Introduction:
This PowerShell script automates Bing searches with random queries to potentially earn Microsoft Rewards points. It includes optional logging to track progress.

## Key Features:
* Generates random search queries for diversity.
* Simulates keystrokes to perform searches automatically.
* Allows optional logging of search activity.

# Requirements & Usages:

1. Edge Browser: The script launches Microsoft Edge to perform searches that can earn Microsoft Reward points.
2. Windows and Mac operation system: This PowerShell script can only be executed in a Windows PowerShell terminal or on a Mac using a terminal emulator.

# Useage:

## Syntax
```
Run -Searches [Number of searches] -Path [Log file path] -Browser_Load_time [Load time in seconds] -Random_length [Random query length]
```
* Searches (Mandatory): Number of Bing searches to perform (range: 1-100).
* Path (Optional): Path to save the log file. If not provided, you'll be prompted for input.
* Browser_Load_time (Mandatory): Time in seconds to wait for the browser to load (default: 3).
* Random_length (Optional): Length of random search queries (range: 1-100). If not provided, a random value between 1-100 will be used.
## How to run it in Powershell
Step 1: 
  Open PowerShell with administrator privileges.<br>
  1.  Right-click the Windows icon on the taskbar.<br>
  2.  Click "Windows Terminal (Admin)."

Step 2:
Paste this code in the command line.<br>
This code will bypass the execution policy from windows powershell.

```
set-executionpolicy -executionpolicy bybass
```
Step 3:
Then, run this command:

```
powershell -command "& { . <path>\Microsoft-Reward-cheater.ps1; Run}"
```
#*You'll need to replace ```<path>``` with the actual path to your file.*<br>
Step 4:
Set the execution policy back to restricted, so your computer will not be hacked.
```
set-executionpolicy -executionpolicy restricted
```

<!--```--->
