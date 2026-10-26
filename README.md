# 길덕영

API·DB·장치 사이의 흐름을 연결하고, 데이터와 처리 상태가 어긋나는 문제를 추적·개선합니다.

Android·FastAPI 기반 무인 우산 대여 시스템을 개발했으며, 앱·서버·장치 사이의 연동과 대여·반납 상태 처리를 구현했습니다.

현재 한국전력기술에서 현장실습을 진행하며 OCR·LLM 업무 시스템 개선을 맡고 있습니다. 개인 프로젝트로는 Java·Spring Boot 기반 기자재 대여·예약 시스템 **LabGear**를 개발하고 있습니다.

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

### 한국전력기술 현장실습 | 2026.09 ~ 현재

- **저장 데이터 검증:** LLM 출력의 표기 차이가 잘못된 DB 컬럼 생성으로 이어지는 문제를 분석하고, 정규화·표준 필드 매핑·저장 검증을 적용했습니다.
- **OCR 처리 흐름 개선:** 처리 상태를 DB에 영속화하고 재시작 복원과 페이지 단위 재처리를 구현했습니다. 조건부 상태 갱신과 lease 기반 복구로 후속 안정화를 진행했습니다.
- **업무 UI 개선:** 기존 API·실시간 이벤트·DB 저장 연동을 유지하며 React로 전환하고, 사용자 피드백을 반영해 작업 흐름을 정리한 뒤 운영 서버에 배포했습니다.

## Tech

- **Backend:** Java · Spring Boot · Spring Data JPA · Spring Security · Python · FastAPI
- **Database / Test:** MySQL · SQLite · JUnit 5 · MockMvc · pytest
- **App / System:** Kotlin · Android · C · Linux · Raspberry Pi
- **Tools / Infra:** Git · GitHub Actions · Railway · GCP

## Contact

- Email: [deokyoung.dev@gmail.com](mailto:deokyoung.dev@gmail.com)
- Portfolio: [Notion Portfolio](https://app.notion.com/p/90ee14d1855a4fccb0bc3c278c89fe20?source=copy_link)
