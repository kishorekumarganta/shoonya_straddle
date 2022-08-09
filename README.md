# shoonya_straddle

'''
NOTE: 
I am not responsible for the profit or loss you make it stock market. 
Use this script at your own risk.
'''

*****
check If you have all the packages installed.

# This repository contains the sample code for running straddle with Finvasia shoonya Api

*****
I am using a method where once the Login fucntion is called , we can store the token and use it to start another session.
By default method we can not run two or more files simultaneously.

The sell orders will be market orders
The Buy orders will be SL-LMT orders

*****
'''


How to Use:

1.Download the repository, change the details in the config.py file

2.Login.py is used to generate and store the token.

3.straddle.py file is the file you need to run the straddle strategy

4.Options Expiry is calculated automatically, But please cross check

5.This is just an example , do change as per your requirements

6.There might be slippages while doing it live

'''


First Run Login.py

it will create shoonyakey.txt directly


change time in stradle.py file to check on offtime.
