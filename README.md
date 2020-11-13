# 리액트를 다루는 기술

## 이번 챕터의 최종목표

- newsapi.org의 newsAPI를 이용한 news viewer 만들기

  - 책의 코드대로 만들지 않고 나만의 방식으로 똑같이 구현

- md 파일 작성법도 함께 터득하기

## Part.0

- `axios` : 현재 가장 많이 사용되는 자바스크립트 HTTP 클라이언트
  - HTTP 요청을 Promise 기반으로 처리한다.

## Part.1

- newsapi.org 사용법

  - https://newsapi.org/s/south-korea-news-api

- `.env` 파일
  - newsapi.org의 API Key를 숨기기 위해 작성
  - REACT_APP_API_KEY=key
  - 사용 : process.env.REACT_APP_API_KEY
  - 참고 : https://syki66.github.io/blog/2020/02/23/git-hide-apikey.html

## Part.2

- UI 구성
  - 책에서는 styled-components를 사용했기 때문에 복습하는 겸 따라치기
