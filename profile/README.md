


# Memoraize

<div align = "center">
<img width="560" alt="image" src="https://github.com/junhaa/study/blob/main/image/project/memoraize/memoraizeLogo.png?raw=true">
</div>

<br>

<div align = center>
<b>여행 앨범 자동 생성 커뮤니티 서비스, Memoraize</b>
</div>



## 팀원 소개

<br>

> 2024 한성대학교 캡스톤디자인
> <br>
> 개발기간: 2024.01 ~ 2024.07

<br>

|                                        이나경                                        |                                        김진하                                        |                                       김준하                                       |                                       양윤석                                        |
| :-------------------------------------------------------------------------------: | :-------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------: | :------------------------------------------------------------------------------: |
| <img width="160px" src="https://avatars.githubusercontent.com/u/115490634?v=4" /> | <img width="160px" src="https://avatars.githubusercontent.com/u/121429925?v=4" /> | <img width="160px" src="https://avatars.githubusercontent.com/u/94986147?v=4"/> | <img width="160px" src="https://avatars.githubusercontent.com/u/115922214?v=4"/> |
|                  [@Na.\_.kyung](https://github.com/lee-nakyung)                   |                    [@Jinha Kim](https://github.com/ghvfgfcht)                     |                      [@junhaa](https://github.com/junhaa)                       |      [@hs_1991317_YoonseokYang](https://github.com/hs-1991317-YoonseokYang)      |
|                                     프론트엔드 개발                                      |                                     백엔드 서버 개발                                     |                                    백엔드 서버 개발                                    |                                    백엔드 서버 개발                                     |


<br>

## 프로젝트 소개
<br>
MemorAIze는 사용자가 여행의 순간을 담은 사진들을 업로드하면, AI를 이용하여 사진의 해시태그를 추출하고 이 해시태그를 통해 특색있는 여행앨범을 생성합니다. 앨범에는 사진에서 추출한 위치 및 시간 데이터를 통해 사용자의 여행 일정이 일별로 기록되어있고, 이 정보가 지도 위에 표시됩니다. 앨범은 다른 사용자들과 공유할 수 있으며 사용자는 방문한 장소에 대해 리뷰를 작성할 수 있습니다. 이를 통해 사용자는 여행의 추억을 효과적으로 기록하고, 다른 사용자들에게 생생한 정보를 공유할 수 있습니다.

<br>

## 주요 기능 


### ✅ 여행 앨범 자동 생성
- AI를 이용한 사진의 제목, 상세 내용 자동 작성
- AI가 사진을 인식하여 단어 태그 자동 생성
- 사진의 메타데이터를 추출하여 사진 촬영 시각, 위치 정보를 저장
- 사진의 전반적인 색상을 추출하여, 사진에 어울리는 색상을 배경으로 적용
- 사용자의 음성을 업로드 시, 사진의 상세 내용을 사용자의 목소리로 합성하여 재생 가능

### ✅ 사용자의 앨범 저장 기능
- 앨범 내부 사진들의 위치 메타데이터 정보를 이용하여 사용자의 여행 이동 경로를 지도에 표기
- 여러 사진 앨범들을 분류 및 저장 가능
- 앨범 전체 사진 내용을 간단한 슬라이드 쇼로 보여주는 기능 제공

### ✅ 장소 데이터 저장
* 앨범의 사진에 대한 장소 데이터를 따로 저장
* 사진 촬영 장소의 메타데이터를 추출하여, 촬영 장소에 대한 리뷰 작성 가능
* Google Map을 통해 위치와 Google Map에서 제공하는 리뷰 확인 가능

### ✅ 커뮤니티 기능 제공
* 사용자 마이페이지를 제공하여 사용자가 생성한 앨범, 리뷰 확인 가능
* 사용자는 자신의 앨범을 공개 할 수 있어, 다른 사용자에게 자신의 앨범을 공유 가능
* 팔로우, 팔로잉 시스템을 이용하여 다른 사용자의 페이지를 쉽게 열람할 수 있음
* 통합 검색 기능을 제공하여 사용자, 앨범, 장소, 태그 별 검색 가능



## 구현 화면

|                                                              메인 페이지                                                               |                                                            앨범 목록 페이지                                                             |
| :-------------------------------------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------------------------------: |
| <img width="400" alt="image" src="https://github.com/junhaa/study/blob/main/image/project/memoraize/memoraize_main.png?raw=true"> | <br><img width="500" src="https://github.com/junhaa/study/blob/main/image/project/memoraize/memoraize_album_list.png?raw=true"/> |
|                                                              앨범 페이지                                                               |                                                            사진 상세 페이지                                                             |
|<img width="300" src="https://github.com/junhaa/study/blob/main/image/project/memoraize/memoraize_photo_list.png?raw=true"/> |<img width="500" src="https://github.com/junhaa/study/blob/main/image/project/memoraize/memoraize_album.png?raw=true"/>|
|통합 검색 페이지| 사용자 마이페이지|
|<img width="500" src="https://github.com/junhaa/study/blob/main/image/project/memoraize/memoraize_search.png?raw=true"/>|<br><img width="500" src="https://github.com/junhaa/study/blob/main/image/project/memoraize/memoraize_mypage.png?raw=true"/> |

---
## 시작 가이드

### Front-End
```bash
$ git clone https://github.com/MemorAIzee/MemorAIzee-Frontend.git
$ cd MemorAIzee-Frontend/
$ npm install 
$ npm start
```

### Back-End
```bash
$ git clone https://github.com/MemorAIzee/MemorAIzee-BackEnd.git
$ cd MemorAIzee-BackEnd/
$ ./gradlew build -x test
$ java -jar ./build/libs/memoraize-0.0.1-SNAPSHOT.jar
```

---

## 사용된 기술

### Front-End
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=Javascript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)

### Back-End
![Mysql](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=MySQL&logoColor=white)
![Spring](https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=Spring&logoColor=white)
![AWS](https://img.shields.io/badge/Amazon%20AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)

### Tools
![Notion](https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=Notion&logoColor=white)
![Github](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=GitHub&logoColor=white)             

---
<br><br>
<div align=center>
<img width="700px" src="https://github.com/junhaa/study/blob/main/image/project/memoraize/memoraize_panel.jpg?raw=true" />
</div>
