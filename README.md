# IIT Week 1

Print "Hello!", then print a word backwards — in three languages:
Python,javascript,gcc

## Sum
C needed the most setup: when I first ran hello.c, it failed with "printf is not defined", because I had left out the first two lines, #include <stdio.h> and #include <string.h>. On top of that, the source has to be compiled into an executable with gcc before it will run at all. That is the difference between compiled and interpreted languages — Python and JavaScript need neither headers nor a compile step, because their interpreter runs the source directly.


## Write following codes to run it. 

```powershell
python hello.py

node hello.js

gcc hello.c -o hello.exe
.\hello.exe

