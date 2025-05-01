# Carelift

## 🧩 개요
**CareLift**는 교통약자의 편의를 위한 **엘리베이터 제어 시스템**입니다.  
RFID, 카메라 인식, 음성 제어 기능 등을 활용하여 휠체어 사용자 및 교통약자가 보다 **안전하고 편리하게 엘리베이터를 이용**할 수 있도록 설계되었습니다.

## 🛠️ 사용 기술

### 📟 하드웨어
- **STM32F411RE**: 스텝모터, 서보모터 제어
- **Arduino Nano ESP32**: RFID, 버튼, 부저, 서보모터 제어
- **Jetson Nano + Camera**: YOLOv8 기반 휠체어 인식
- **Raspberry Pi 4**: 서버/음성 인식 처리

### 🌐 통신
- **TCP 소켓 통신**: 메인서버 ↔ 클라이언트 명령 송수신

### 🗄 데이터베이스
- **MariaDB**: 사용자 정보 및 탑승 기록 저장
- **MySQL 라이브러리**: Raspberry Pi에서 DB 제어

### 🧰 개발 도구
- STM32CubeIDE, Arduino IDE, VS Code

### 🎥 시연 영상
[👉 버튼 제어](https://youtube.com/shorts/SQt_mkShKDk)
[👉 음성인식](https://youtube.com/shorts/iNJ-vfX4VzU)
[👉 휠체어 우선탑승](https://youtube.com/shorts/i7uu4Uciq9c)
