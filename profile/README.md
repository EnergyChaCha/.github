# 강한날 👋
![ganghannal-logo](https://github.com/user-attachments/assets/ed20aa47-ad47-43f0-babf-50f9fe27d38a)

## 프로젝트 소개
- 2024 CJ대한통운 미래기술 챌린지 참가작
- 스마트 워치를 활용한 물류 현장 근로자 건강 관리 어플리케이션

## 개발 기간
- 예선:  2024.06.18 ~ 2024.07.24
- 본선:  2024.08.09 (~2024.08.12 추가기능 구현)

## 프로젝트 링크
- 웹: https://www.ganghannal.life/
- 스웨거: https://server.ganghannal.life/api/docs

## 프로젝트 문서
- [API 문서](https://www.notion.so/a4856769beb34526b69b5e64b77ec951?pvs=21)
- [기능명세서](https://www.notion.so/a790212276014b0ea5d6bbead2b0011a?pvs=21)

## 레포지터리
- [백엔드](https://github.com/EnergyChaCha/Energy-Springboot)
- 프론트엔드
    - [예선](https://github.com/EnergyChaCha/Energy-front)
    - [본선](https://github.com/EnergyChaCha/energy-front2)
- [워치](https://github.com/EnergyChaCha/Energy-watch)

## 팀원 소개
| <a href="https://github.com/Jiwon119"><img src="https://github.com/Jiwon119.png" width="120"/></a> | <a href="https://github.com/LeeJE20"><img src="https://github.com/LeeJE20.png" width="120"/></a> | <a href="https://github.com/woori0214"><img src="https://github.com/woori0214.png" width="120"/></a> |
| --- | --- | --- |
| [김지원](https://github.com/Jiwon119) | [이정은](https://github.com/LeeJE20) | [전우리](https://github.com/woori0214) |
| Frontend | Watch | Backend |

## ERD
![erd-240812-dark](https://github.com/user-attachments/assets/679e1301-10b1-4fb3-9906-2c9e36b86661)

## 아키텍처
![image](https://github.com/user-attachments/assets/2f1adccf-4d7b-4c36-a1c2-b05bcd337d46)

## 개발환경 및 기술 스택
- Frontend
    - react-native
    - expo
    - typescript
- Backend
    - java 17
    - springboot 3.2.4
    - spring security
    - spring data jpa
    - swagger
- Watch
    - kotlin
    - WearOS
    - jetpack-compose
    - minSdk: 30
    - compileSdk: 34
    - targetSdk: 34
    - Wearable Data Layer API
    - retrofit2
- Infra
    - EC2 (Ubuntu 22.04 LTS)
    - TimescaleDB 2.15.2-pg16, pgcrypto extension
    - Docker
    - Github actions
