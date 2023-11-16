# HSTACK (황스택)

> 2021.06 ~ 2022.12 <br/>
> 한성대학교 컴퓨터공학부 학생으로 이뤄진 프로젝트 팀입니다.

<br/>
<br/>

## 👩 팀원

| 이름 | 소속 (`22기준) | github | email |
| --- | --- | --- | --- |
| 조민화 | 한성대학교 컴퓨터공학부 |[@MinhwaCho](https://github.com/MinhwaCho) | dianne11161@gmail.com |
| 김다연 | 한성대학교 컴퓨터공학부 | [@DayeonKim](https://github.com/yeondelight) | hihi5v@naver.com |
| 오하늘 | 한성대학교 컴퓨터공학부 | [@HaneulOh](https://github.com/haneul5) | okk0719@naver.com |
| 이선영 | 한성대학교 컴퓨터공학부 | [@SunyoungLee](https://github.com/hs-1891265-sunyounglee) | 4446207@naver.com |
| 이화랑 | 한성대학교 컴퓨터공학부 | [@HwarangLee](https://github.com/Lee-Hwarang) | ghk2684@naver.com |

<br/>
<br/>
<br/>

## 🏆 수상 내역

| 21st NEA OSS Promotion forum <br/> Outstanding Technologies Project Award | '22 제 16회 공개SW 개발자대회 <br/> 과학기술정보통신부 장관상 <br/> (학생부문 대상, 1위) | '22 한성대학교 컴퓨터공학부 <br/> 캡스톤디자인 작품 발표회 <br/>모바일분야 최우수상 (1위) | '22 1학기 한성대학교 <br/> 창의융합성과 경진대회 (C&C Festival) <br/> 금상 (2위)  |
| --- | --- | --- | --- |
| --- | <img src="https://user-images.githubusercontent.com/73868349/205923726-77bf0d71-0c73-42a5-a647-205d4e834b65.jpg" alt="공개SW개발자대회_과기부장관상_황스택" width = "500"/> | <img src="https://user-images.githubusercontent.com/73868349/187857473-778ddd63-96d4-4bc7-98ac-e1ce692a7239.jpg" alt="22캡스톤" width = "500"/> | <img src="https://user-images.githubusercontent.com/73868349/202950859-4cfeaa4d-7d1e-4ed7-ac8f-be85c7b1811b.jpg" alt="22C&C" width = "500"/> |


| 한성대학교 <br/> 제 18회 한성공학경진대회 <br/> 작품부문 대상 (1위) | 한성대학교 <br/> 제 18회 한성공학경진대회 <br/> 특허부문 금상 (1위) | 한성대학교 <br/> 제 17회 한성공학경진대회 <br/> 작품부문 금상 (2위) | 한성대학교 <br/> 제 17회 한성공학경진대회 <br/> 특허부문 동상 (3위) |
| --- | --- | --- | --- |
| <img src="https://user-images.githubusercontent.com/73868349/202950862-78e46386-18f2-45f8-ac3d-c9fcf8935cc4.jpg" alt="22공경진_대상" width = "500"/> | <img src="https://user-images.githubusercontent.com/73868349/202950863-fd5eb36f-9b12-49af-8b01-a4d8c22b0994.jpg" alt="22공경진_금상" width = "500"/> | <img src="https://user-images.githubusercontent.com/73868349/187857608-bcec835a-76bb-4b24-ac3f-94292126b639.jpg" alt="21공경진_금상" width = "500"/> | <img src="https://user-images.githubusercontent.com/73868349/187857543-cfef093d-e940-4810-8463-c7f7a267d05a.jpg" alt="21공경진_동상" width = "500"/> |

<br/>
<br/>
<br/>


## ⚙ Repository

- **검색 가능한 비디오 플레이어 (Timestamp Finder / Video Searcher)**
    
    [<img src="https://user-images.githubusercontent.com/73868349/187857334-510a3c9f-5667-46f8-bbd3-a80be5d59d63.jpg" alt="VideoSearcher"
 width = "480" height="270" />](https://github.com/HSTACK-2022/VideoSearcher)
    
    > Timestamp Finder(구 Video Searcher)는 영상 내 <b>키워드와 이미지를 바탕으로 한 검색</b> 시스템을 구축해<br/>
    > 사용자에게 효율적인 영상 시청을 제공하는 <b>Android Application</b>입니다.

    
    - 개발 기간 : 2021.06 ~ 2021.09
    - 핵심 기술
        - FFmpeg과 ETRI STT API를 이용한 영상의 스크립트 추출
        - OpenCV를 활용한 영상 내 장면 변화 감지 및 추출
        
<br/>

- **영상의 풍부한 메타데이터 자동 구축 및 효과적인 검색, 재생 시스템 (VMeta, VideoMetaSystem)**
    
    [<img src="https://user-images.githubusercontent.com/73868349/171586152-85d907ca-51e4-4186-998c-c3c808e651e2.jpg" alt="VMeta"
 width = "480" height="270" />](https://github.com/HSTACK-2022/VideoMetaSystem)
    
    > Video Meta System (이하 VMeta)는 <b>영상의 메타데이터를 자동으로 구축</b>해<br/>
    > 사용자에게 세밀하고 용이한 검색을 가능하게 하는 시스템입니다.
    
    
    - 개발 기간 : 2022.01 ~ 2022.11
    - 핵심 기술
        - MySQL로 메타데이터 관리가 가능한 Flask 서버
        - Tensorflow의 Keras와 OpenCV, FFmpeg 등 다양한 기술을 활용해 풍부한 메타데이터를 생성
        - HTML, CSS, Javascript를 이용한 웹 홈페이지 제작
        - 직접 개발한 Deep Rank 알고리즘을 활용하여 영상 검색의 정확도 향상
