INTRODUCTION 
The ID Card Generator this is a python-based project mainly intended for generating ID cards during events conducted 
in the college Pimpri Chinchwad College. This project reduces the manual effort in creating ID cards for attendees, 
managing attendee data and distributing of very large number of IDs. In 3rd semester project, we developed this to 
automate event management and easy ID card generation of students. 
OBJECTIVE 
The overall Vision of this project is just to make a system that saves our time collects information, generates an ID card 
and then directly give it the student. Moreover, the software saves all user information in an Excel sheet for further 
references to event and crowd management. 
PROJECT FEATURES 
DATA ENTRY INTERFACE 
The application provides a simple, user-friendly interface where event organizers can input essential details of the 
participants : 
• Name of the Student 
• Enrollment Number 
• Phone Number 
• Email Address 
• Course 
• Event Name 
These fields allow for quick entry and management of participants' details. 
ID CARD GENERATION 
After the participant's data is entered, the application automatically generates a professional ID card. The ID card 
includes : 
• Name of the Student 
• Enrollment Number 
• Phone Number 
• Email Address 
• Course 
• Event Name 
• Logo of the University
• Unique QR code
• Unique ID Number
This ID card is formatted for print and distribution, ensuring that all essential information is clearly visible. 
AUTOMATED EMAIL GENERATION 
Once the ID card is generated, the system automatically emails the ID card to the student using the email address 
provided during data entry. This feature ensures that participants receive their ID cards instantly and conveniently. 
EXCEL DATA STORAGE 
The system stores all participant entries in an Excel file, capturing all details provided for each student. The file keeps 
records of : 
• Student Name
• Enrollment Number
• Phone Number
• Email Address
• Event Name
• Date and Time of Entry 
This Excel file serves as a comprehensive record for event organizers to track participants and manage data efficiently. 
TECHNOLOGIES USED 
• Python: The core programming language used for logic and functionality. 
• Tkinter: For designing the graphical user interface. 
• Pandas: To handle the storage of participant data in Excel format. 
• OpenPyXL or XlsxWriter: To manage Excel file creation. 
• Smtplib: For sending automated emails with the ID card attachment. 
• PIL (Python Imaging Library): To generate and manipulate images for ID card creation. 
WORKING MECHANISM 
1. Input Stage: Event organizers enter the details of the student through the GUI. 
2. ID Card Generation: Based on the provided details, the software generates a custom ID card. 
3. Record Keeping: The entered data is saved in an Excel file, keeping track of all the participants for future 
reference. 
4. Emailing: The generated ID card is shared with the student via email automatically, streamlining the 
distribution process. 
ADVANTAGES 
• Efficiency: Automates the manual process of creating ID cards, reducing time and effort for event organizers. 
• Data Management: Organizers can easily manage and access participant data through the Excel records. 
• Convenience: Students receive their ID cards immediately through email without any delay. 
• Scalability: The system can handle data for large-scale events involving numerous participants. 
DISADVANTAGES
• Manual Data Entry: 
The system relies on manual input, which can introduce errors if incorrect data is entered. There's no 
automatic verification of details, such as student enrollment numbers or names.
• Dependency on Email System: 
The email sharing feature might depend on reliable internet connectivity and proper configuration of email 
servers. If the email system fails or is improperly set up, users may not receive their ID cards on time.
CONCLUSION 
The ID Card Generator project provides an automated way to create ID cards for better event management at Pimpri 
Chinchwad University and automates handling of the data. The user-friendly experience offers event organizers 
automatic ID card generation and real-time email delivery. Moreover, it comes with an Excel data storage functionality 
where the record of participants is stored which can be beneficial at any upcoming event. 
This project serves as an example of real-world Python and GUI development, with the ability to move data in a way 
that automates otherwise manual information management required at university events.
