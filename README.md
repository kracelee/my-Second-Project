# TIL

## 리눅스 명령어

1. ls

   > list(목록)

2. cd
   change directory (작업 경로 변경)

3. rm

   > remove (파일 삭제)

4. mkdir  
   make directory(작업목록 생성)  
    (빈칸 3번 입력하고 엔터)

5. rmdir  
   remove directory (작업목록 삭제)

6. touch  
   파일 생성

7. cat  
   파일의 내용 출력

# Git

1. init  
   git 생성
2. add <파일명>  
   staging area
3. commit -m <메세지>  
   Repository로 이동
4. push<원격저장소><브랜치>  
   원격(GitHub)으로 이동
5. pull<원격저장소><브랜치>  
   원격에서 로컬로 복사
6. clone <원격저장소><브랜치>  
   원격에서 로컬로 복제
7. status  
   StagingArea의 상태
8. log  
   repository의 상태
9. git commit --amend  
   바로 전 commit과 stagin Area의  
   Merge를 할 때
10. git restore --staged파일명  
    stagin area의 파일을 working
    directory로 가져옴

![Git Sheat Sheet](asset/cheatSheet.gif)

ㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡ

인코딩 <-> 디코딩

기계 : 0과 1만 인식
'a' : 97 'A' : 65 '0' : 48

문자코드 : 컴퓨터언어 0과 1로 변환할 때

사용되는 기준

문자와 숫자를 1:1로 맵핑시켜놓은 값

ex)문자 : 'A'

ㅡㅡㅡㅡㅡ

진법(진수): 10(사람) <-> 2, 8, 16(기계)

[ 인식하는 값 ]

5 <-> 101

문자코드 : 아스키코드(ASCII code)(7bit),
안시코드(ANSI, 8bit, 확장ASCII),
유니코드, EUC-KR코드

code paging:각 나라별로 제공

대한민국 : cp949

인코딩 : ASCII, 유니코딩(utf-8/16/32),

ㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡ

2진법 : 0과 1

8진법 : 0~7 / 10진법 : 0~9

16진법: 0~9 10~15(A~F)

bit/byte : 데이터를 표현할 수 있는 단위

      0, 1만 저장할 수 있는 단위

8bit = 1byte

1101(2)=13(십진법) / 13=1101(2) (2진법)
257(8)=175 / 175=257(8) (8진법)
2AD(16)=685 / 685=2AD(16)(16진법)

ㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡ

front <-> back-end<-> Database

[프론트엔드]
developer.mozilla.org/ko/docs/Web/HTML
w3schools.com
getbootstrap.com
jquery.com
reactjs.com
ko.reactjs.org

<html>
  <head>
    <style>
  h1{color.red; 
      background-color:yellow;
</style> </head> </html>
