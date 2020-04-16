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




















0. 구글 클래스룸의 강의 페이지에 접속합니다. 
구글 클래스룸 강의 페이지에 접속하면, 그동안 올리신 게시물들이 있을 것입니다. 
각 게시물 중에는 출석 댓글이 달리는 게시물도 있고, 단순히 공지를 위한 게시글도 있을 것입니다. 
각 게시물들 중에서 출석 댓글이 달리는 게시물에 어떠한 날에 대한 출석댓글이 달리는 글인지를 댓글로 명시해 주셔야 합니다. 
예를 들어 어떠한 게시물이 3/25일에 대한 출석 댓글이 달리는 글이라 한다면, [3/25 강의]라고 댓글을 달아주셔야합니다. 
만약 여러날에 대한 출석체크를 담당하는 글이라면, [3/25 강의] [3/30 강의] [4/1 강의] 라고 해당 글에 댓글을 달아주시면 됩니다. 
형식은 반드시 "[X/X 강의]"로 입력하셔야 인식이 됩니다. 
해당 댓글이 달리지 않은 글은 출석을 담당하는 글로 인식이 되지 않기 때문에 정확한 날짜를 [X/X 강의] 형식에 맞추어 달아주시는 과정이 꼭 필요합니다!

1. 메일에 첨부된 google classroom attendance check.zip을 다운받습니다.

2. 바탕화면에 폴더 하나를 만들고, 해당 폴더에 압축파일을 풀어줍니다. 
압축 암호는 kyunghee 입니다

3. 크롬 페이지를 열고, 오른쪽 상단의 점 세개 아이콘 클릭 -> 도움말 -> chrome 정보 로 접속하여 크롬 버전을 확인합니다.
 예를 들어 버전이  80.0.3987.163 라고 표기되어있다면, 크롬 80 버전입니다.

4. 압축을 풀어준 폴더로 이동하여, chromedriver 폴더로 접속합니다.  
chromedriver 폴더에는 chrome 81, chrome 80, chrome 79 폴더가 있습니다.  
이전 단계에서 확인한 크롬 버전에 해당하는 폴더로 이동합니다.
 (크롬 버전 확인시 80 버전이었다면 chrome 80으로 이동하면 됩니다.)

5. chrome 81, chrome 80, chrome 79 폴더 중 하나의 폴더로 이동했다면, 그 폴더 안에는 chromedriver 항목이 있을 것 입니다. 
해당 chromedriver 파일을 복사하여 맨 바깥에 있는(압축을 풀었을 때 들어가면 바로 확인할 수 있는 폴더) 폴더들 중 dist 폴더에  chromedriver를 붙여넣어 주시면 됩니다.

6. dist 폴더 내에 chromedriver을 세팅해 주었다면 해당 폴더 안에 있는 googleclassroom_attendance_check 파일을 실행해주세요.
 프로그램을 더블클릭하면 까만색 창이 실행되면서 조금 뒤 문구들이 뜰 것입니다.

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
