<div align="center">

# 안녕하세요, 플러터 풀스택 개발자 김민우입니다 👋

**앱을 만들고, 그 앱이 쓰는 서버까지 직접 만들어요**

실제로 쓰이는 프로젝트를 만들면서 배우고 있습니다 🌱

![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

</div>

<br>

## 🎧 대표 프로젝트 · PLIVIEW

> **듣고, 점수 주고, 같이 고르는 플리**
> Spotify의 곡 · 앨범 · 플레이리스트에 별점과 리뷰를 남기는 앱. **Flutter 앱 + Spring Boot 서버**를 함께 만들었어요.

<img src="https://raw.githubusercontent.com/minwoo0708/PLIVIEW_server/main/docs/design/overview.png" alt="PLIVIEW 앱 화면 디자인" width="100%">

<p align="center"><sub>PLIVIEW 앱 화면 디자인 (Figma)</sub></p>

| 저장소 | 역할 | 기술 |
|---|---|---|
| 📱 [**PLIVIEW_app**](https://github.com/minwoo0708/PLIVIEW_app) | 안드로이드 앱 + 웹 (Flutter 하나로) | Flutter · Dart · Riverpod · Dio · PKCE 로그인 |
| 🍃 [**PLIVIEW_server**](https://github.com/minwoo0708/PLIVIEW_server) | REST API 29개 · 회원 · 리뷰 · 통계 · Spotify 연동 | Java 21 · Spring Boot 4 · Security(JWT) · JPA · MySQL · Flyway |

**만들면서 신경 쓴 것**
- 🔐 이메일 회원가입·로그인(JWT, BCrypt)과 리뷰 CRUD, 별점 분포·평균·랭킹 같은 **통계 API**
- 🎧 **Spotify Web API**를 서버가 대신 조회하고(응답 캐시 · 사용자별 요청 제한), 사용자 계정 연동은 앱이 PKCE로 처리
- 🗄 DB 변경 이력을 **Flyway**로 관리하고, **MockMvc 통합 테스트 68개**로 검증
- 🎨 Figma 디자인을 보고 화면을 구현하고, 서버와 앱을 오가며 API를 맞춰 갔어요

<br>

## 🧰 Tech Stack

**Mobile · Web**<br>
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white)

**Backend**<br>
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring%20Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Flyway](https://img.shields.io/badge/Flyway-CC0200?style=flat-square&logo=flyway&logoColor=white)
![Gradle](https://img.shields.io/badge/Gradle-02303A?style=flat-square&logo=gradle&logoColor=white)

**Others**<br>
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

**Tools**<br>
![Android Studio](https://img.shields.io/badge/Android%20Studio-3DDC84?style=flat-square&logo=androidstudio&logoColor=white)
![IntelliJ IDEA](https://img.shields.io/badge/IntelliJ%20IDEA-000000?style=flat-square&logo=intellijidea&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white)

<br>



<br>

<div align="center">

⭐ 구경해 주셔서 감사합니다 ⭐

</div>
