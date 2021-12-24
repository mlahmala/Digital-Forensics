# Digital-Forensics

CASE REPORT   NATIONAL GALLERY DC

Scenario:
Just as in a real-world scenario, you will complete a final report to present your findings. You will work with your team to fill out the report.

The final report should be submitted as the homework deliverable for this week. Everything your group has completed in class should be included. What you do not finish today can be continued at home.

Use the Final Case Report Google Doc template to complete your report. Make a copy and be sure that each student has editing access. This will allow everyone in the group to access and work on the document at the same time.

Each group will turn in one completed report to be graded.

Use the following resource to help guide your work:

iPhone Forensics - Important Files and Databases
Lab Environnement
This homework will use the Digital Forensics - Autopsy lab in Kali Linux.

You will find the tracy-phone-2012-07-15.final.E01 file located in the /corpus directory in Autopsy.

Instructions
You've examined and documented quite a bit of information from the iPhone image file. Now you will use that documentation to build a final report.

First, fill out the following evidence worksheet to document the case's WiFi and GPS locations. You will add this, along with the Correspondence Worksheet, to the final report.

Location Information Worksheet
Your group can look for WiFi and GPS info the following directories:

Find information about WiFi locations in root/Library/Caches/locationd/consolidated.db.

Note: Input GPS coordinates into Google Maps to see the locations.

Refer to the image below as an example:

Google-GPS

Find information related to WiFi and cell tower location information in consolidated.db.

Google-GPS

Working in your group's copy of the report template, add content and details as indicated in each section.

You will rely on the Locations Information and Correspondence Evidence Worksheets you've completed so far. Additionally, you can use the iPhone Forensics - Important Files and Databases resource to analyze and find more information to support your case, such as Voicemails and notes from the Notepad iPhone application.

Be sure to add to the report the equipment and tools you used to gather and analyze the evidence.

For example, Autopsy, the operating system (Kali Linux), text editors (Nano), etc.
When including pictures from the iPhone, please use the time stamp of the Created time from autopsy.

Submission Guidelines
Each group should submit one version of the completed Final Case Report document.
Bonus Assignment: Russian Tea Room
The goal of this assignment is to sharpen your skills in locating and identifying data in a forensic image.

These skills are important for tasks related to locating and decoding data, such as executable code or malicious documents embedded in images or network logs.
Scenario: The Case of the Little Russian Tea Room
There was a fire at the Little Russian Tea Room restaurant last week, and the only thing recovered was a hard drive. To start rebuilding the business, the restaurant hired you as a forensics investigator to look at the disk image and reconstruct the menu.

You'll be working with an EnCase image of the hard drive.

Luckily, the English and Russian menu are both in the hard drive image. However, only the English menu and two sections of the Russian menu are readable. Your must decode several sections of the Russian menu.

Resources:
The strings in the EnCase image are hex and represent the UTF-16 format. You'll need to be familiar with hex and UTF-16 encoding and decoding for this activity.

Review this Unicode Tutorial and the practice exercises. This review will help you locate the menus on the hard drive image.
Below are the files required to complete the assignment:

RussianTeaRoom.zip (560 KB): The Autopsy case file and Encase image file.

menu.pdf (56.0 KB): The Little Russian Tea Room menu.

Google Sheets: Russian Team Room

Unicode-Tutorial.md: Short Unicode tutorial.

The files can also be found in the /root/autopsy-files/homework directory in Autopsy.

Instructions
Your task is to find, decode, and document six of the menus from the hard drive image using the Unicode Cyrillic and Latin character (cipher) set.

Launch Autopsy and select Open Case.

Open the RussianTeaRoom folder and select RussianTeaRoom.aut.

Add the Russian-TeamRoom.E01 EnCase image file to the case.

This is a sample of the hex data in the Autopsy RussianTeaRoom case file:

Images/hex-data.png

Use Google Sheets: Russian Team Room to document the remaining information from the EnCase image for the investigation.

Find and document the complete file locations for the six menu sections in the image.

Hint: There may be multiple locations for the same file.
Document the menu items in Cyrillic (e.g., бифштеке) and English (e.g., steak) for the two following menu sections:

Pancakes (Menu #3)

Meat and Fish (Menu #5)

Hint: Use the Hex and String tabs in Data Content window in Autopsy to view the data.
String Dump
