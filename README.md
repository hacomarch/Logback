# LogBack란?

Slf4j 라는 인터페이스를 구현하는 구현체

Logging 프레임워크

운영을 위해서는 반드시 로그가 필요하다. 그래서 로그백 설정을 해서 로그를 관리한다.

데이터는 돈이므로 로그는 곧 값비싼 자산이다.

Appender 종류
- ConsoleAppender : 콘솔에 로그를 출력
- FileAppender : 파일 단위로 로그 저장
- RollingFileAppender : (설정 옵션에 따라) 로그를 여러 파일로 나누어 저장
- 위의 3개가 제일 많이 사용됨.
- SMTPAppender : 로그를 메일로 전송해 기록
- DBAppender : 로그를 DB에 저장
