# 프로젝트 planning

[파일 컨벤션](#파일-컨벤션)  
[기술 스택](#기술-스택)  
[일정 및 마일스톤 관리 방법](#일정-및-마일스톤-관리-방법)  
[효율적인 의사소통 방법](#효율적인-의사소통-방법)  
[R&R 분배](#rr-분배)  
[Git 레포 세팅, 커밋 메시지 방식](#git-레포-세팅-커밋-메시지-방식)

## 파일 컨벤션

- api: (https://rolling-api.vercel.app/8-5/)와 통신하는 코드 담는 곳
- assets: png, svg 등 여러 이미지 파일을 올리는 곳
- components: 페이지 컴포넌트를 제외한 모든 컴포넌트를 담는 곳
- hooks: custom hooks를 만드는 곳
- layouts: 각 route의 공통 layout을 만들어 두는 곳
- pages: url 기준 각 path 값에 해당하는 컴포넌트를 담는 곳
- styles: css 파일을 담는 곳 (컴포넌트 파일 이름과 똑같이 작성한다.)
- utils: custom hook을 제외한 공통적으로 쓰일 유틸함수를 담는 곳

## 기술 스택

- dayjs: 날짜 정보를 get, set할 수 있는 라이브러리
- axios: fetch를 대체할 비동기 통신 라이브러리

## 일정 및 마일스톤 관리 방법

- jira atlassian 으로 타임라인, 칸단 보드 작성

## 효율적인 의사소통 방법

- (월 ~ 토) 오후 2시 ~ 5시까지 코어타임
- (월 ~ 토) 오후 3시에 데일리 스크럼

## R&R 분배

- 신윤하 : **메인 페이지** "/", **생성된 롤링페이퍼 수정 페이지** "/post/{id}/edit"
- 강효성 : **롤링페이퍼 만들기 페이지** "/post", **롤링페이퍼에 메세지 보내기 페이지** "/post/{id}/message"
- 조규진 : **롤링페이퍼 목록 페이지** "/list"
- 김강우 : **생성된 롤링페이퍼 페이지** "/post/{id}"

## Git 레포 세팅, 커밋 메시지 방식

- 커밋 메시지 방식 : 한글로 커밋 메시지를 작성해주세요
  > 제목과 설명을 모두 잘 작성하시면 됩니다.  
  > push 시에는 각자의 [이름]으로 된 branch에 push하셔야합니다. **절대 main 하지 마세요!!**  
  > pull 받을 때에는 미리 안내하겠습니다. (각자의 이름으로 만든 branch에서 merge할 시간이 필요합니다.)
