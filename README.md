# GitHub Copilot 활용 사례: BCR 모니터링 도구 개발

## 1. 프로젝트 개요 및 Copilot 적용

- **프로젝트 배경**: 기존 코드베이스를 활용한 BCR 모니터링 도구 개발
- **적용 범위**: 기존 코드베이스 구조 분석, 기능 명세서 작성, 아키텍처 설계까지의 프로젝트 진행 전 과정
- **사용 모델**: Claude Sonnet 3.7 Thinking
<br />
<br />

## 2. Copilot 활용 내용

### 2.1 코드베이스 분석 및 이해
![attach1](https://github.com/user-attachments/assets/c498557c-c7c2-4892-be1d-b599c1b9d482)\
**프로젝트의 전체 구조와 각 파일/폴더의 역할, 그리고 주요 기능이 무엇인지 설명해줘.**\
기존 프로젝트의 주요 컴포넌트와 역할, 기능 등 구조 파악
<br />
<br />

### 2.2 아키텍처 설계 및 문서 작성
![attach2](https://github.com/user-attachments/assets/6d617f59-bd56-4141-a49f-9547cc3f6f50)\
**Tool 디렉터리에 새로운 프로그램을 하나 만들고 싶어. 간단하게 생각해본 기능은 다음과 같아. 이를 구체화해주라.**\
간단한 요구사항을 제시해 기능 구체화
<br />
<br />

![attach3](https://github.com/user-attachments/assets/a00c3c68-f867-43c7-9678-67655c441565)\
**playback 폴더를 참고해서 어떤 구조와 로직이이 필요할지 구체화해줘. 코드는 필요없이 구조만 필요해. playback 폴더의 어느 부분을 활용하는지도 알려줘.**\
이를 바탕으로 기존 프로젝트를 활용해 새로운 구조 설계
<br />
<br />

### 2.3 문서 작성
![attach4](https://github.com/user-attachments/assets/42bb1fb6-7b33-41c7-b046-2651ef660759)\
**명세서를 생성하고, 다이어그램으로 로직을 그려줘.**\
기능 명세서와 다이어그램 작성해 이해도 향상
<br />
<br />

### 2.4 API 및 라이브러리 활용법 탐색
![attach5](https://github.com/user-attachments/assets/95b02f29-66cb-4278-8ed0-d202dcec832a)\
**하위 파일들을 참고해서 어떤 api를 활용할 수 있을지 추출해줘.**\
SUNAPI 문서를 참고한 API 활용 방안 도출
<br />
<br />

## 3. 사용 팁

### 3.1 효과적인 프롬프트 작성

![attach6](https://github.com/user-attachments/assets/7049b6b6-7024-40bc-ba98-1a4166e37797)\
**폴더 컨덱스트 활용**\
  AI가 프로젝트의 전체 맥락을 이해하고 기존 코드베이스와 일관된 솔루션을 생성하는 데에 도움을 줍니다.
<br />
<br />

![attach7](https://github.com/user-attachments/assets/6f8e3f0f-16d3-4393-88f8-62ce5f4a8504)\
**구체적으로 질문하기**\
  코파일럿이 생성한 문서에는 바코드를 인식하고 데이터를 추출하는 과정이 포함되어 있었습니다. 이미 rtsp로 받아올 수 있는 데이터이기 때문에 해당 부분을 생략하라고 요청하는 과정이 필요했습니다. 처음부터 구체적으로 질문하면 좋을 것 같습니다.

