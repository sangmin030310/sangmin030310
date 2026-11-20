# 권상민 | AI 서비스 기획·개발

전주대학교 인공지능학과에서 공부하고 있습니다. AI 서비스를 기획할 때 사용자가 어떤 정보를 입력하고, 결과를 어디서 확인하며, 다음에 무엇을 결정하는지부터 살핍니다.

## 프로젝트

### [Re AI · 산업폐기물 자원순환 AI 서비스](https://github.com/sangmin030310/re-ai)

**AI 부트캠프 경진대회 · Microsoft 주제 · 4인 팀 · 개발 중**

산업 부산물의 품질과 수요 업체의 요구 조건을 바탕으로 활용 가능한 재활용 경로와 업체를 찾는 서비스입니다. 저는 **AI 채팅과 문서함의 UI/UX**를 맡았습니다. 채팅에서 작성한 요청서를 문서함에서 다시 찾을 수 있도록 화면 전환과 사용 흐름을 설계했습니다. React 화면과 FastAPI 서버의 연동, 회원가입 이메일 인증 동작을 확인했습니다.

[화면 구성 코드](https://github.com/sangmin030310/re-ai/blob/main/frontend/src/App.tsx) · [API 연동 코드](https://github.com/sangmin030310/re-ai/blob/main/frontend/src/lib/api.ts)

### [Last Order 2050 · 공공조달 2D 게임](https://github.com/sangmin030310/last-order-2050)

**2026 조달청 AI 게임·콘텐츠 공모전 AI 게임 부문 · 2인 팀 · 개발 중**

재난으로 공급망이 끊긴 도시에서 제한된 물자를 어디에 먼저 보낼지 결정하는 게임을 Godot과 GDScript로 개발했습니다. 기존 부품과 후속 부품의 도착 시간, 정수·통신시설의 가동 한계를 비교해 플레이어의 선택을 **엔딩 5종과 시설별 복구 보고서**에 반영합니다. 최종 배차와 엔딩 분기를 포함한 **자동 테스트 15개**를 통과했습니다.

[배차·엔딩 로직](https://github.com/sangmin030310/last-order-2050/blob/main/recovery.gd) · [배차·엔딩 테스트](https://github.com/sangmin030310/last-order-2050/blob/main/tests/dispatch_policy_smoke.gd)

### [앵커 · 딸기 과실 탐지 및 성숙 단계 식별](https://github.com/sangmin030310/strawberry-ripeness)

**전주대학교 RISE 특성화 인재양성 프로그램 · 4인 팀 · 개발 중**

재배 영상에서 YOLO로 딸기 과실을 찾아 **미숙·착색 중·완숙** 단계를 화면에 표시하는 시제품을 목표로 합니다. 조명이 달라지거나 잎이 과실을 가릴 때 어떤 탐지 오류가 생기는지도 확인할 계획입니다.

### [전주대학교 도서관 · 도서 오배열 탐지](https://github.com/sangmin030310/misplaced-book-detection)

**6인 팀 · 개발 중**

스마트폰으로 서가를 비추면 잘못 꽂힌 책의 위치를 화면에 표시하는 시제품을 기획했습니다. **YOLO로 책등 라벨을 찾고, OCR로 읽은 청구기호를 실제 서가 순서와 비교**하는 방식입니다.
