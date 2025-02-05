> # 숙소기반 여행 코스추천 웹 여행을가요(A.K.A 여가) 

<img src="https://github.com/user-attachments/assets/885b79f2-188b-4f76-a1f2-5b28d0c50dcf" 
     alt="logo1" 
     style="width:30%; border: 2px solid #eee;" />

<!--목차-->
# Table of Contents
- [[1] About the Project](#1-about-the-project)
  - [Features](#features)
  - [Technologies](#technologies)
- [[2] Getting Started](#2-getting-started)
  - [Installation](#installation)
  - [Configuration](#configuration)
- [[3] Usage](#3-usage)
- [[4] Contribution](#4-contribution)
- [[5] Acknowledgement](#5-acknowledgement)
- [[6] Contact](#6-contact)



# [1] About the Project

>우리는 여행 코스를 계획할때 많은 고민을 하게 됩니다.<br>
>어디 지역으로 여행을 가겠다고 정하면 숙소부터 시작해서 근처에는 어떤 관광명소가 있는지,어떤 먹을거리가 있는지 열심히 조사를 하게 됩니다.<br>
>저희는 이런 고민거리를 타파하고자 **여가**를 만들어 숙소 추천을 받거나 숙소만 정했다면 그 근처에 무엇이 있는지 추천을 해주는 사이트를 만들었습니다.

## Features

여가는 한국관광공사API를 활용하여 숙소와 여행지 코스, 날씨등의 데이터를 받아와 활용하였습니다.<br>
또한 카카오지도API도 사용하여 코스를 추천 받았을 경우, 코스에 대한 이동경로를 지도에 표시하여 사용자가 코스이동을 어떻게 이동할지에 대해 도움을 주도록 노력하였습니다.

## Technologies

<img width="725" alt="image" src="https://github.com/user-attachments/assets/6cb20d4b-8fd0-44af-aa6a-518cbe027db0" />


# [2] Getting Started
*백엔드 기준 설명입니다.*

## Installation
1. Repository 클론
```bash
git clone https://github.com/TravelMaker-DMU/YeoGa_BackEnd.git
```
2. 각자 ide 실행

## Configuration
- `application.properties`에 각자 API키를 입력
```bash
spring.datasource.driver-class-name=org.mariadb.jdbc.Driver
spring.datasource.url=jdbc:mariadb://${MYSQL_HOST}:${MYSQL_PORT}/${DATA_BASE_NAME}?useSSL=false&useUnicode=true&serverTimezone=Asia/Seoul&allowPublicKeyRetrieval=true
spring.datasource.username=${DB_username}
spring.datasource.password=${DB_password}

spring.jwt.secret=${JWT_secret}

spring.profiles.active=${profile}

tour.api.key=${TOUR_API_KEY}
tour.api.base-url=${TOUR_API_BASE_URL}

tour_course.api.key=${TOUR_COURSE_API_KEY}
tour_course.api.base-url=${TOUR_COURSE_API_BASE_URL}

trip_news.api.key=${TRIP_NEWS_API_KEY}
trip_news.api.base-url=${TRIP_NEWS_API_BASE_URL}

vworld.api.key=${VWORLD_API_KEY}
vworld.api.base-url=${VWORLD_API_BASE_URL}

kakao.api.key=${KAKAO_API_KEY}
kakao.api.base-url=${KAKAO_API_BASE_URL}


google.api.key=${GOOGLE_API_KEY}
google.api.base-url=${GOOGLE_API_BASE_URL}

#registration
spring.security.oauth2.client.registration.naver.client-name=naver
spring.security.oauth2.client.registration.naver.client-id=${NAVER_CLIENT_ID}
spring.security.oauth2.client.registration.naver.client-secret=${NAVER_CLIENT_SECRET}
spring.security.oauth2.client.registration.naver.redirect-uri=${NAVER_REDIRECT_URI}
spring.security.oauth2.client.registration.naver.authorization-grant-type=authorization_code
spring.security.oauth2.client.registration.naver.scope=name,email

#provider
spring.security.oauth2.client.provider.naver.authorization-uri=https://nid.naver.com/oauth2.0/authorize
spring.security.oauth2.client.provider.naver.token-uri=https://nid.naver.com/oauth2.0/token
spring.security.oauth2.client.provider.naver.user-info-uri=https://openapi.naver.com/v1/nid/me
spring.security.oauth2.client.provider.naver.user-name-attribute=response


#registration
spring.security.oauth2.client.registration.google.client-name=google
spring.security.oauth2.client.registration.google.client-id=${GOOGLE_CLIENT_ID}
spring.security.oauth2.client.registration.google.client-secret=${GOOGLE_CLIENT_SECRET}
spring.security.oauth2.client.registration.google.redirect-uri=${GOOGLE_REDIRECT_URI}
spring.security.oauth2.client.registration.google.authorization-grant-type=authorization_code
spring.security.oauth2.client.registration.google.scope=profile,email
```



# [3] Usage

<h2>로그인 화면</h2>

![readme3](https://github.com/user-attachments/assets/5a090074-86c3-4c76-8880-8cf986886ac0)

<h2>회원가입 화면</h2>

![readme4](https://github.com/user-attachments/assets/95c14ffb-8900-4d3c-a611-8f3b83217124)

<h2>메인 화면(여행지 추천 부분)</h2>

![image](https://github.com/user-attachments/assets/0e5fe0a1-cc4b-4da4-afcd-7b230b6e11b6)
<h2>메인 화면(여행코스와 숙소 추천 부분)</h2>

<img width="486" alt="그림1" src="https://github.com/user-attachments/assets/a94c7466-6ac7-4165-8e15-3dd5791bfce5" />

<h2>여행 코스 추천 상세페이지</h2>

![readme](https://github.com/user-attachments/assets/058876c9-f4da-4718-9312-263c49530f81)


<h2></h2>

# [4] Contribution



# [5] Acknowledgement

- [여행 플래너 사이트 MYRO](https://www.myro.co.kr/)
- [How to write a kickass Readme - James.Scott](https://dev.to/scottydocs/how-to-write-a-kickass-readme-5af9)
- [Best-README-Template - othneildrew](https://github.com/othneildrew/Best-README-Template#prerequisites)



# [6] Contact
- 📧 qkrgmlxo3174@gmail.com


# [7] 아쉬운점

> 스프링으로 뭔가를 만들어본 첫 프로젝트이기도 하고 한국관광공사 API에서 모든걸 제공해주는줄 알고
> 비즈니스 로직은 외부 API로 받고 나머지 기능을 만드는 방향으로 프로젝트를 진행했습니다.
> 하지만 외부API는 저희가 원하는대로 데이터 가공도 안되어있고 문서도 제대로 작성이 안되어있어 불편한점이 많았습니다.
> 기회가 된다면 한국관광공사가 제공해주는 데이터만으로 비즈니스로직 API를 다시만들어 리펙토링해보고 싶습니다.

<!--Url for Badges-->
[license-shield]: https://img.shields.io/github/license/dev-ujin/readme-template?labelColor=D8D8D8&color=04B4AE
[repository-size-shield]: https://img.shields.io/github/repo-size/dev-ujin/readme-template?labelColor=D8D8D8&color=BE81F7
[issue-closed-shield]: https://img.shields.io/github/issues-closed/dev-ujin/readme-template?labelColor=D8D8D8&color=FE9A2E

<!--Url for Buttons-->
[readme-eng-shield]: https://img.shields.io/badge/-readme%20in%20english-2E2E2E?style=for-the-badge
[view-demo-shield]: https://img.shields.io/badge/-%F0%9F%98%8E%20view%20demo-F3F781?style=for-the-badge
[view-demo-url]: https://dev-ujin.github.io
[report-bug-shield]: https://img.shields.io/badge/-%F0%9F%90%9E%20report%20bug-F5A9A9?style=for-the-badge
[report-bug-url]: https://github.com/dev-ujin/readme-template/issues
[request-feature-shield]: https://img.shields.io/badge/-%E2%9C%A8%20request%20feature-A9D0F5?style=for-the-badge
[request-feature-url]: https://github.com/dev-ujin/readme-template/issues

<!--URLS-->
[license-url]: LICENSE.md
[contribution-url]: CONTRIBUTION.md
[readme-eng-url]: ../README.md

