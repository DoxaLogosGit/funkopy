# funkopy
Script I wrote to parse my Funkoverse play data from BGG.  It is quick and dirty and based off another script.

This script requires a specific format to the data stored in your boardgamegeek.com (BGG) plays.


Also, make sure you enter your username as one of the players even if you're playing solo and multiple
heroes.  The script is looking for the username.  


To run the script, make sure you have Python 3.7+, requests, and beautifulsoup4 installed on your system.

Edit the "USER" in funko_data.py to your BGG username.

Run from a bash shell with the following "./funko_data.py"
