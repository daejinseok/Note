토탈커맨더에서 FTP 접근할 때,
기본적으로는 서버종류를 알아서 판단해서 디렉토리, 파일구조 정보를 보여주게 되는데,
간혹 드물게 서버 종류를 알아차리지 못해, 날짜가 ? 표시 되는 경우가 있다.


날짜가 ? 표시된다


그중에 FTP 접근할 서버가 SunOS -한글로컬설정- 일 경우에도 동일하게 발생을 하는데  (날짜가 ? 표시) 이때 해결책은 다음과 같다.

1.토탈 커맨더의 FTP 연결세부사항 에서 서버 종류를  "사용자정의 (매우 드문형태의 서버일 때)" 로 설정. - Server type : Define new type (for exotic servers)

2.FTP 정보를 저장하기 위해 확인을 누르고 FTP 로 접근 

2.호스트유형정의 (Define server type) 화면에서 문자열 정의 란에

pppppppppp--------------------S*-MM---DD----UUUUU n*

3.정의 문자열 추가 (Additional definition strings -optional) 란에
 
pppppppppp----------------------SSSSSSSS---YY---MM---DD---n*

정보를 입력한다.
