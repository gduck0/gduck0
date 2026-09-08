# 길덕영

SW 시스템의 흐름과 상태를 이해하고, HW·SW가 연결되는 지점의 문제를 추적하는 컴퓨터공학 전공자입니다.

현재 한국전력기술 현장실습에서 Python/FastAPI 기반 OCR·LLM 업무 시스템의 구조와 처리 흐름을 분석하고 있으며, 프로젝트에서는 백엔드·임베디드·VR/데이터 분석을 경험했습니다.

## Projects

### ☂️ [우산있나우](https://github.com/gduck0/umbrellaisnow)
**QR 기반 무인 우산 대여·반납 서비스**  
`Android` `Kotlin` `FastAPI` `Python` `SQLite` `Raspberry Pi` `REST API`

- 3인 팀 캡스톤 프로젝트에서 **Android 앱과 FastAPI 서버** 담당
- 일회용 QR 토큰 발급·검증과 대여/반납 상태 처리 구현
- Raspberry Pi 제어 프로그램과 서버 간 API를 연동해 **앱 → 서버 → 실제 장치 → 상태 변경**으로 이어지는 흐름 구성
- 요청, 장치 상태, DB 상태를 함께 확인하며 오류 발생 지점을 추적

### 🏠 [스마트홈 통합 제어 시스템](https://github.com/gduck0/smarthome)
**Raspberry Pi 기반 멀티프로세스 스마트홈 통합 제어 시스템**  
`C` `Python` `Raspberry Pi` `pthread` `POSIX Message Queue` `GPIO` `NFC` `Bluetooth`

- 4인 팀 프로젝트에서 **메인 제어 프로그램과 재난 감시 SW** 담당
- 센서·액추에이터·NFC·Bluetooth 기능을 하나의 제어 흐름으로 통합
- 프로세스 간 통신과 멀티스레드 구조를 구성하고 HW·SW 통합 문제를 추적
- PWM과 GPIO 제어 충돌 등 실제 장치 연동 과정의 문제를 분석·해결

### 🧠 [디멘시아](https://github.com/gduck0/dementia)
**치매 환자의 인지 혼란을 1인칭으로 체험하는 VR 시뮬레이터**  
`Unity` `C#` `OpenXR` `Python` `Flask` `Scikit-learn`

- VR 사용자 행동 데이터를 수집해 Isolation Forest 기반 이상 행동 탐지 로직 구현
- 혼란도에 따라 시각 왜곡·환청 등의 연출 강도를 변화시키는 기능 구현
- 프로토타입 과정에서 서버 연동 안정성을 검토하고 일부 기능을 로컬 로직으로 대체

## Experience

**한국전력기술 현장실습 | 2026.09 ~ 현재**

- 발전소 설계도면을 처리하는 OCR·LLM 시스템의 구조와 업무 흐름 분석
- PDF 등록 → Job 생성 → 페이지 처리 → OCR → DB 저장으로 이어지는 API·DB·처리 로직 추적
- 각 단계의 데이터 생성·변경과 상태 전이를 따라가며 전체 프로세스를 이해하는 경험 축적

## Tech Stack

- **Languages:** C, Python, Kotlin
- **Backend / App:** FastAPI, Android SDK, Retrofit2, OkHttp
- **System / Embedded:** Linux, Raspberry Pi, pthread, POSIX Message Queue, GPIO
- **Data / Tools:** SQLite, SQL, Git, GitHub, Railway

## Contact

- Email: [deokyoung.dev@gmail.com](mailto:deokyoung.dev@gmail.com)
- Portfolio: [Notion Portfolio](https://app.notion.com/p/90ee14d1855a4fccb0bc3c278c89fe20?source=copy_link)
