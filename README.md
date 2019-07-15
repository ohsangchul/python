# Python 학습 내용
더좋은컴퓨터학원(종로) 파이썬 교육 과정

1. OT
 - 조각,조퇴,외출 3회 = 1일 결석 (기준 21시)
 - 수료 기준 80% (최대 : 결석4일, 기타 2회)

2. Tools
 - 화면 확대 프로그램 : ZoomIt
 - 폰트 : D2Coding -> D2Coding 폴더 아래 ttc 파일로 설치
 - 에디터 : jupyter notebook (https://jupyter.org/)
           
3. 교제 : 점프 투 파이썬 (https://wikidocs.net/book/1)
 - http://media.fastcampus.co.kr/knowledge/dataanalysis-python-r/ (Python이냐 R이냐...)
 - Python 과정 -> ML & 빅데이터 분석 과정 : Tensorflow + Anaconda(Library 모음) 사용
 
4. 파이썬 다운로드 : https://www.python.org/downloads/
 - 파이썬 버전마다 동작이 상이 할 수 있으므로 버전을 명기한 폴더를 생성해서 설치하는 것이 좋다.
 - 언제나 그렇듯 최신버전 보다는 안정화 버전을 설치하자...

5. 실습(연습) 사이트 : http://codingdojang.com/

# jupyter notebook 설치하기
1. 환경 변수 설정 (path 추가)
  - C:\Users\(사용자계정)\AppData\Local\Programs\Python\Python37-32
  - C:\Users\(사용자계정)\AppData\Local\Programs\Python\Python37-32\Scripts

2. 설치 (최신버전 업그레이드는 선택)
  - [cmd] => [pip install jupyter notebook]

3. 실행 (프로그램이 실행된 경로가 root가 된다)
  - [cmd] => [프로그램을 사용할 위치로 이동 : python source가 있는 곳(workspace)] => [jupyter notebook]

4. 비고
  - jupyter notebook에서는 .py파일 오픈만 가능하고 실행은 할 수 없다.
  - jupyter notebook로 작성한 내용을 .py파일로도 생성 할 수 있다. ([File] => [Download as])

5. 기타
  - Font 변경 방법 : C:\Users\Administrator(또는 사용자계정)\.jupyter 폴더에 custom 폴더를 생성하고 아래의 css 파일을 추가한다.  
  ** custom.css **
  .CodeMirror pre {
   font-family: D2Coding; 
   font-size: 12pt; 
   line-height: 140%; 
   font-weight: bold;
  }
  .container {
   width:100% !important;
  }
  div.output pre{
   font-family: D2Coding;
   font-size: 12pt;
   line-height: 140%;
   font-weight: bold;
   color: blue;
  }
  div > p {
   font-family: D2Coding;
   font-size: 12pt;
   line-height: 140%;
   font-weight: bold;
   color: red;
  }

# 참고 사이트 주소
< Python >
 https://docs.python.org/ko/3/
 https://wikidocs.net/book/1553
 https://code0320.tistory.com/category/python
 http://pythonstudy.xyz/

< Anaconda >
 http://docs.anaconda.com/

< Pandas >
 https://dataitgirls2.github.io/10minutes2pandas/
 https://doorbw.tistory.com/172
 https://pinkwink.kr/734
