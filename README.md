# Reddi
A bot that searches Reddit API and exports stories as audio files. ((The audio files are a bit slow and I would like to change the voice but am not sure how yet.))



How To Work:

1. FIRST, Make sure you have the latest version of python installed on your machine. You can find the download here: https://www.python.org/downloads/

2. Download the file "Reddit_Bot_Main"

3. Go into the file using VS or notepad and edit the <Directory> on the line 37   directory = "C:/Users/<Username>/Documents/Reddit_Files"    Replace <username> with the username connected to or used to login to your computer.

4. Save the file to your desktop in a new folder named Reddit_Files. MAKE SURE THERE ARE NO TYPOS!  MAKE SURE YOU SAVE THE FILE AS A PYTHON SCRIPT BY CHANGING .TXT TO A .py

5. Double click on the file to run your code and just wait while audio files are exported to the foler.
      a. If that dosent work you may have to run the file directly from the terminal, Open Your terminal and navigate to the directory the file           is located in, then type, python Reddit_Bot_main.py    and your code should run 
      b. You will be prompted to enter your search query into the terminal, Type in the words or phrases you want your stories to be about, like "AITAH", or "Storytime"
      
      Sit back and relax while your files generate to the folder the file was located in 
     
Possible Errors: 
      
      You may get errors such as directories dont exist or errors about your praw, If youve used other projects like this before you should have this installed already but if you dont you will have to install the required dependancies 
      To do this, type into your terminal the following:
      
     "pip install praw"
     "pip install gtts"
     "pip install moviepy.editor"
      
      Make sure to leave out the quotations of course!
      
      This should fix any possible errors with your code
