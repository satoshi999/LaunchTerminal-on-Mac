# LaunchTerminal on Mac
====

## Overview
The Apple Script for launching "Terminal" at current Folder.

## Description
This is the Apple Script that can launch "Terminal" at current Folder.  
You can launch "Terminal" on current folder by calling this script using short cut key When you are opening "Finder" at forefront.  
Case of execute this when you aren't opening "Finder" at forefront, it will launch "Terminal" as default.



* Note  
Source code is written in "main.txt"(is not scpt file) .  
Because scpt can not open on this page.

## SetUp
1.Launch "Automator" app.
2.Choose "Service".
3.Choose "no input" in select box of "service receives selected".
4.Set "Run AppleScript" from left side.
5.Back to this github page and copy source code in the script.
6.Back to "Automator" again, then paste the code into panel of "Run AppleScript".
7.Save as new worlflow.
8.Open setting page of "Short cut" in "System Preferences".
9.Select "Services" and find service as saved workflow from before.
10.Set any short cut key you want to launch.

## Usage
Open Finder. Press the short cut key, Then You will see that "Terminal" will be launched at current folder.  
Case of when you aren't opening "Finder" at forefront, it will launch "Terminal" as default.

## Licence

MIT Licence

## Author

[yorudazzz](https://github.com/yorudazzz)