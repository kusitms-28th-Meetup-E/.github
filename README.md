
## **💻 Technology**



### FrontEnd

<img src="https://img.shields.io/badge/typescript-3178C6?style=flat&logo=typescript&logoColor=white"/><img src="https://img.shields.io/badge/React-61DAFB?style=flat&logo=React&logoColor=white"/>
<img src="https://img.shields.io/badge/recoil-3578E5?style=flat&logo=recoil&logoColor=white"/>
<img src="https://img.shields.io/badge/vite-646CFF?style=flat&logo=vite&logoColor=white"/>
<img src="https://img.shields.io/badge/styledcomponents-DB7093?style=flat&logo=styledcomponents&logoColor=white"/>
<img src="https://img.shields.io/badge/axios-5A29E4?style=flat&logo=axios&logoColor=white"/>

### Server

<img src="https://img.shields.io/badge/SpringBoot-6DB33F?style=flat-square&logo=SpringBoot&logoColor=white"> <img src="https://img.shields.io/badge/SpringDataJpa-6DB33F?style=flat-square&logo=SpringDataJpat&logoColor=white"> 
<img src="https://img.shields.io/badge/QueryDsl-137CBD?style=flat-square&logo=QueryDsl&logoColor=white">
<img src="https://img.shields.io/badge/Gradle-02303A?style=flat-square&logo=Gradle&logoColor=white">
<img src="https://img.shields.io/badge/Swagger-85EA2D?style=flat-square&logo=Swagger&logoColor=white">
<img src="https://img.shields.io/badge/JWT-black?style=flat-square&logo=JSON%20web%20tokens">
 

<br>
<img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=MySQL&logoColor=white">
<img src="https://img.shields.io/badge/AmazonEC2-FF9900?style=flat-square&logo=AmazonEC2&logoColor=white">
<img src="https://img.shields.io/badge/AmazonRDS-527FFF?style=flat-square&logo=AmazonRDS&logoColor=white">
<img src="https://img.shields.io/badge/AmazonS3-569A31?style=flat-square&logo=AmazonS3&logoColor=white">
<img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=Redis&logoColor=white">

<br>
<img src="https://img.shields.io/badge/GithubActions-2088FF?style=flat-square&logo=GithubActions&logoColor=white">
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=Docker&logoColor=white">

## **💻 시스템 아키텍쳐**

