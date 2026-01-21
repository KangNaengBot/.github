# 🌽 KangNaengBot  
강남대학교 학생을 위한 AI 캠퍼스 어시스턴트

KangNaengBot은 강남대학교 학생들이 자주 겪는  
**학사 정보 탐색, 졸업요건 확인, 수강신청, 시간표 구성**의 불편함을 해결하기 위해 개발된  
대화형 AI 캠퍼스 도우미입니다.

복잡한 학사 정보는 간단하게 정리하고,  
흩어져 있는 학교 정보는 하나로 통합하여,  
검색이 아닌 **대화 기반 인터페이스**로 제공합니다.

---

## 🌽 Core Features

### 🌽 학교 정보 통합 제공
- 졸업요건, 학과·조직 정보, 학사일정, 수강신청 가이드 통합 제공
- 여러 시스템을 오갈 필요 없이 한 곳에서 확인 가능
- 학교 관련 정보 탐색 비용 최소화

---

### 🌽 질문 의도 자동 파악
- 질문이 불완전하거나 애매해도 의도를 분석해 응답
- 추가 설명 없이도 필요한 정보 자동 보완
- 사용자 입력 부담 최소화

---

### 🌽 실시간 정보 응답
- 현재 시각, 날짜, 요일 즉시 제공
- 한국 표준시(KST) 기준 서버 시간 사용
- 기본적인 실시간 유틸리티 기능 지원

---

## 🌽 Graduation Requirement Assistant

- 2021 ~ 2024학번 및 2025학번 이후 졸업요건 모두 반영
- 전공·교양 학점, 필수 이수 조건, 졸업 인증 요건 통합 안내
- 입학년도나 전공 정보가 누락되어도 자동 보완

**Example**
> 소프트웨어전공 졸업요건 알려줘

---

## 🌽 Department & Organization Search

- 학교 조직도 기반 데이터 제공
- 학과 / 학부 / 단과대학 정보 조회
- 학부장, 학과장, 주임교수 정보 제공
- 교학팀 위치 및 담당 부서 안내
- 교학팀 전화번호 확인 가능

**Example**
> 컴퓨터공학부 학부장 누구야?  
> 복지융합대학 교학팀 어디 있어?  
> 교학 2팀 전화번호 알려줘

---

## 🌽 Course & Enrollment Information

- 최신 학기 개설 과목 정보 제공
- 강의계획서 연동
- 수강신청 일정 및 학년별 신청 시간 안내
- 장바구니 제도 지원
- 연간 학사일정 조회 가능

---

## 🌽 Profile-Based Personalized Guidance

- 로그인 후 프로필을 한 번만 작성하면 맞춤형 안내 제공
- 이름, 학번, 단과대학, 학부, 전공, 학년·학기 정보 기반 동작
- 졸업요건, 수강신청, 행정부서 정보를 개인 기준으로 필터링

![image.png](https://github.com/KangNaengBot/.github/blob/main/profile/assets/profile_1.png?raw=true)

**지원 기능**
- 공통 졸업요건과 전공 필수 요건 자동 정리
- 현재 학년·학기 기준 남은 이수 조건 안내
- 반복적인 개인 정보 설명 불필요

---

## 🌽 AI Timetable Manager

> 대화를 통해 사용자의 조건을 반영한 시간표를 자동으로 구성해주는 기능입니다.

### 🌽 사용 흐름

#### 1. 시간표 모드 활성화
![image.png](https://github.com/KangNaengBot/.github/blob/main/profile/assets/schedule_1.png?raw=true)

---

#### 2. 과목 검색 / 졸업요건 / 필수 과목 확인
![image.png](https://github.com/KangNaengBot/.github/blob/main/profile/assets/schedule_2.png?raw=true)
![image.png](https://github.com/KangNaengBot/.github/blob/main/profile/assets/schedule_3.png?raw=true)
![image.png](https://github.com/KangNaengBot/.github/blob/main/profile/assets/schedule_4.png?raw=true)

---

#### 3. 과목 장바구니 담기
- 분반 상관없이 추가 가능
- 원하는 분반 선택 가능
- 목표 학점에 맞춰 유연하게 추가 가능

![image.png](https://github.com/KangNaengBot/.github/blob/main/profile/assets/schedule_5.png?raw=true)
![image.png](https://github.com/KangNaengBot/.github/blob/main/profile/assets/schedule_6.png?raw=true)
![image.png](https://github.com/KangNaengBot/.github/blob/main/profile/assets/schedule_7.png?raw=true)

---

#### 4. 장바구니 과목 확인
![image.png](https://github.com/KangNaengBot/.github/blob/main/profile/assets/schedule_8.png?raw=true)

---

#### 5. 시간표 생성 요청
![image.png](https://github.com/KangNaengBot/.github/blob/main/profile/assets/schedule_9.png?raw=true)

---

#### 6. 조건 입력
![image.png](https://github.com/KangNaengBot/.github/blob/main/profile/assets/schedule_10.png?raw=true)

> 조건에 따라 처리 시간이 다소 소요될 수 있습니다.

![image.png](https://github.com/KangNaengBot/.github/blob/main/profile/assets/schedule_11.png?raw=true)

---

#### 7. 시간표 저장 및 다운로드
![image.png](https://github.com/KangNaengBot/.github/blob/main/profile/assets/schedule_12.png?raw=true)

---

## 🌽 Safety & Stability

- 학교 내부 데이터 기준으로 정보 제공
- 애매한 요청에도 안정적인 응답 흐름 유지
- 빈 응답 없이 명확한 안내 제공

---

## 🌽 Roadmap

- 모바일 환경 최적화
- 시간표 추천 알고리즘 고도화
- 개인 맞춤 알림 기능
- 사용자 피드백 기반 지속 개선
- 교수 이메일 작성 지원
- 학교 인근 맛집 및 점심 메뉴 추천

---

## 🌽 Team

**Leader**
- 홍기현 (Backend / PO)  
  - Email: kpj45123@gmail.com  
  - GitHub: @CodeBBakGoSu  

**Members**
- 방태림 (Designer / PM)
- 조성민 (Backend) — @ChoSeongmin1128
- 김근언 (Backend) — @kimgeuneon
- 최민석 (Frontend) — @SleepyMS

---

## 🌽 Repository

- Frontend  
  https://github.com/KangNaengBot/KangNaengBot_Front

- Backend  
  https://github.com/KangNaengBot/KangNaengBot_Back

---

## 🌽 Feedback & Contribution

![image.png](https://github.com/KangNaengBot/.github/blob/main/profile/assets/feedback_1.png?raw=true)

- GitHub Issue
- 서비스 내 피드백 버튼
- 이메일 제보

사용자 경험을 기반으로 지속적으로 개선됩니다.
