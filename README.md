# Google_classroom_attedance_check Program 

## Program introduction

Download and Use google classroom attendance check program. \
It checks students' comments automatically and gives you excel file.

<img width="960" alt="example" src="https://user-images.githubusercontent.com/60082435/79423965-733ab400-7ffa-11ea-88f9-f2777b0106a8.PNG">

You can check whether a student attended or was absent with a excel file created after execution of this program.\
Attendace in that day is expressed as "O", Lateness is expressed as "(Real_date)" format and Absent is expressed as ".".

## How to use 


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


## Informations you have to enter

1.tudents' name(학생 명단) : Enter students' names seperated by comma and space(, ). (ex - 유재석, 하하, 박명수, 정형돈, 노홍철, 정준하)

(2)







7. 프로그램 실행시 입력해야 하는 정보들
(1) 학생 명단 : 수업을 듣는 학생들의 이름을 컴마와 스페이스(, )로 구분하여 입력해 주세요.
(유재석, 박명수, 정준하, 노홍철, 정형돈, 하하) <- 이런식으로 컴마와 스페이스로 정확히 구분되어야 합니다. 
 이렇게 다 입력하시는게 귀찮으시겠지만, 메모장에 한번 정리해 두시면 계속해서 쓰시기 편하실 것입니다. 
다 입력한 뒤에는 엔터를 쳐주세요!

(2) 수업이 진행되는 요일 : 강의가 월수에 진행된다면 월/수, 화목에 진행된다면 화/목, 금요일에 진행된다면 금 이라고 입력해주시면 됩니다.

(3) 구글클래스룸 강의 메인페이지의 url : 구글 클래스룸 강의 페이지의 주소(url)을 입력해 주시면 됩니다. (http로 시작하는 주소입니다.)

(4) 구글 email 주소(학교 메일) : ****@khu.ac.kr 형식의 이메일을 입력해주시면 됩니다.

(5) 경희대학교 웹메일 아이디 : 경희대학교 웹메일에 로그인하는 아이디를 입력해 주시면 됩니다.

(6) 경희대학교 웹메일 패스워드 : 경희대학교 웹메일에 로그인하는 패스워드를 입력해주시면 됩니다.
패스워드는 키보드로 입력해도 화면에 보이지 않으니, 신경쓰지 마시고 입력해주신 뒤 엔터를 치시면 됩니다.

(7) 정리된 엑셀 파일이 저장될 절대경로 : 최종적으로 출석체크 결과가 정리될 엑셀이 저장될 위치를 절대경로로 적어주시면 됩니다. 

[프로그램 이용시 주의 사항]

1. 해당 프로그램은 다음과 같은 방식으로 출석체크를 하고 있습니다.

(1) 학생이 (3/25, 4/1 나경아 출석합니다.) 라고 댓글을 단 경우
: 학생이 3/25, 4/1일에 대한 출석체크를 원하는 것으로 간주하여 3/25, 4/1일에 출석을 한것으로 표시됩니다. 
이때 실제 댓글을 단 날짜와 학생이 출석을 원한 날짜가 일치하는 경우 O, 일치하지 않는 경우에는 실제 댓글을 단 날짜를 표기하도록 하였습니다.

(2) 학생이 (나경아 출석합니다.) 와 같이 어떠한 날짜에 대한 출석을 의도했는지 명확히 적어주지 않은 경우 

: 만일 해당 글이 하루에 대한 출석체크(예를 들어 3/25에 대한 출석체크)를 담당하는 글이라면, 해당 날짜에 출석을 한 것으로 간주하고 출석체크를 해야 하는 날짜와 실제 체크한 날짜가 같다면 O, 다르다면 실제 출석 체크를 한 날짜를 표기하도록 하였습니다.

: 만일 해당 글이 여러 날에 대한 출석체크(에를 들어 [3/25 강의] [4/1 강의]로 표시)를 담당하는 글이라면, 학생이 실제 댓글을 단 날짜를 보고 해당 날짜에 대한 출석 체크가 이루어질 수 있도록 하였습니다.

따라서, 해당 알고리즘에 대응하지 않는 댓글은 누락되었을 수 있습니다. 결석을 한 사람이 있다면, 반드시 구글클래스룸 강의의 댓글 창을 열고 CTRL + F(찾기) 기능을 이용하여 해당 학생의 댓글이 누락되었는지 확인해주셔야 합니다.

2. 동명이인은 출석체크가 올바르게 처리되지 않습니다.

해당 클래스에 동명이인인 학생이 있다면 반드시 CTRL +F(찾기) 기능을 통해 따로 출석체크 해주시길 바랍니다.

3.  엑셀 파일을 더 쉽게 보기 위해서는 첫행 고정으로 날짜를 고정하여 사용하시면 편리합니다. 엑셀 : 보기 -> 틀 고정 -> 첫행 고정으로 고정하시면 됩니다.

교수님과 조교님들의 귀한 시간을 아끼는 데 도움이 되었으면 합니다.
감사합니다.
첨부파일 영역
