# nuxt-shopping

## 프로젝트 소개
Nuxt Shopping 프로젝트 입니다.

> 해당 글의 내용은 [인프런] Nuxt.js 시작하기 강의를 토대로 만들어졌습니다.

### 배포 
 
SSR 배포 URL : https://nuxt-shopping-app1.herokuapp.com/
SSG 배포 URL : https://eager-allen-454cbc.netlify.app/

<br />


## 프로젝트 설치 및 실행

```bash
# 설치 
$ npm install

# 개발 모드 실행
$ npm run dev

# server모드 배포 및 실행
$ npm run build
$ npm run start

# static 모드 배포
$ npm run generate
```


## 폴더 구조 설명

```
.
├── api : api 함수들이 있는 폴더
├── assets : 기타 자원 폴더
├── backend : server 폴더
├── components : 컴포넌트 폴더
├── layouts : page 컴포넌트의 상위 폴더로 페이지의 공통 레이아웃 파일들
│   ├── default.vue
│   └── error.vue
├── nuxt.config.js : nuxt 기본 셋팅
├── package.json : 프로젝트 및 패키지 정보
├── pages : page 컴포넌트로 자동 라우팅이 되는 폴더
│   ├── cart.vue
│   ├── detail
│   │   └── _id.vue
│   ├── index.vue
│   └── product.vue
├── static : 정적 자원 폴더
└── store : vuex 저장소

```

## 브랜치 설명
  - master
  - develop : 개발 브랜치(기본)
  - deploy/heroku : SSR 모드 배포 브랜치 
  - deploy/netlify : SSG 모드 배포 브랜치
