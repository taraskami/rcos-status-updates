## Last Week's Accomplishments

A very good two weeks, actually. I decided to set up an Ubuntu virtual machine on my computer, and it wasn't too taxing. I think I can work in that environment. Furthermore, installing everything necessary worked well (as it should!!). I pulled the newest version of AGENCY onto the machine and it came with a cleaner set of instructions and installation scripts, which I think set up AGENCY correctly. An interesting thing to point out, when I was trying to get this to work on Windows, I had the AGENCY code sitting in my OneDrive folder and have xampp point to that as the document root. However, I assume there is code in AGENCY that expected it to be sitting in "var/www/html", which seems to really exist in Linux and is accessed by Apache there. I could go through the code and repoint to that, but why? In the new VM, I did exactly as I should, git cloning into var/www/html and running the apache server there. And, it works! kind of. I get a new error message that I don't have certain PHP things installed to work with Postgres. But I contacted Ken about it and he provided me with a few more packages I need to install. So, I am very close.

## This Week's Plan
Installing those packages and getting AGENCY up is a fairly small task from this view, but I will be most likely busy this week due to HackRPI. So, that's my goal, and if I can tack in some documentation and notes on my repo's wiki, I'll be happy. I'll also need to communicate my success to the rest of the team so that they can replicate this.

## Anything Blocking?
Just the problem above that I am missing some packages, but I know which ones to install and I'll get to it soon.

## Notes

> This is an optional section for any sort of information that does not fall under any of the other categories.
