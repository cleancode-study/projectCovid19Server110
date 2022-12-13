#### todoList

| 완료     | 작업내용                       |작업자|
|--------|----------------------------|----|
| closed | data.go.kr 공공데이터 요청        |김준석|
| closed | Java 언어로 api데이터 받기 샘플코드 완성 |김준석|
| closed | github가입과 관리               |김준석|
| closed |readme.md 개발문서 작성|김준석|
| open   | server0과 server1 @GetMapping 연결 구조 설계 | 김준석|
| open   | 통계용어 정리 및 메서드 추가 1 | 김준석|
| open   | 그래프 그리기 3 | 김준석|

---

#### 서버 directory 구조


> component
> > convert : json과 map 자료형 변환 메서드

> controller
> > graph : graph HTML 이동
> 
> > openapi : 공공데이터 혹은 openapi 받는 controller
> 
> > rest : 통계서버 (python) 연동하는 api

> entity
> > example : DB 혹은 데이터 튜플 단위의 자료형 class

> repository
> > example : JPA를 활용하여 MySQL 연동

> service
> > example : 실질적인 개발자 코드를 작성하는 영역 (controller와 의존관계)

> temp : 사용하지 않는 코드를 임시 저장


#### 관련 서버 구조
![이미지제목](/src/main/resources/static/img/structServer.png)
---
#### 스토리 보드
![이미지제목](/src/main/resources/static/img/storyboard.png)
---
#### 클래스 다이어그램
![이미지제목](/src/main/resources/static/img/storyboard.png)


---
#### 요구사항
코로나 데이터 시각화

코로나 데이터 통계

코로나 데이터 모델링과 검증

---
#### 개발문서
| 제목             |주소 |작업자|
|----------------|----|----|
| 시각화 서버코드 110   |https://github.com/cleancode-study/projectCovid19Server110.git|김준석|
| 시각화 서버 ip/port |http://192.168.42.100:8080/|김준석|
| 관리 서버 ip/port  |http://192.168.42.100:8090/|김준석|
| 시각화 서버(python) |http://192.168.42.100:8100/|김준석|
| 통계 서버(python)  | http://192.168.42.100:8110/ |김준석|

#### 개발환경
- spring boot 3.0.0
- - mysql connector
- - thymeleaf
- - lombok
- - json
- mysql 

---
#### developer
email : js@cleancode.kr
name : js

```
opend : 작성진행요청
in progress : 작업진행중
closed : 완료
```

---
예제
```
` : ESC 바로 아래 키 * 3 : 블럭 코드 작성 가능 : 복사할 코드 작용
# : 제목같은 큰 문자열에 쓰는 선언문 = HTML의 <h2>
```
# 한개
## 두개
### 세개


```
하이퍼 링크 예제 : 링크거는 문자열 선언 : HTML의 <a href:링크주소>
```
<https://naver.com/>

[네이버](https://naver.com)

```
선 긋기 : 가로줄 생성 : HTML <hr>
```
***
<hr>

```
순번 없는 목록
```
* 안녕하세요

```
순번 있는 목록
```
1. 일번
2. 2번

```
이미지 링크 : readme.md 파일에서 이미지 파일을 불러와서 보이기
절대주소(프로젝트의 최상단 위치에서 이미지 파일 경로 찾기)로 표기
```
![이미지제목](/src/main/resources/static/img/YONSAI_1920x1080.jpg)

```
테이블 작성
좌측, 우측 정렬 시 클론 사용 ---: 클론으로 정렬하고 싶은 위치 지정
```
|            제목 | 내용312321312312312312312312 |
|--------------:|---------------------------:|
|          테스트1 |              테스트1231231232 |
