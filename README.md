# AutoWisher
Developed and implemented a system to automatically send birthday wishes to contacts on WhatsApp using Python and the PyAutoGUI.   Designed a user-friendly interface to input contacts and personalized birthday messages that would deliver the message at a particular time. 

AUTO WISHER is a Python-based automation project that automatically sends birthday or special occasion wishes to your friends and family via WhatsApp. This application helps users avoid forgetting important dates and ensures timely wishes without manual effort.
**Abstract**
In today’s busy lifestyle, remembering special occasions like birthdays and anniversaries can be difficult. AUTO WISHER solves this problem by automating the process of sending wishes. The user provides details such as name, date (DDMM format), message, and contact number. The system checks the current date and sends the predefined message automatically via WhatsApp.
**Features**
✅ Automated WhatsApp message sending
✅ Date-based wish detection
✅ CSV-based data storage
✅ Simple GUI built with Tkinter
✅ Minimal human intervention
✅ Time-saving and efficient
🛠️ Technologies Used
**Programming Language**: Python 3.10
**Libraries:**
csv,tkinter,pyautogui,datetime,schedule,time
**IDE:** Any Python IDE (Recommended: PyCharm)
**Operating System:** Windows OS
**Application Required:** WhatsApp Desktop App

 
 
**How It Works**
User enters:
1.Name
2.DOB (in DDMM format)
3.Message (e.g., Happy Birthday)
4.Contact Number (must be saved in phone/WhatsApp)
The data is appended to a CSV file.
The program checks if today's date matches any date in the CSV file.
If a match is found: Opens WhatsApp Desktop, Searches for the corresponding contact,Types the predefined message,Sends the message automatically,Displays: "Successfully Sent the Message".If no match is found,Displays: "Match Not Found".
Program terminates
