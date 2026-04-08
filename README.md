# 👋 Hi, I'm Seongmoon Kim

### 💻 Software Developer | Smart Factory & Vision System Engineer

C#, Java, SQL을 기반으로 한 산업용 소프트웨어 및 웹 서비스 개발 경험을 가진 **풀스택 지향 개발자**입니다.  
스마트팩토리, 비전시스템, 자동화 설비 통신 등 다양한 분야에서 **문제 해결 중심의 개발**을 추구하고 있습니다.  

---

## 🚀 Tech Stack

**Languages**  
`C#` `Java` `HTML` `CSS` `JavaScript` `SQL`

**Frameworks & Tools**  
`WinForms` `WPF` `Spring Boot` `Bootstrap` `MyBatis`  
`MsSQL` `Oracle` `MariaDB` `PostgreSQL`

**Other Skills**  
`Socket Communication` `Serial Communication` `PLC Communication` `Image Processing`  
`Deep Learning Inference` `Git` `Notion`

---

## 🏢 Career

### 🔹 HiveVision (2025.04 ~ Present)
**Software Developer (System Development Team 2)**  
- C# Windows Forms 기반 **UI 프로그램 개발**  
- **MsSQL DB 설계 및 CRUD 기능 구현** (PostgreSQL 전환 예정)  
- 산업용 **카메라 및 렌즈 제어**를 통한 Grab / Record / Snap 기능 개발  
- **RS-232 시리얼 통신** 기반 바코드 리더 연동 및 자동 촬영 트리거 구현  
- **PLC 통신 연동**을 통한 생산라인 신호 수신 및 검사 결과 전송  
- **ONNX Runtime + CUDA** 기반 딥러닝 결함 검출 모듈(DeepCulus) 연동  
- **SWIR 카메라** 및 **Matrox 비전 라이브러리** 기반 이미지 처리 시스템 개발  
- **조명 컨트롤러 제어** 연동 (LightController)  
- `libwebp` P/Invoke 기반 **WebP 이미지 인코딩** 및 FastAPI AI 서버 HTTP 연동  
- **AWS S3** 이미지 클라우드 업로드 연동  
- Memory Mapped File 기반 **프로세스 간 비전 데이터 공유** 구현  

### 🔹 Asetech (2023.02 ~ 2023.07)
**WCS Team – Interface Developer**  
- C# 기반 **물류센터 LAAS 시스템 UI** 개발  
- ORACLE Package로 데이터 관리  
- POSCO 광양센터 **AutoStore 시스템 화면 개발**

---

## 📚 Education
**Dongguk University (Gyeongju)**  
B.S. in Computer Engineering (2017.03 ~ 2023.02)  
GPA: 3.77 / 4.5  

**ITWill Academy (2023.07 ~ 2024.01)**  
_Project-based Java Fintech Web Developer Course_  
- HTML, JSP, Spring Boot, WebSocket 기반 프로젝트 수행  
- `Tindog` 팀 프로젝트에서 **DB 설계**, **채팅 기능(WebSocket)**, **관리자 모드** 구현 담당

---

## 💡 Projects

### 📷 HiveDI — 멀티 카메라 이미지 취득 시스템 (2025)
> 바코드 기반 자동 트리거로 3채널 카메라를 동기화 촬영하고, AI 서버로 이미지를 전송하는 산업용 머신비전 시스템

**개발 환경**  
`C# .NET Framework 4.8` `Windows Forms` `MetroFramework` `HIKROBOT MVS SDK` `x64`

**주요 기능**  
- Hikvision GigE/USB 카메라 **3채널 동기화 촬영** (LEFT / TOP / RIGHT 배치)  
- USB 전동 렌즈 3개 **포커스 위치 자동 제어** (A / B / C 프리셋)  
- RS-232 바코드 리더 연동 — 4자리 커맨드 파싱 기반 **자동 촬영 트리거 및 포커스 전환**  
- `libwebp` P/Invoke 기반 **WebP 이미지 인코딩** (무손실 / 손실 선택)  
- FastAPI AI 추론 서버 HTTP 연동 — **파일 저장 전송 / 메모리 직접 전송** 이중 모드  
- Memory Mapped File 기반 **프로세스 간 비전 데이터 공유**  
- INI 파일 기반 카메라·렌즈 설정 관리 및 바코드별 촬영 카운트 기록  

**담당 역할**  
전체 시스템 설계 및 단독 개발 — 카메라 / 렌즈 / 시리얼 통신 통합, 전략 패턴 기반 카메라 추상화 설계

---

### 🔬 HD_Dross — SWIR 기반 결함 검출 시스템 (2025~2026)
> SWIR(단파적외선) 카메라와 딥러닝을 결합하여 제조 공정 중 실시간으로 결함(Dross)을 자동 검출하는 머신비전 시스템

**개발 환경**  
`C# .NET Framework` `Windows Forms` `Matrox 비전 라이브러리` `ONNX Runtime` `CUDA`

**주요 기능**  
- **SWIR GigE 카메라** 제어 및 Avaldata 프레임그래버 SDK 연동  
- **PLC 통신 연동** — 생산라인 트리거 신호 수신 및 검사 결과 전송  
- **DeepCulus ONNX Runtime + CUDA GPU** 딥러닝 결함 검출 (Bounding Box 좌표 추출)  
- **조명 컨트롤러(LightController) 제어** 연동  
- **AWS S3** 검사 이미지 클라우드 업로드  
- Warping / Calibration **이미지 전처리** 파이프라인  
- log4net / NLog 기반 **운영 로그 관리**  

**담당 역할**  
SWIR 카메라 시스템 연동, PLC 통신 구현, AI 추론 모듈(DeepCulus) 통합

---

### 🐾 Tindog (Team Project)
> 반려견 MBTI 기반 매칭 & 실시간 채팅 웹서비스  

- **Frontend**: JSP, Bootstrap, JavaScript, AJAX  
- **Backend**: Java, Spring Boot, MariaDB, WebSocket  
- 주요 기능: 1:1 실시간 채팅, 사용자/관리자 모드, 반려견 프로필 관리  
- 담당 역할: 기술지원 / DB 설계 / 채팅 기능 구현 / 관리자 모드 개발  
- 🔗 [프로젝트 문서 보기](https://github.com/zunmoon/Tindog/blob/master/Tindog_Project.pptx)

---

## 🧠 Strengths

- **문제 해결 중심의 개발 태도**  
  : 현업 환경에서 발생한 카메라·모션 통신 문제를 코드로 해결한 경험  
- **목표지향적 학습 태도**  
  : Oracle DB 사내 평가에서 만점으로 1위 달성 (신입 포함)  
- **다양한 언어와 환경 적응력**  
  : C#, Java, SQL 등 Backend 중심 기술을 Frontend/Full-stack으로 확장 중  

---

## 📫 Contact

📍 Gwangju, Gyeonggi-do  
📧 **vosejtjdans@gmail.com**   
💻 [GitHub](https://github.com/vosejtjdans)

---

### ✨ Motto
> "빠르게 배우고, 꾸준히 개선하며, 기술로 문제를 해결한다."
