# myGpt
## 기능 1. Chat-GPT 사용하기
* Open AI 사이트에서 REST API 형태로 제공해주는 기능을 사용하면 웹 브라우저에 나만의
chat-bot을 만들 수 있다.
* 기본적인 UI를 제공해주면서 원활하게 chat-bot과 상호작용을 할 수 있다.
* 기능 3을 위해서 채팅마다 기록한다.
## 기능 2. DALL-E2 사용하기
* 이미지를 생성해주는 모델을 Open AI 사이트에서 REST API를 사용하면 웹 브라우저에 서비
스할 수 있다.
* 한번의 prompt를 입력 시 4개 또는 8개의 이미지를 생성해서 보여준다.
* 이미지를 출력할 때 일정한 간격으로 정렬해서 보기 좋게 출력한다.
## 기능 3. 채팅 로그 보여주기
* 자바스크립트는 보안 문제로 인해서 파일 입출력 같은 기능을 사용하기 어렵다.
* 하지만 Web Storage API 를 이용한다면 JSON 형태로 브라우저에 데이터를 영구적으로 저
장할 수 있다.
* 이를 통해서 채팅 로그를 기록하고 TABLE 형태로 출력해주는 기능을 구현한다