![architecture](https://github.com/kusitms-28th-Meetup-E/.github/assets/53565255/9a66a3e7-8215-4163-808e-c4518c55ba9e)


## 🏠 기술 스택 및 프레임워크 사용 이유


### 🌿 FrontEnd

| React | TypeScript |
| --- | --- |
| **빠른 렌더링**<br>React는 사용자 인터페이스를 만들기 위한 강력하고 유연한 JavaScript 라이브러리로서, 컴포넌트 기반 아키텍처와 가상 DOM을 통해 빠른 렌더링을 제공합니다.<br><br>모듈 개발 컴포넌트 재사용성과 가독성이 뛰어나며, 커뮤니티와 생태계가 크기 때문에 문제 해결이나 모듈 개발에 도움이 되기에 React로 선정하였습니다. | **코드 안정화** <br>TypeScript는 정적 타입 언어로, 코드를 더 안정적으로 만들고 개발자 사이의 협업을 용이하게 해줍니다.<br><br>**생산성** <br>컴파일 단계에서 에러를 발견하여 런타임 오류를 방지하며, 코드 힌트와 자동 완성을 제공하여 개발 생산성을 높여주는 장점이 있어 TypeScript를 선정하게 되었습니다. |

| vite | Recoil |
| --- | --- |
| **신속한 개발** <br> Vite는 빠른 개발 환경을 제공하는 도구로, 신속한 개발과 빌드 시간을 최소화합니다.<br><br>**빠른 리로딩**<br> HMR(Hot Module Replacement)을 통해 빠른 리로딩을 제공하고, 기본적으로 ES 모듈을 사용하여 빌드 시간을 줄여준다는 장점이 있어 vite를 선정하게 되었습니다. | **복잡성 최소화** <br>Recoil은 React 애플리케이션의 상태 관리를 간단하게 만드는 라이브러리로, 컴포넌트 간 데이터 공유를 용이하게 합니다.<br> 중앙 상태 관리 패턴과 비교했을 때 코드의 복잡성을 줄이며, 복잡한 상태 관리를 쉽게 구현할 수 있다는 점이 메리트가 있어 상태 관리 라이브러리로 Recoil을 선정하였습니다. |

| axios | styled components  |
| --- | --- |
| **Promise 기반의 좋은 호환성**<br> 요청과 응답 인터셉터, 취소 처리, 오류 처리 등 다양한 기능을 제공합니다.<br> Promise 기반 API로 비동기 코드 작성을 용이하게 해주기 때문에 axios로 선정하였습니다.| **CSS-in-JS**<br> Styled Components는 CSS를 JavaScript로 작성하는 방식으로,<br> 컴포넌트 스타일링을 쉽게 만들어줍니다.<br><br>**동적 스타일링**<br> 컴포넌트 스코프 스타일링을 통해 스타일 충돌 문제를 해결하고, <br>동적 스타일링을 쉽게 다룰 수 있다는 점이 큰 메리트라고 생각해 선정하였습니다. |


### ☁️ BackEnd

**MSA 선정 이유**
> 기존의 모놀리식 아키텍쳐는 애플리케이션이 모두 단일 프로젝트에 존재하여 단순하기 때문에 개발 속도가 빠르다. 또한 오류 시 문제가 발생한 위치를 식별하기 쉽고, 테스트 수행이 쉽다. 하지만 애플리케이션 규모가 크다면 관리가 어려울 수 있고 이 방식은 확장에 유연하지 않다.
<br>다른 다양한 기능 추가로 확장할 계획이 있고, 현재 기획단계의 애플리케이션 규모가 큰 ‘광장’ 에서는  복잡한 시스템 설계 및 관리가 필요하고 다른 서비스와 독립적으로 확장할 수 있는 MSA 구조를 채택하였다.
> 

| Spring Eureka | github actions |
| --- | --- |
| **서비스 디스커버리**<br> Spring Eureka는 마이크로서비스 간의 통신을 위해 서비스 디스커버리 기능을 제공한다. 이를 통해 서비스가 동적으로 등록되고 해지될 수 있으며, 클라이언트 애플리케이션은 Eureka 서버를 통해 서비스의 위치를 검색할 수 있습니다.<br><br> **로드 밸런싱**<br>Spring Eureka는 로드 밸런싱을 지원하여 여러 인스턴스 중 하나를 선택하여 요청을 분산시킬 수 있습니다. 이는 애플리케이션의 확장성과 가용성을 향상시키므로 Spring Eureka로 선정하였습니다. | **통합된 환경** <br> 다른 툴에 비해 리소스적 비용이 적고 GitHub와 완전히 통합되어 있어 이슈, 풀 리퀘스트 등 GitHub의 다른 기능과 원활하게 연동이 가능합니다.<br> <br>**이벤트 기반 워크플로우** <br> master 브랜치에 푸시했을 때 지정한 액션이 실행되도록 이벤트 기반 워크플로우를 지원. 이를 통해 자동화된 작업을 더욱 정확하게 제어하여 지속적 통합, 지속적 배포를 이룰 수 있기에 github actions 로 선정하였습니다. |

| Docker | Redis |
| --- | --- |
| **일관성**<br> 컨테이너는 환경을 패키지화하므로 개발, 테스트 및 프로덕션 환경 사이의 일관성을 유지하기가 더 쉽습니다. 동일한 컨테이너를 로컬 개발 환경에서 실행하고 프로덕션 서버에서 실행할 때 예상대로 동작합니다.<br> <br>**선언적 구성** <br>Docker Compose와 같은 도구를 사용하면 애플리케이션 구성을 선언적으로 정의할 수 있습니다. 이를 통해 환경 변수, 네트워킹, 볼륨 마운트 등을 쉽게 관리할 수 있어 Docker를 선정하였습니다. |**빠른 성능**<br> 인메모리 기반으로 빠른 응답 속도를 제공합니다.<br><br> **유연한 데이터 만료 관리**<br> 각 키에 대해 만료 시간을 설정할 수 있어, Refresh Token의 유효 기간 관리가 용이합니다. 따라서 Redis로 Refresh Token을 관리하기 위해 해당 기술을 선정하였습니다. |



## 🔖 Naming Rules

- 컴포넌트, 타입, 인터페이스, 생성자, 클래스 : PascalCase
- 메소드 & 파라미터 & 변수 : camelCase
- 상수 : SNAKE_CASE

## **🗂️ Commit Convetion**


### **📌 Type**

| commit명 | commit 규칙 |
| --- | --- |
| feat | 새로운 기능 추가 |
| fix | 버그 수정 혹은 기능 수정 |
| design | css 등 사용자 UI 디자인 추가 및 수정 |
| docs | 문서 추가 및 수정 |
| test | 테스트코드, 리팩토링 테스트 코드를 추가했을 때 |
| style | 코드 포맷팅, 세미콜론 누락, 코드 변경이 없이 추가 및 수정 |
| refactor | 코드 리펙토링 |
| build | 빌드 관련 파일 추가 및 수정 |
| rename | 파일 혹은 폴더명을 수정하거나 옮기는 작업만 수행 |
| remove | 파일을 삭제하는 작업만 수행 |
| chore | 그 외 자잘한 수정 |
- **commit message example**
    - feat : 작업 내용
    - fix : 작업 내용
    - chore :  …
- **커밋은 파일 단위로 작업한 내용 쪼개서 하기**
- 커밋메시지는 **영어로 작성**

## 👨🏻‍🎓 Branch 규칙


- 형식 `[Header]/[이슈 번호]/[이슈 작업 내용 요약]`
    - ex) `feat/#2/login`

