# PROJECT OVERVIEW

# D.EXECUTING THE PROJECT


### **Project Design and Coding**

##### Flowchart Design:

![flowchart](https://user-images.githubusercontent.com/121369021/211849364-7463801c-9484-4da9-8f14-cd2950333ccf.png)
### Model Training Flowchart Design

<br>1.0 Start
<br>1.1 Activate camera for scanning
<br>1.2 Open Camera
<br>1.3 Search for face
<br>2.1 Face Detected
<br>2.2 If yes, draw rectangle around the face
<br>3.1 If unrecognize face, detect faces as 'unknown'
<br>3.2 If recognize face, detect faces by their names
<br>4.0 End

### **Description of the project coding and implementation**

Libraries and Packages required:

Facial Recognition System: Firstly, we load our model from the pre-trained that was created. From our Github repository, two file: mainwindow.py and out_window.py can be found. 

### **As for the mainwindow.py**

![packages](https://user-images.githubusercontent.com/95037934/211976277-a25adec1-1a40-47c5-8f93-58fcc29a0785.png)

Then, load the UI for the main window

![load ui](https://user-images.githubusercontent.com/95037934/211978162-3efe4322-bf69-4818-9363-370b30b5dc8e.png)

Once valid it will set the text of line edit

![set text once valid](https://user-images.githubusercontent.com/95037934/211978290-a5f9681b-e33b-48ba-b478-5136e0278f67.png)

When the user presses the Run button it sill called the class runSlot and it will hide the main window then open new output window

![call](https://user-images.githubusercontent.com/95037934/211978463-4c37d7ff-55ea-4368-854f-2d295d17082c.png)

Then a new window will be created for visual output of the video in GUI

![video](https://user-images.githubusercontent.com/95037934/211978567-f7817c6a-8228-4bb8-8cc6-c0d357575a53.png)

After the process is completed, the system will exit

![exit main](https://user-images.githubusercontent.com/95037934/211978648-fea383f4-1dc6-45ac-a713-412398d32a8c.png)

### **As for the out_window.py**

Load packages

![out Packages](https://user-images.githubusercontent.com/95037934/211978955-161bfca6-29f9-4412-a641-3b1ab09221ab.png)

Load output UI

![out ui](https://user-images.githubusercontent.com/95037934/211979002-d214a752-5493-4617-8c39-4bd73bcff6b5.png)

Link camera and start video

![out cam](https://user-images.githubusercontent.com/95037934/211979039-0e895e7b-0ff8-4de6-bc28-ec8c25829f96.png)

Save in attendance list

![out att](https://user-images.githubusercontent.com/95037934/211979101-ba9be924-563a-4223-82aa-1a186c95c31f.png)

check face and sync with excel

![out csv1](https://user-images.githubusercontent.com/95037934/211979141-fafaa407-96f8-4b10-90c6-8030f9e26b09.png)

![out csv2](https://user-images.githubusercontent.com/95037934/211979165-9f88a99f-5673-4c75-ac2b-46c15f1706e4.png)

![out csv 3](https://user-images.githubusercontent.com/95037934/211979185-46ee5196-0b01-473e-bdb8-c829f1d40c8e.png)

Face recognition

![face rec](https://user-images.githubusercontent.com/95037934/211979251-f48ffd19-b4cc-4df5-9a2d-3de0cc19e294.png)

Show dialog message box

![out dialog](https://user-images.githubusercontent.com/95037934/211979345-5e9561e0-2a56-4056-bad3-29bf610cf1c2.png)

Save the details in Excel when user click the Clock In and Clock Out button

![out list](https://user-images.githubusercontent.com/95037934/211979558-5fc9c9ab-e44d-465f-b9c5-f1e1fc21c7a2.png)

![out image](https://user-images.githubusercontent.com/95037934/211979811-712f30f5-9832-4ee2-842f-bf5ac2e6c5b6.png)


### **Project Result**

Result using Qt Designer

Interface

![ui](https://user-images.githubusercontent.com/95037934/211982202-34d6b838-d4e7-41d5-b42d-e4e297aedca3.jpg)

Clock In

![clocking in](https://user-images.githubusercontent.com/95037934/211982258-7f4bf8a7-ea68-44dc-9ecc-cd762a59148f.jpg)

![clock in](https://user-images.githubusercontent.com/95037934/211982281-5697a7d2-3d0c-41a7-981a-0b8add395f9c.jpg)

Clock Out

![clocking out](https://user-images.githubusercontent.com/95037934/211982304-2ea8d5cf-3ae5-483f-880e-2d22c32c2610.jpg)

![clock out](https://user-images.githubusercontent.com/95037934/211982317-62187606-8bc1-4de9-9212-5ddc4730bc2e.jpg)


