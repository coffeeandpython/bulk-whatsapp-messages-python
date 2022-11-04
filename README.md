# Send Bulk WhatsApp Messages using Python

I was playing around with [PyWhatKit](https://github.com/Ankit404butfound/PyWhatKit) to send bulk WhatsApp texts but I found that it was not designed to do that. PyWhatKit is a great library to send multiple WhatsApp messages to the same person, schedule texts, etc. but it didn't work for sending bulk WhatsApp messages. This is where [pyautogui](https://github.com/asweigart/pyautogui) came to help. With the help of [openpyxl](https://github.com/theorchard/openpyxl) to read the contacts from an Excel spreadsheet, I am using PyWhatKit and pyautogui to send 'personalized' texts to all of them via WhatsApp.

To use this program, import your contacts' information to the 'contacts.xlsx' spreadsheet and then run the program. Remember to include the ISD code with the phone numbers without the '+' signs. Also remember that you need to be logged-in to WhatsApp web on your default browser.

P.S. I love coffee more than I love Python. If you found my code useful, please consider buying me a coffee by clicking on the button below. 


<a href="https://www.buymeacoffee.com/coffeeandpython" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/default-orange.png" alt="Buy Me A Coffee" height="41" width="174"></a>