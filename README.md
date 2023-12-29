# ICM-Calc
ICM monte carlo simulation for poker tournaments

This program estimates the ICM value of a chip stack for any poker tournament using a monte carlo simulation. 
You can run the program on up to 2000 players, but it will become computationally intensive for a 
personal computer to run for any number of players over ~500. 
This program is written in Python 3

--------------INSTALLATION-----------------
1. Download and install Microsoft Excel
2. Download and install Python 3 https://www.python.org/downloads/
   See this video for instructions https://www.youtube.com/watch?v=yivyNCtVVDk
3. Download all files from this repo and store them in a folder on your hard drive (ICM Calc.py, TournamentData.xlsx,
   updatedTournamentData.xlsx, README.md)
4. Open IDLE (program that lets you run Python programs), and open ICM Calc.py.
5. Click Run


-------------RUNNING THE SCRIPT--------------
1. Open TournamentData.xlsx and input stack sizes in Column B and Payouts in Column D.
2. Check # trials at the top of Column C, set it to an appropriate number (more players = lower # trials, to save compute time)
3. Save the file and close it. 
4. Run the script, wait for the calculation to finish (can take up to 30 minutes for 500 players)
5. Open updatedTournamentData.xlsx to view results. ICM value should be populated in Column C

















*****************************************************************************************************************
The code for the monte carlo ICM simulation was first written by twoplustwo user 'halftilt' and can be found in 
the link below. This is the same estimation method used by the freely available calculator online. 

https://forumserver.twoplustwo.com/15/poker-theory-amp-gto/new-algorithm-calculate-icm-large-tournaments-1098489/
