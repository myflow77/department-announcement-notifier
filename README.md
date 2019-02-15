# Department-Announcement-Notifier
경북대학교 컴퓨터학부 공지사항 게시판을 크롤링하여 새 게시글 등록 시 등록된 메일 주소로 알림을 보내주는 프로그램입니다.

## 사용 플랫폼, 패키지
- AWS Lambda  
- AWS dynamoDB  
- python boto3  
- python bs4  
- python requests  
- python pytz  

## 주의사항
AWS lambda에서 사용하기 위해서는 위의 파이썬 패키지들을 작업 디렉토리 안에 오프라인 다운로드해야합니다.

~~~
pip install {packages} -d .
~~~