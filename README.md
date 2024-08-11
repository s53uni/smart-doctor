<a name="top"></a>

# Clova Studio를 활용한 AI 기반 스마트 닥터 서비스
🏆 BDIA Hackathon 네이버클라우드 트랙상 수상 🏆
- 구분: 팀 프로젝트
- 기간: 2023년 12월 9일 ~ 2023년 12월 10일

<details>
  <summary>Table of Contents</summary>
  
  1. [프로젝트 팀원](#프로젝트-팀원)
  2. [프로젝트 개요](#프로젝트-개요)
  3. [사용 기술](#사용-기술)
  4. [개발 방법](#개발-방법)
      * [AI 진단 서비스](#ai-진단-서비스)
      * [맞춤형 질병 예측 서비스](#맞춤형-질병-예측-서비스)
  5. [서비스 소개](#서비스-소개)

</details>
<br>

![발표자료](https://github.com/user-attachments/assets/7791ff2c-c291-48a9-a8e5-5f16d2541783)

<br>

## 프로젝트 팀원

<table>
    <tr align="center">
        <td style="width:300px;"><a href="https://github.com/xx-Sommer-xx"><b>김소연</b></a></td>
        <td style="width:300px;"><a href="https://github.com/saeuggang10"><b>강민지</b></a></td>
        <td style="width:300px;"><a href="https://github.com/s53uni"><b>박시윤</b></a></td>
        <td style="width:300px;"><a href="https://github.com/Erin-53"><b>최예진</b></a></td>
    </tr>
    <tr align="center">
        <td>BE 개발<br>질병 예측 모델</td>
        <td>데이터 가공<br>질병 예측 모델</td>
        <td>FE/BE 개발<br>언어 모델 학습</td>
        <td>데이터 크롤링<br>질병 예측 모델</td>
    </tr>
</table>

<br>

## 프로젝트 개요
2022년 11월 17일에 발행된 ‘청년의사’ 기사에 따르면, 네이버 지식인 건강 관련 질문에 대한 답변 중 비전문가가 작성한 답변 비율이 43%에 달하며, 특히 작성된 답변의 50% 이상은 특별한 근거가 없는 것으로 나타났다. 
대다수의 사람들은 건강 이상 증세를 발견했을 때 검색 엔진을 통해 증상, 질환 내용 및 건강식품, 영양제 정보를 얻으려 하지만, 근거 없는 의학 정보나 과잉 진료와 관련된 데이터, 건강식품 광고를 접하는 경우가 많다.
<br><br>
이러한 문제점을 해결하기 위해 전문적인 의학 정보를 제공하고 사용자의 개별 특성 및 질병 히스토리를 고려한 질병 예측 정보와 질병 치료 정보를 제공하는 웹사이트를 구축하여, 
사람들이 보다 정확한 의학 및 질병 정보를 얻을 수 있게 한다.

<p align="right"><a href="#top">⬆️TOP</a></p>

## 사용 기술
### Back-End
* Django

### Front-End
* HTML5
* CSS3
* Javascript

<p align="right"><a href="#top">⬆️TOP</a></p>

## 개발 방법
### AI 진단 서비스
#### HyperCLOVA 프롬프트 튜닝
- 프롬프트를 '증상을 입력하면 자주 발생하는 질병 순으로 몇 가지를 제시하고 쉽게 설명해준 뒤 관련 진료과를 알려주는 형식'으로 설계
- 사용자 요청을 '너는 친절하고 똑똑한 의사야. 사용자가 증상을 입력하면, 그 증상과 관련된 가장 자주 발생하는 질병 몇 가지를 쉽게 풀어서 설명해줘. 마지막으로 관련 진료과도 안내해줘.'로 설정

#### HyperCLOVA 테스트 앱 생성
- 최대 토큰을 500으로 설정하고 챗 모드로 HyperCLOVA 엔진을 선택하여 테스트 앱 생성

#### 결과 출력 화면 구현
- Python으로는 대화형 화면을 성공적으로 구현했으나, 자바스크립트로 실행 시 콘솔 창에서 오류 발생
- 대화형 화면 구현은 실패했지만 출력 화면은 성공적으로 구현함

<br>

### 맞춤형 질병 예측 서비스



<p align="right"><a href="#top">⬆️TOP</a></p>


## 서비스 소개

![진단서비스](https://github.com/user-attachments/assets/7de3b3bb-3ebc-4b3c-85ea-d1a94df5d889)
![질병예측서비스](https://github.com/user-attachments/assets/0916f3be-e01e-43c4-bd4a-66eb6be29dac)

<p align="right"><a href="#top">⬆️TOP</a></p>







