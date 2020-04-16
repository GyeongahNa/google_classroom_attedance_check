## GOOGLE_CLASSROOM_ATTENDANCE_COMMENTS_CHECK PROGRAM

## PROGRAM INTRODUCTION

Download and Use google classroom attendance check program. \
It checks students' comments automatically and gives you excel file.

<img width="960" alt="example" src="https://user-images.githubusercontent.com/60082435/79423965-733ab400-7ffa-11ea-88f9-f2777b0106a8.PNG">

You can check whether a student attended or was absent with a excel file created after execution of this program.\
Attendace in that day is expressed as "O", Lateness is expressed as "(Real_date)" format and Absent is expressed as ".".

## HOW TO USE


**0. Access to your classroom page.** 

When you access to your page, there would be posts you uploaded. Some posts would have attendance comments, ohers wouldn't because that is not for attendance but for annoucements or assignments. \
You have to write a comment that contains which date the post intended to check for. For example, If a post was created to check students' attendance for 3/25, you have to write "[3/25 강의]" as a comment on your post. If this post was designed to check for several days, you have to write "[3/25 강의] [3/30 강의] [4/1 강의]".

<img width="951" alt="0" src="https://user-images.githubusercontent.com/60082435/79429983-36bf8600-8003-11ea-8795-93b8014a15a6.PNG"> 


**1. Download google_classroom_attendance_check file and locate it at your Desktop.**

Access to here ↓ and click green button to download files. [Clone or Download] - [Download Zip] - unzip files at Desktop.

```
https://github.com/GyeongahNa/google_classroom_attedance_check
```

**2. Check your chrome version.**

Open a chrome page and check your chrome version. \
ou can check it with [click dots at the top-right of the screen] - [도움말] - [Chrome 정보]. For example, if your chrome version is expressed as  "80.0.3987.163", that is chrome 80.


**3. Copy chromedriver and Paste it at dist folder.**

Move to a forlder that you downloaded and located at your desktop. At chromedriver folder, there would be folders named "chrome 81, chrome 80, chrome 79". Enter the chrome XX folder coressponding to your chrome version. f your chrome version is 80, you have to enter chrome 80 folder. Then, You will be able to find chromedriver file. Copy it and paste to dist folder in parent-folder.

<img width="960" alt="3" src="https://user-images.githubusercontent.com/60082435/79434134-e5b29080-8008-11ea-8872-d4bba63c9561.PNG">

**4. Execute googleclassroom_attendance_check file.**

Execute "googleclassroom_attendance_check file" in dist file". Then you will be able to see black screen on your computer. Don't panic! Now you are ready to use automatic check program.

<img width="960" alt="4" src="https://user-images.githubusercontent.com/60082435/79435812-15629800-800b-11ea-8409-7cc7643ef93e.PNG">


## INFORMATIONS YOU HAVE TO ENTER

**1. Students' name** \
: Enter students' names seperated by comma and space(, ). 
(ex - 유재석, 하하, 박명수, 정형돈, 노홍철, 정준하) \
you will be irritated because there are so many students, but Once you write them in your notepad you can use it continuelly. After entering them, please press enter.

**2. Day of week** \
: If your class is progressed on Mon/Wed, Enter 월/수. If your class is progressed on Tue/Thu, Enter 화/목, You can enter 금 if your class is progressed on Friday.

**3. Google class room url** \
: Enter url of class that starts with http.

**4. Kyunghee univ web mail** \
: ****@khu.ac.kr

**5. Kyunghee univ web mail id**

**6. Kyunghee univ password** \
: Don't worry for your id or password to be devulged. Even I don't know who use this program and what you entered as information!

**7. Alsolute Path(Where your final excel file stored)** \
: How to see your absolute path of your desktop : [Open file explorer(파일 탐색기)] - [내 PC] - [로컬 C] - [사용자/User] - [your name] - [바탕화면/Desktop] - [Click address at the top]. For example, If your desktop address is C:\Users\나경아\Desktop, you can enter " C:\Users\나경아\Desktop\class_name.xlsx" to store your final file on your desktop.

## CAUTION

**1. you have to recheck students who were absent!** \
(It is really mandatory!) There are comments algorithm can't catch!!!!
Use CTRL + F to recheck absent students!!

**2. This program can't check for People with same name!** \
If your class have People with same name, Use CTRL + F to check them!

## PURPOSE OF THIS PROGRAM

Because of COVID-19, Most of Classes in our univ are using google classroom. Because there isn't enough ways to check students' attendance on online, students are writting comments and operators of classes have to check a lot of classes.
The purpose to make this program is to help timeless TAs and professors. I hope this program helps as many people as possible who suffer from checking all comments in google classroom. 
