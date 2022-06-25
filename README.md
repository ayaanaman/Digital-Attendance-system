# Digital-Attendance-system
Developed a fully automatic and modernized attendance system  Used Deep Learning technology for detection and recognition of faces. Linked with Excel sheet which updates automatically. Used Tkinter for designing GUI
Topic : Digital Attendance System
Problem Statement: Modernization of Conventional Attendance System.
Special Features : 
❏ Fast and Multiface detection at same time
❏ Real time system
❏ Graphical representation
❏ Adding a student from the Logbook
❏ Removing a student from the Logbook 
Approach :
● Attendance Module:
Reading frames -> Detecting and matching faces-> Processing -> Updating in excel sheet
● Adding New Student:
Manual capturing->Encoding image->Saving in encode data base(in proper order)->Saving image 
to folder(in proper order)->Updating Student in excel sheet(in proper order)
● Removing Student:
Manual input Name->Finding image in Student image Folder and deleting->Getting Index->Using 
index to delete encoding from database->Using index for removing Student from excel sheet
● Graphical representation:
Traversing through each row in Excel sheet->Taking count of no. of PRESENTS and save as per 
their names->Using plotly for representation in percentage.

![image](https://user-images.githubusercontent.com/58986643/175780107-b5e39ac4-c973-40ed-b963-e5c42dcbf034.png)
![image](https://user-images.githubusercontent.com/58986643/175780174-7e7d0337-d7b0-4041-933d-ad57584eec48.png)
![image](https://user-images.githubusercontent.com/58986643/175780204-1d8b1a5e-2610-4141-b468-0f42c6e44060.png)
![image](https://user-images.githubusercontent.com/58986643/175780221-32fadd91-6d73-426b-839c-1ae3e7ffb8bb.png)
![image](https://user-images.githubusercontent.com/58986643/175780253-20beab04-917c-45fd-b53e-5ba2d03ae9e6.png)
