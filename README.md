# Private Storage

## 

## Project title

_________

PC와 모바일의 저장공간을 연결하여 PC에서 작성한 내용을 모바일에서 확인 및 편집하거나 반대의 경우를 가능하도록 구현

## Motivation

_________

PC에서 작성한 문서 또는 파일들을 모바일 앱을 통해 입출력하거나 모바일에서 작성한 파일을 PC에서 사용하고 싶다는 니즈를 충족시키기 위해 프로젝트를 기획하고 구현

## Tech/framework used

______

### Server 

java 1.8, Spring context, Spring data mongodb, mongoDB

### Client

java 1.8, swing UI, Android Studio

## Structure

________

![제목 없음](https://user-images.githubusercontent.com/41600558/92667554-2fe53700-f347-11ea-9535-aeb24f062e9c.png)

## Features

_________

- 사용자 인증(Spring Security 적용)
- 공유공간의 파일리스트 출력 및 탐색
- 파일 입출력

## How to use?

_______

빌드시 생성되는 apk와 windows 설치파일을 각각 모바일과 PC에 설치하여 이용 가능

1. 사용자 등록
2. 로그인
3. PC에서 저장공간을 지정
4. 모바일을 통해 저장공간 확인 및 편집