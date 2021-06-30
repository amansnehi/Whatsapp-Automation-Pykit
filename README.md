# Whatsapp-Automation-Pykit
Whatsapp Automation Pykit can automate whatsapp web and can perform different task like Sending a message to a bunch of contacts and groups just by a simple click and many more .
# Some basic libries used in this project
- ### selenium [refer](https://pypi.org/project/selenium/)
- ### time [built-in] 
- ### os [built-in]
- ### openpyxl [refer](https://pypi.org/project/openpyxl/)
- ### re [built-in]
# Follow this steps
- ### Use cmd --> pip install selenium to install selenium https://pypi.org/project/selenium/
- ### Install openpyxl {for using excel files}
- ### Copy Whatsapp Automation pykit file in your system 
- ### run main.py file from cmd promt/powershell
# Available commands
-  ### send_message(), bulk_message(), forward_message(Enter Contact name), links_share()
## send_message()
send_message() command is capable of sending a one liner text to multiple people.
### Important points
- **contacts name** should be seperated with ",".contacts name are case sensitive
![](https://github.com/amansnehi/Whatsapp-Automation-Pykit/blob/main/Images/send_message.PNG)  

## bulk_message()
bulk_message() cmd is capable of sendings a multiline message to multiple contacts and groups just using a single line of code.

### Important points
- Enter the contacts names and groups names in the first column in the groups Excel file and save it
- Enter the message you desire to send in text_message.txt file and save it
**case sensitive**
![](https://github.com/amansnehi/Whatsapp-Automation-Pykit/blob/main/Images/bulk_messages.PNG) 

## forward_message(...)
As there is a limit of five for forwarding messages in whatsapp. Now its over by jusing just a single line of command one can forward as many contacts and groups they want.

### Important points
- save the contacts and groups name in the first column of contacts Excel file and save it.
- **cons** --> The message should be a forwardable message and the target contact should have only one forwardable message in chat list.
### Parameter
- Enter the contact name from where the message is to be forwarded{taget_contact} **case sensitive**




