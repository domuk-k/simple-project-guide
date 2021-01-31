<div align=center>
  <p> FC-FDS 18기를 위한</p>
  <h1> JS 프로젝트 간단 가이드</h1>
  <img width=200 src="https://i.etsystatic.com/13517909/r/il/e028cc/1802571151/il_570xN.1802571151_kie1.jpg"/>
</div>

<br/>

## TOC

### 1. [팀빌딩](#팀-빌딩)

### 2. [일정과 목표](#일정과-목표)

### 3. [프로젝트 설계](#프로젝트-설계)

### 4. [프로젝트 매니징](#프로젝트-매니징)

### 5. [구현](#구현)

### 6. [결국 남는 것](#결국-남는-것)

----


### 팀 빌딩

- PM의 역할과 책임 : 프로젝트 환경 세팅, 빌드 옵션, 소스코드 관리, 업무 분배
- 커뮤니케이션 : 각자의 프로젝트에 참여한 목적과 지향하는 방향을 공유
- 구현할 앱, 또는 product 결정 : 클론, 개선된 형태, 합쳐진 형태 등 방향성 결정

### 일정과 목표

- 일정 : 디버깅, 리팩토링, 리스크 버퍼 기간을 제외한 가용기간
- 목표 설정 : 구현할 앱 명세. **일정을 고려한 최소구현기능** 설정. 주요 **마일스톤** 설정.

  ex.

  1. 월 - 팀 빌딩, 레퍼런스 조사, 최소구현기능 목록 작성, 컨벤션 정리, 사용기술 정리 등. README.md 초안
  2. 화수 - 기능구현
  3. 목금 - 디버깅, 마무리(포기할거 포기하기), README.md 완성

### 프로젝트 설계

- 상태관리 & 뷰 설계

  - 컴포넌트 / 전역 상태 : 용어에 대한 이해
  - 모듈 분리 기준
  - 분리된 모듈들이 **어떤 상태를 어디서 가져다가 사용할까?**
  - render 함수가 무얼 해야할까?

- 컨벤션 합의

  - JS 문법
  - git commit prefix / issue label
  - 네이밍 컨벤션
  - 스타일링 방식

- 개발환경 설정 공유

  - 모듈 번들러 선택
  - 정적 코드분석 툴 (`eslint`,`prettier`)
  - etc.

- 구현/배포 방법 논의

  - 외부 라이브러리 선별
  - 배포 전략 선택

- 업무 분담
  - 기능 단위 분담 권장

### 프로젝트 매니징

- git 활용 : `git flow`, github org, project, issue/milestone
- 스크럼 회의 : 매일 정해진 시간동안만 todo-doing-done 에 관한 공유 - 개별 사항은 별도 미팅

### 구현

- 내가 다른 개발자에게 설명할 수 있는 코드
- 컨벤션에 맞는 코드
- 컨벤션이나 협업이 필요한 부분에 대한 적극적인 논의

### 결국 남는 것

- 결과물
  - 팀원 모두가 팀의 **결과물을 이해하고 설명할 수 있기** 바랍니다.
- 사람 : 감정적인 다툼이 없기 바랍니다. 현업에서 뵙길 바랍니다.
