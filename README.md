# Face-Recognition-and-Attendance-marking-by-Python
Attendance of students in a large classroom is hard to be handled by the traditional  system,  as  it  is  time-consuming  and  has  a  high  probability  of  error during  the  process  of  inputting  data  into  the  computer.  This  paper  proposed automated  attendance  marking  system  using  face  recognition  technique.  The system deployed Haar cascade to find the positive and negative of the face and eigen face  algorithm  for  face  recognition  by  using  python  programming  and Open CV library. The attendance of the student was updated to the Excel sheet after student’s face has been recognized.


At the begining of the project we have to install the visual
studio 2019 (Community version)application from your browser.Next we have to
install Pycharm application.Now we have to install the packages that are
required for our project.
file<settings<packages

The packages for this project is:
(1)cmake
(2)dlib (19.18.0)
(3)numpy
(4)opencv
(5)face-recognition

These packages should be installed before the starting of the project
and in this project we have to use dlib(19.18.0) in specific 
because to reduce the error in the project.Now we have 
to browse for the pictures.For example,we have 
used pictures like Elon Musk,Jeo Biden,Trump,Modi,Virat Kohli.
The images of the members is stored in the folder(*(here)ImagesAttendance).


Now we have to select two different images of anyone members from choose.
One image of the selected members (in this case we have used Elon musk) is to 
be saved as train.py to train the Project for taking the attendance.And another 
image of the selected member should be saved as Test.py to test the image for 
the attendance purpose.


Now open Pycharm application.Then have the Basic.py as one file and AttendanceProject.py
as other file and do change the file path as per your system.Then run the 
AttendanceProject.py file, photo names stored will be displayed as a list 
and your webcam will automatically on in which you show photo of anyone member stored
in our folder.You get a green box around the face with the name at the bottom, if 
not so pls move closer to the camera you will get it.And then attendance will
be marked and will be displayed in excel file. 
