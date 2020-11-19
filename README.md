# HTB-Box-Setup-Script

## What does the script do?
  * Creates a dir called \<machine-name\> or \<fortress-name\>
  * Creates a dir called nmap inside the dir
  * Creates and opens a new cherry-tree document for you to take notes
  * Opens a new tmux session for you

## What more do I want it to do?
  * I'm contemplating if I need to make a dir for gobuster/fuff/any-web-discovery-script because not all HTB machines use web
  * I actually don't know, I'll sleep on it maybe

# Usage
```
My Personal Script to help me create my initial setup for HTB Machines
Options:
 -h|--help Prints this help text and exits
 -b|--box To specify name of the machine you are going to attempt
 -f|--fort To specify name of the fortress you are going to attempt
 
 Usage:
 htb -b <box-name>
 htb -f <fort-name>
 OR
 htb --box <box-name>
 htb --fortress <fort-name>

```
