# ⛅ 실전 날씨 일기 API 프로젝트

## ⚙ 주요기능
<ol>
  <li>Open Weather Map api를 이용해 날씨 데이트를 얻어옴</li>
  <li>외부 API에서 받아온 날씨 데이터와 함께 DB에 저장함</li>
  <li>해당 날짜 혹은 기간의 일기를 List형태로 반환해주는 기능</li>
  <li>해당 날짜의 첫번재 일기 글을 새로 받아온 일기글로 수정해주는 기능</li>
  <li>해당 날짜의 모든 일기를 지워주는 기능</li>
  <li>DB와 관련된 함수들을 트랜잭션 처리 함</li>
  <li>매일 새벽 1시에 날씨 데이터를 외부 API에서 받아다 DB에 저장해둠</li>
  <li>logback을 이용한 프로젝트 로그</li>
  <li>ExceptionHandler를 이용한 예외처리</li>
  <li>swagger를 이용한 API documentation</li>

## 🛠 사용기술
<ul>
  <li>Language : <strong>Java</strong></li>
  <li>Build : <strong>Gradle</strong></li>
  <li>Database : <strong>MySql</strong></li>
  <li>JDK : <strong>OpenJDK 21</strong></li>
  <li>Testing : <strong>JUnit</strong></li>
  <li>Library : <strong>web, jdbc, mysql-connector-java, jpa, json-simple, swagger, servlet-api, webmvc, springdoc, lombok, junit</strong></li>
  <li>Tool : <strong>IntelliJ IDEA Ultimate</strong></li>
</ul>
