# ConsoleKeyboardStroker
This repo includes python code to stroke keys for virtual machines consoles (useful for entering long passwords) such as Ovirt, Rhev , Nutanix, and Vmware
# How to use
1- Clone the project to your own directory <br />
2- run the following command <br />
   python ./keyboard.py YourPassword <br />
Note: I your password include " character then you need to pass \ before the character for instance, 12345"54321 must be be 12345\\"54321
3- you need to hover to your VM console screen within two seconds then the password will be entered.

