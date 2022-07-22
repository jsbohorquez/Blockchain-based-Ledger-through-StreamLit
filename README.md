# Challenge-18
Blockchain-based Ledger through StreamLit

## Overview
This program application [pychain.py] allows the user to create a block chain and ledger that can be verified. The app is coded for StreamLit and allows the user to input information pertaining to who is sending and who is receiving in a transaction and the value of the transaction. User may access information of different transactions saved within the ledger in the application. 

## Technologies Used
The libraries and dependencies used in this program are listed in the first cell of the program which are: streamlit, dataclasses, typing, datetime, pandas, and hashlib 

## Program Layout
This program is divided into the following parts:

**Part 1** - pychain.py code
            This file contains all functions and structure for the blockchain-based ledger as well as the structure of the streamlit application.
            Within it are functions which creates a record of transactions, adds the information to a block and ultimately binds information blocks together. In addition, blockchain update functions as well as structural code for streamlit are included within the file.
            
**Part 2** - Streamlit Application
            User will run the application using the pychain.py file. Once application is open, there will be 3 areas in which user will input transaction data (sender, receiver, and amount). User will then click 'add block' button and the transaction will be recorded in the PyChain ledger. On the left hand side there will be a 'Block Inspector' drop down menu which the user may use to navigate to previous transactions stored within the blockchain. 

            The following images show PyChain application running:

            

## To Run Web APP
-Download program packages, and files under 'starter_code' folder
-Access file through terminal, run command: streamlit run pychain.py 



## Author
Juan Bohorquez