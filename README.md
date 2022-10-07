# Barco
#This is a web UI automation validation work. The URL is https://www.barco.com/en/clickshare/support/warranty-info
#Before validation, Please click “Accept all cookies” while you opening the page.
#I randomly run 10 times with the different scenario automatically.
#Step1: I desgined some type of serial number to insert the textbox. The program will randomly choose one from the pool ('1863552437', '123', '186355243a', '!@#4', '0021!','186355243!','1863552417' ).
#Step2: click get info button
#Step3: check the corresponding message. I list three type of the message as below. Case: insert “1863552437”, check device info.
#one special case: if you get correct length of serial number, but not equal to 1863552473. The verification result will be” sorry! you get correct length of serial number, but i only have 1863552437 device info to do validation.”
