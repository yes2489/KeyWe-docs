# 🥝 KeyWe - 시니어를 위한 원격 키오스크 주문 지원 플랫폼
<img alt="KeyWeLanding" src="/assets/keywe_landing.png">

## 📅 프로젝트 정보
- **기간**: 2025.01.06 ~ 2025.02.21 (7주)
- **참여 인원**: 6명 (FrontEnd 3 / BackEnd 3)
- **SSAFY**: 삼성 청년 SW 아카데미 12기 공통 프로젝트

## 📝 프로젝트 개요
KeyWe는 키오스크 사용이 어려운 **시니어**를 위해 **자녀 등 측근이 원격으로 키오스크 주문을 도와주는 서비스**입니다.  
디지털 소외 문제를 해결하고, 가족 간 연결을 강화하며, 매장 입장에서는 고객 만족도와 매출 증대를 기대할 수 있습니다.

## 🎯 목표
- **디지털 소외 해소**: 시니어가 키오스크에서 도움을 요청하면 자녀가 원격으로 주문을 지원
- **안전한 원격 주문**: 키오스크와 앱 화면을 실시간으로 동기화, 원활한 주문 환경 제공
- **매장 효율성 향상**: 주문 시스템을 통해 고객 만족과 매출 증가

## ✨ 주요 기능
| 기능                | 설명                                                                                       |
|--------------------|------------------------------------------------------------------------------------------|
| 🧓 시니어 대리 주문 요청 | 키오스크에서 "대리 주문" 선택 → 본인 휴대폰 번호 입력 → 자녀에게 원격 주문 요청 푸시 알림 발송             |
| 📱 자녀 원격 주문 지원   | 자녀는 앱에서 요청 수락 후 키오스크와 실시간 연동 화면을 통해 주문 진행, 필요 시 음성 통화 지원                  |
| 🏪 매장 관리자 메뉴 관리 | 매장 관리자는 키오스크에 등록된 메뉴와 카테고리를 손쉽게 추가, 수정, 삭제 가능                                     |
| 🛒 주문 및 장바구니 기능  | 카테고리, 메뉴 조회 → 옵션 선택 → 장바구니 담기 및 주문 진행, 주문 내역 조회 및 취소 가능                        |
| 👨‍👩‍👧 가족 프로필 관리   | 자녀 계정에서 부모님(시니어) 프로필을 다수 등록 가능, 가족 관계에 따라 차별화된 권한 및 기능 제공                  |
| 🔒 인증 및 보안 강화     | 이메일, 휴대폰 인증 및 JWT 기반 인증 체계, SMS 인증 시스템으로 보안 강화                                           |

## 📊 주요 화면

### 🧓 시니어 키오스크 대리 주문 요청
키오스크에서 시니어가 대리 주문을 요청하는 화면입니다.   
<img alt="시니어 대리 주문 요청" src="/assets/preview_parents.gif" width="350" height="750">

### 📱 자녀 원격 주문 진행
자녀가 원격으로 키오스크와 연동된 화면을 통해 주문을 지원하는 화면입니다.   
<img alt="자녀 원격 주문" src="/assets/preview_child.gif" width="350" height="750">

### 🏪 원격 주문 진행 시 키오스크 화면
자녀와 매칭된 후 매장 키오스크에서 보이는 화면입니다.  
<img alt="키오스크 화면" src="/assets/parents_menu.jpg" width="350" height="750">

## 🌐 서비스 구조
<img alt="서비스 아키텍처" src="/assets/service_architecture_keywe.png" width="700">

## 🏆 기대 효과
- **디지털 소외 해소**: 시니어가 독립적으로 외출하고 주문할 수 있는 환경 조성
- **가족 간 연결 강화**: 바쁜 자녀도 원격으로 부모님을 지원
- **매장 운영 효율화**: 고객 만족도 향상 및 매출 증가

## 🛠️ 기술 스택

| 영역         | 기술 |
|:------------:|:----|
| **Frontend** | ![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white) ![Jetpack Compose](https://img.shields.io/badge/Jetpack%20Compose-4285F4?style=for-the-badge&logo=jetpackcompose&logoColor=white) |
| **Backend**  | ![Java](https://img.shields.io/badge/Java%2017-007396?style=for-the-badge&logo=openjdk&logoColor=white) ![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white) ![JPA](https://img.shields.io/badge/JPA-59666C?style=for-the-badge&logo=hibernate&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white) ![Kafka](https://img.shields.io/badge/Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white) |
| **DevOps**   | ![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white) ![AWS EC2](https://img.shields.io/badge/AWS%20EC2-FF9900?style=for-the-badge&logo=amazonec2&logoColor=white) ![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white) |
| **협업 도구**| ![Jira](https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=jira&logoColor=white) ![GitLab](https://img.shields.io/badge/GitLab-fc6d26?style=for-the-badge&logo=gitlab&logoColor=white) ![Notion](https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=notion&logoColor=white) |

## 👥 팀원 소개

| <img alt="profile" src ="https://github.com/csct3434.png" width ="100px"> | <img alt="profile" src ="https://github.com/Bheinarl.png" width ="100px"> | <img alt="profile" src ="https://github.com/invent819.png" width ="100px"> | <img alt="profile" src ="https://github.com/hiheesoo.png" width ="100px"> | <img alt="profile" src ="https://github.com/jungchanSon.png" width ="100px"> | <img alt="profile" src ="https://github.com/yes2489.png" width ="100px"> |
| :-----------------------------------------------------------------------: | :-----------------------------------------------------------------------: | :-----------------------------------------------------------------------: | :-----------------------------------------------------------------------: | :-----------------------------------------------------------------------: | :-----------------------------------------------------------------------: |
| 김동철 (팀장)                                                              | 곽동연                                                                      | 김정현                                                                      | 변희수                                                                      |  손정찬                                                                      | 양은서                                                                      |
| [csct3434](https://github.com/csct3434)                                     | [Bheinarl](https://github.com/Bheinarl)                                     | [invent819](https://github.com/invent819)                                     | [gmltn0907](https://github.com/hiheesoo)                                     | [jungchanSon](https://github.com/jungchanSon)                                     | [yes2489](https://github.com/yes2489)                                     |
| BE                                                                     | AOS                                                                     | AOS                                                                     | AOS                                                                     | BE                                                                     | BE                                                                     |

## 📝 라이선스
MIT License

