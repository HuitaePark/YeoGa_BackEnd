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
  - [Prerequisites](#prerequisites)
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
*만약 운영체제에 따라 프로그램을 다르게 동작시켜야한다면, 운영체제별로 동작 방법을 설명하세요*

## Prerequisites
*프로젝트를 동작시키기 위해 필요한 소프트웨어와 라이브러리를 나열하고 어떻게 다운받을 수 있는지 설명하세요.*

- [OpenWeather API key](https://openweathermap.org/) (무료)
- npm
```bash
npm install npm@latest -g
```

## Installation
*어떻게 이 프로젝트의 소스코드를 다운받을 수 있는지 설명하세요.*
1. Repository 클론
```bash
git clone https://github.com/your-username/project-repository
```
2. NPM packages 설치
```bash
npm install
```

## Configuration
*코드의 어느 부분을 채우거나 수정해야하는지 설명하세요.*
- `config.js`에 Openweather API key를 입력
```bash
const API_KEY = "<Your API key>";
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
***유사한 프로젝트의 레포지토리** 혹은 **블로그 포스트** 등 프로젝트 구현에 영감을 준 출처에 대해 링크를 나열하세요.*

- [Readme Template - Embedded Artistry](https://embeddedartistry.com/blog/2017/11/30/embedded-artistry-readme-template/)
- [How to write a kickass Readme - James.Scott](https://dev.to/scottydocs/how-to-write-a-kickass-readme-5af9)
- [Best-README-Template - othneildrew](https://github.com/othneildrew/Best-README-Template#prerequisites)



# [6] Contact
- 📧 qkrgmlxo3174@gmail.com




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

