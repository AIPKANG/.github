# 글그린

**글그린**은 여러 사람이 각자 블로그를 갖고 글을 쓰는 서비스입니다. 티스토리·벨로그처럼 내 블로그 주소를 받아 글을 쓰고, 다른 사람의 글을 읽고, 팔로우하고, 댓글로 이야기합니다.

🌐 운영 사이트: **https://geulgreen.java21.net**

## 주요 기능

- **회원**: 이메일 가입·인증, Google·GitHub 로그인, 블로그 주소·닉네임, 프로필, 탈퇴와 30일 안 복구
- **글쓰기**: 보이는 대로 쓰는 편집기(저장은 Markdown), 자동 저장, 사진·표, `/` 명령, 태그와 AI 태그 추천, 예약 발행
- **공개 범위**: 공개·비공개·친구 공개·그룹 공개·링크 공개, 비공개 계정
- **읽기**: 홈·탐색·피드, 트렌딩, 검색, 카테고리·시리즈, 목차, 이전 글·다음 글, RSS, 다크 모드
- **반응**: 댓글·답글(비밀 댓글), 좋아요, 조회수, 팔로우, 인앱 알림, 방명록
- **기록**: 오늘의 미션과 배지, 잔디·스트릭, 작성자 통계, 짧은 기록
- **운영**: 관리자 대시보드, 신고·숨김·회원 정지, 사이트 공지, 관리 기록

## 기술 스택

| 영역 | 사용 기술 |
|---|---|
| 서버 | Java, Spring Boot 4.1, Spring Security(OAuth2) |
| 화면 | Thymeleaf |
| 데이터 | PostgreSQL, Flyway, Redis 세션 |
| 빌드 | Gradle (Kotlin DSL) |
| 배포 | Docker, GitHub Actions 자동 배포 |
| 품질 | SonarQube 코드 분석, 테스트 자동 실행 |

## 저장소

| 저장소 | 내용 |
|---|---|
| [**blog**](https://github.com/AIPKANG/blog) | 소스 코드·빌드·배포 |
| [**docs**](https://github.com/AIPKANG/docs) | 설계 문서와 기능 명세([GitHub Spec Kit](https://github.com/github/spec-kit)) |

기능은 Spec Kit으로 명세를 먼저 쓰고 그대로 구현했습니다. 변경 내역은 blog 저장소의 `CHANGELOG.md`와 사이트의 릴리스 노트 화면에서 볼 수 있습니다.
