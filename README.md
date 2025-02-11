# 🎥HRERock
![image](https://github.com/user-attachments/assets/9ec816e1-ff2c-4794-867d-ec6fcf9b66dd)


# 📄프로젝트 소개
![image](https://github.com/user-attachments/assets/c8e44710-e5a1-4acb-9068-bf534f994639)
![image](https://github.com/user-attachments/assets/32d1aeba-536c-46d0-b5b8-4d9a05c84d26)


# 🧑‍💻팀원 소개 및 역할
![image](https://github.com/user-attachments/assets/c4fb1392-9ff1-4677-a53e-74204496bb8d)

# 📔개발 개요
![image](https://github.com/user-attachments/assets/1168a681-f2d2-4ec6-9e3c-261c491793bf)

# 📆개발 일정
![image](https://github.com/user-attachments/assets/dd3957bf-0aa7-4467-936b-1ed14a009064)

# 🔍주요 기능
▶ 영화 기능
  - 영화에 대한 정보 제공 (감독, 배우, 장르, 줄거리, 포스터. 예고편, 본편)
  - 각 영화에 대한 감정/리뷰 포인트와 리뷰의 작성/수정/삭제 기능 제공
  - 각 리뷰에 대한 '좋아요' 기능 구현, 리뷰 리스트의 '좋아요순', '최신순' 정렬 기능 구현
  - 각 영화에 대한 찜 기능 제공
  - 개인별 영화 추천 기능 제공 (리뷰에 작성된 포인트 기반 협업필터링, 컨텐츠필터링, 배우, 감독, 장르의 빈도 기반의 협업기반 필터링)
  - imdb 공식을 활용한 영화 순위 리스트 제공
  - 신규 추가된 영화 리스트 제공 (+ 예고편)
  - 사용자 시청기록 저장을 통해 이어보기, 최근 시청리스트를 시청률을 표시하여 제공
  - 영화 재생 기능을 제공하며, 사용자의 시청기록을 db에 저장
  - 시청기록이 있을 경우, 해당 시점부터 재생

▶ 회원 기능
  - 회원 가입 (아이디, 이메일, 핸드폰번호 중복확인, 이메일 인증코드)
  - 로그인
  - 아이디/비밀번호 찾기 (비밀번호 재설정: 이메일 인증을 통한 재설정 페이지 이동)
  - 회원정보 수정
  - 회원탈퇴

▶ 검색 기능
  - 영화 제목, 제작 감독, 출연 배우, 장르를 기준으로 영화를 검색
  - 검색 순위 기능 제공
    
▶ 챗봇 기능
  - 웹 소켓(WebSocket)을 통한 관리자, 사용자 간의 실시간 채팅

▶ 공지사항 기능 (사용자)
  - 공지사항 조회 기능 제공 (조회 시, 조회수 증가)
  - 공지사항 파일 다운로드 기능 제공

▶ 마이페이지 기능
  - 개인화된 사용자 프로필 사진 설정 기능 제공
  - 최근 시청 내역 조회/삭제 기능 제공
  - 영화의 찜 내역 조회/삭제 기능 제공
  - 개인별 작성 리뷰의 조회/삭제 기능 제공

▶ 관리자페이지 기능
  - 공지사항 작성/수정/삭제 기능 제공
  - 공지사항 파일 업로드 추가/수정/삭제 기능 제공
  - 회원 조회/삭제 기능 제공
  - 영화 조회/추가/수정/삭제 기능 제공

# 🛠기술 스택
![image](https://github.com/user-attachments/assets/5c50e200-db18-422e-8ced-23daf6265f54)

# 📂폴더구조
![image](https://github.com/user-attachments/assets/6caf035d-9fd3-4bf4-81c6-8ee24690ce23)





주요 구성:
- `data_visualization`: 파이썬 모듈
- `src/forntend`: React 프론트앤드 코드
- `src/java`: Java 백엔드 코드
- `src/python`: Python 스크립트 및 데이터 처리 관련 파일들
- 루트 디렉토리: 프로젝트 설정 및 빌드, 임시 생성 관련 파일들


![screencapture-localhost-3000-user-MoviePage-122-2024-10-23-17_52_23](https://github.com/user-attachments/assets/8f8027b4-83aa-4abd-b98f-9c00bb09f869)

![screencapture-localhost-3000-user-MovieSearch-2024-10-23-17_52_44](https://github.com/user-attachments/assets/53870c7a-56ec-4f35-aff2-c3ffab41f0e7)

![screencapture-localhost-3000-admin-memberList-2024-09-13-10_05_55](https://github.com/user-attachments/assets/53b84dd6-e469-4db1-8e80-9181c41710cb)

![screencapture-localhost-3000-admin-movieList-2024-10-23-18_34_59](https://github.com/user-attachments/assets/08273c2d-ca92-468e-936b-1f5f8d688160)

![screencapture-localhost-3000-user-mypage-2024-10-23-18_35_17](https://github.com/user-attachments/assets/1e775960-0892-4eda-af2b-fa11a01a5001)

