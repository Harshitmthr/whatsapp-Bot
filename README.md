# Send bulk messages from the Excel

It is a python script that sends bulk WhatsApp message from a excel file.


## Prerequisites

In order to run the python script, your system must have the following programs/packages installed and the contact number should be saved in your phone (You can use bulk contact number saving procedure of email). You can only send text messages through it.
* Python 3.8: Download it from https://www.python.org/downloads
* Chrome v79: Download it from https://chrome.google.com
* Pandas : Run in command prompt **pip install pandas**
* Xlrd : Run in command prompt **pip install xlrd**
* Selenium: Run in command prompt **pip install selenium** 
* Web Driver: Run in command prompt **pip install webdriver_manager**

## Approach
* First need to clone this respiratory
* Run python script script.py using py script.py in the terminal
* The script opens WhatsApp web using chrome.
* User needs to scan QR code from his/her phone.
* Enter in command prompt to execute further.
* The script hit url with contact number and message from excel sheet.
* Once all the message will be sent chrome driver will automatically closed.



Note: The script may not work in case if the HTML of web WhatsApp is changed. If you face any problem please do let me know.
