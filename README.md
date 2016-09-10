# Change IMEI
Method 1. ( NON ROOT METHOD )Step 1. Turn you phone Off ( install adb drivers and first check if all drivers are working . )
Step 2. Search and Download the pakage ( team kustom's IMEI package . )
Step 3. Install the Meta software given in the package .
Step 4. Open it ( make sure to run it in admin mode - run as admin )
Step 5. Select IMEI download as shown in images below .
Step 6. go to options and select the second option ( shown in images )
Step 7. Click on reconnect and connect you phone via USB ( do not turn it on . keep your phone turned off )
If this doent work then please remove battery and connect and turn the phone on .
You will see a popup relating IMEI tool . Now select the first option ( download Flash file ) and browse the BPLGU file which is in the package 
Note : Other phone owner ( other than android one ) can search their BPLGU file in the ALL_MTK_BPLUG zip . This is special file for android one device . 
Step 8. Now write both SIM imei ( check your mobile box for it or behind the battery - Writing wrong imei is illeagal )
Step 9. Click on second Option ( update flash file ) and close the imei tool.
Step 10. click on disconnect and turn your phone on . WTF you are on network back :P  

Method 2. ( ROOTED METHOD ) - this wont work for our device and for many device it works .Step 1. Install Uncle mobile tool
Step 2. Open and give this app root access
Step 4. Go to engineer mode
step 5. Go to mtk engineer
Step 6. Or to directly go to engineer mode try this ( note it wont work for all device so use uncle moble application )
Open the Dialer and type *#*#3646633#*#* you will enter the MTK Engineering Mode or using Mobile Uncle APP Hit the Engineer Mode option and choose the Engineer Mode (MTK).
On EngineerMode Chosee Connectivity and click the CDS information option.
You will see Radio information there and after tapping on it. If you have dual SIM ANDROID then you will see TWO option select any one on which you want to write IMEI with.
Click Phone 1
At “AT+” line add : AT+EGMR = 1,7,”my_first_IMEI_code”
Click on “SEND AT” button below
For second SIM tap Phone 2 and type this command
AT+EGMR=1,10,”my_second_IMEI_code”
Click on “SEND AT COMMAND” button below a second time
Reboot phone

*#*#3646633#*#*
Rooted Phone.
in terminal: getprop net.hostname  and then setprop net.hostname CBI-GOV ( change hostname )
