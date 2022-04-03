# About Me
As I have the programmer job, I know a lot about it.
#
I am also developer. I make games and batch files, also some programs.
#
I work at Roblox. My username is GamerLighting23233.
#
For now, I will only do basics for batch files on this site.
#
Later, I will add scripting and building in Roblox.
#
# Basics | Batch File Coding
So first of all, we're going to start with basic functions in batch file.
FUNCTIONS
- ECHO
- set
- PAUSE
- timeout
ECHO will print out messages. I recommend using @ECHO OFF on first line.
This will disable the directory where the file is saved when the commands execute.
Example:
`@ECHO OFF
ECHO Hello world!`
================================================================================
The variants of set are set /p and set /a.
set /p will prompt user to write answer. This is useable for quiz or anything similar to this.
Example:
`@ECHO OFF
set /p amount="Type amount: "`
If you want to make this to print out answer, do the following:
`@ECHO OFF
set /p amount="Type amount: "
ECHO The amount is %amount%`
set /a will set a numerical expression from a string.
It's hard to tell about it and examples.
================================================================================
PAUSE is a simple command, allowing you to pause the batch file until the user presses any key on keyboard.
Example:
`@ECHO OFF
ECHO Hello world!
PAUSE`
Output:
`Hello world!
Press any key to continue . . .`
If you want it to not print `Press any key to continue` then simply type `PAUSE > nil`
nil will remove the message from any commands, like timeout.
================================================================================
And last, the timeout command.
timeout allows you to pause the batch file for the set amount of time. It will allow the user to skip this.
Example:
`@ECHO OFF
ECHO Hello world!
timeout 2`
To disable skipping and the message, do the following:
`@ECHO OFF
ECHO Hello world!
timeout /T 2 /NOBREAK > nul`
And that's it! I will upload more later.