| Header | 기능 |
| --- | --- |
| main | 최종 배포할 서비스 내용의 브랜치 |
| develop | 주요 개발 브랜치, 이 브랜치를 기준으로 각자 작업한 기능을 merge |
| feat | 기능 개발 브랜치, 기능 개발이 완료 시 develop 브랜치에 merge |
| fix | 기능 수정 브랜치, 이미 develop 브랜치에 merge된 기능을 수정하고 완료 시 develop 브랜치에 merge |
| hotfix | master 브랜치로 배포 후에 버그가 생겼을 때 긴급 수정하는 브랜치 |

## ⚽️ 이슈


- 이슈 제목 - feat : mainPage 수정
- 마일스톤 적용하기 (큰 작업 단위로 묶기)
- 템플릿 이용
    
    ```markdown
    ## 📌이슈 설명
    
    ## 🗒️투두리스트
    - [ ]
    - [ ]
    
    ## 👣참고사항
    ```
    
- 이슈 라벨
    - 😈 chaemin
    - 🤡 hoyeon
    - 🛠 feat
    - 🔨 fix
    - ⚙ chore
    - 🎨 design
    - 📄 docs
    - 💻 test
    - ⌨️ style
    - 📂 rename



## 👻 PR 규칙



- 템플릿 이용
    
    ```markdown
    ### 📝 Description
    이슈 번호 : #번호
    
    ### 💽 작업 내용
    - 1
    - 2
    
    ### 🖼 결과 (사진 및 작업 결과)
    ```
    
    - 이슈 번호
    - 작업 내용
    - 결과 (사진 및 작업 결과)
- pr 타이틀 - feat : mainPage 수정 (이슈제목과 동일하게)
    - ex) 브랜치 이름이 feat/#42/mainpage → pr제목 (feat : 메인페이지 구현)



## 🎃 directory 구조 (src 아래)


### 🌿 FrontEnd

**Atomic Design 패턴** 

> 컴포넌트 재사용을 높이고자, 아토믹 디자인 패턴 도입
> props drilling 최소화하고자, templates 단계 제거 및 상태관리 recoil 도입 <br>
![스크린샷 2023-10-13 오전 1 12 12](https://github.com/kusitms-28th-Meetup-E/.github/assets/53565255/defe8cd1-a7bc-4e5b-9157-1cef90f795a6)


```
┌── node_modules
├── src
│   ├── apis
│   ├── assets
│   ├── components
│   │   └── atoms
│   │   └── molecules
│   │   └── organisms
│   ├── stories
│   ├── 
│   ├── pages
└───└── router
├── app.tsx
├── main.tsx
├── index.html
├── package.json
├── tsconfig.json
├── eslint.json
└── webpack.config.ts
```

### ☁️ BackEnd

**DDD 패턴**

```
┌── api-gateway
├── service1
│   ├── src
│   │   ├── main
│   │   │   ├── java.com.gwangjang.backend
│   │   │   │   ├── domain
│   │   │	  │		│  ├── service1
│   │   │   │	  │	 │   ├── application
│   │   │   │   │	 │	 │   └── dto
│   │   │   │   │	 │	 │   └── mapper
│   │   │   │   │	 │	 │   └── service
│   │   │   │	  │	 │   ├── domain
│   │   │   │   │	 │	 │   └── entity
│   │   │   │   │	 │	 │   └── repository
│   │   │   │   │	 │	 │   └── service
│   │   │   │	  │	 │   ├── exception
│   │   │   │   │	 │	 │   └── exception
│   │   │   │	  │	 │   └── presentation
│   │   │   │   │	 │	     └── controller
│   │   │   │   │	 │	     └── mapper
│   │   │   │   │	 │	     └── service
│   │   │   │   ├── global
│   │   │   │   └── BackendApplication
│   │   │   ├── resources
│   │   └── test
│   ├── build.gradle
│   ├── Dockerfile
│   ├── settings.gradle
│   ├── gradlew
│   └── gradlew.bat
└─── service2
└─── service3
└─── service4
```

## **🐬 Git Flow**

![gitflow](https://github.com/kusitms-28th-Meetup-E/.github/assets/53565255/e5bdafb5-435e-4625-91d2-0d2796296608)



