# ZipForcer
> *Zip file bruteforcer*

A simple zip file password cracker to crack zip file passwords.

# How it works

The program attempts to unzip the zip file given with a password\
if the password is wrong it will fail and be caught by the except\
loop which passes and continues onto the next password, if a password\
succesfully unzips it it will stop the program and print the password.

# Installation

Run `pip install -r requirements.txt` to install nescessary libraries\
Then run python `python ZipForcer.py` to run the actual code.

You will need a password wordlist, a common one called `fasttrack.txt`\
is included here, this is a shortened version of the famous `rockyou.txt`\
which can be found here.\
https://github.com/brannondorsey/naive-hashcat/releases/download/data/rockyou.txt.
