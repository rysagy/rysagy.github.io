# 류상균 로봇 개발 포트폴리오

주소: **https://rysagy.github.io/**

로봇 소프트웨어 개발(ROS2·Nav2, 비전, 임베디드) 프로젝트와 물류자동화 현장 경력을 소개하는 정적 웹사이트입니다. 맨 위는 진행 중인 최종 프로젝트(공장자동화 AMR)입니다.

## 수정 방법

- `index.html`: 프로필, 프로젝트, 경력, 연락처
- `styles.css`: 색상, 레이아웃, 모바일 화면
- `script.js`: 모바일 메뉴, 이메일 복사
- `*.webp`: 제공된 포트폴리오에서 추출한 실제 프로젝트 사진
- `assets/`: 프로젝트 시연 GIF와 사진 (최종 프로젝트 AMR, Safe Eye, ARMIGO, Pinky, PLC)
- `files/`: 포트폴리오 PDF·PPTX (사이트의 'PDF', 'PPTX 받기' 버튼과 연결)

GitHub 저장소의 파일을 수정하고 `main`에 저장하면 Pages가 다시 게시합니다. 사이트 주소를 유지하면 기존에 인쇄한 QR은 그대로 사용할 수 있습니다.

## QR 코드

- `portfolio-qr.png`: PNG 이미지, 인쇄·프로필 문서 삽입용
- `portfolio-qr.svg`: 확대해도 선명한 인쇄용 벡터
- QR에 들어 있는 주소: `https://rysagy.github.io/`

단축 URL이나 유료 동적 QR 서비스를 사용하지 않는 정적 QR입니다. QR 자체에 만료 기한이 없습니다. 연결하려면 GitHub 계정, 저장소, Pages 사이트 주소를 계속 유지해야 합니다.

## 내용 근거

제공된 포트폴리오 PPT, 본인 노션의 ARMIGO·Safe Eye·Pinky Pro 기록, 최종 프로젝트 Confluence 날짜별 기록과 실측 기록을 참고했습니다. 공동 담당과 개인 담당을 구분하고, 모델 검증 수치를 현장 정확도로 표현하지 않았습니다. PLC는 보조 경험으로 정리했습니다.

Pinky Pro 프로젝트는 Gazebo 시뮬레이션입니다. 공개 데이터나 팀 프로젝트의 영상·UI는 개인이 모두 구현한 것으로 표현하지 않았습니다.

## 로컬 확인

이 폴더에서 `python3 -m http.server 8765` 실행 후 `http://localhost:8765`에 접속합니다. 별도 빌드와 서버 백엔드는 필요하지 않습니다.
