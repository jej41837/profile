# ssen-voca | 쎈슬기 단어장

> 홈·학습 탭의 화면 디자인과 TypeScript 화면 구성을 맡고 있는 영단어 학습 앱

[경험 목록](../../README.md) · [앱 저장소](https://github.com/ssen-voca/ssen-app) · [서버 저장소](https://github.com/ssen-voca/ssen-server)

## 한눈에 보기

| 항목 | 내용 |
| --- | --- |
| 서비스 | 차시별 단어장과 문맥 예문으로 수능 영어 어휘를 익히는 학습 앱 |
| 기간 | 10월부터 진행 중 · 시작 연도 미확인 |
| 팀 | 2명 |
| 현재 상태 | 개발 중 |
| 내 역할 | 전체 화면 디자인, 홈·학습 탭 구분과 화면 구성 |
| 직접 사용한 기술 | TypeScript |

## 내가 맡은 작업

| 작업 | 내용 |
| --- | --- |
| 전체 화면 디자인 | 단어 학습 앱의 화면 디자인 담당 |
| 탭 구성 | 홈 탭과 학습 탭을 구분해 구성 |
| 화면 구현 | TypeScript를 이용해 화면 구성 |

아래 서비스 기능·기술은 저장소에서 확인한 **프로젝트 전체 구성**입니다. 제가 직접 맡은 작업은 위 표의 범위로 구분합니다.

## 서비스와 저장소 구성

| 구분 | README에서 확인한 내용 | 연결 |
| --- | --- | --- |
| 앱 | 차시별 단어장·문맥 예문 중심의 영단어 학습 앱. 현재 웹 우선 개발 | [ssen-app](https://github.com/ssen-voca/ssen-app) |
| 서버 | 차시별 단어장, 학습 기록, 복습 스케줄, 엑셀 업로드를 담당하는 API 서버 | [ssen-server](https://github.com/ssen-voca/ssen-server) |

## 기술 사용 맥락

| 기술 | 확인 범위 |
| --- | --- |
| TypeScript | 제가 화면 구성에 직접 사용 |
| React Native·Expo·Expo Router | 앱 저장소 README에 기재된 프로젝트 기술 |
| Spring Boot·PostgreSQL | 서버 저장소 README에 기재된 프로젝트 기술. 개인 담당 기술로 제시하지 않음 |

## 관련 구현 위치

| 작업 대상 | 현재 코드 위치 |
| --- | --- |
| 홈 화면 | [src/app/(main)/index.tsx](https://github.com/ssen-voca/ssen-app/blob/develop/src/app/%28main%29/index.tsx) |
| 학습 화면 | [src/app/study.tsx](https://github.com/ssen-voca/ssen-app/blob/develop/src/app/study.tsx) |
| 공통 화면 구성 | [src/app/(main)/_layout.tsx](https://github.com/ssen-voca/ssen-app/blob/develop/src/app/%28main%29/_layout.tsx) |

현재 파일의 존재와 화면 구성 일부를 확인한 위치입니다. 개별 변경의 작성자·커밋 이력까지 검증한 자료는 아닙니다.

## 진행 중인 설계 고민

**많은 정보를 담은 단어장과, 편의성을 우선한 가벼운 앱 사이에서 방향을 고민하고 있습니다.**

| 선택 방향 | 고민하는 내용 |
| --- | --- |
| 정보량 중심 | 단어장에 많은 정보를 담는 구성 |
| 편의성 중심 | 가볍게 사용할 수 있는 앱 구성 |

최종 결정과 적용 후 결과는 아직 확인되지 않았습니다. 해결을 완료한 사례나 사용성 개선 성과로 표현하지 않습니다.

## 근거와 현재 정리 범위

- **개인 기여:** 경험 인터뷰에서 확인한 전체 화면 디자인·홈/학습 탭 구성·TypeScript 사용
- **프로젝트 구성:** 앱·서버 저장소의 `develop` 브랜치 README 열람
- **관련 코드:** 홈·학습·공통 화면 파일 위치 연결
- **추가로 연결할 자료:** 실제 홈·학습 탭 캡처와 개인 변경·확인 기록
- **미확인:** 구체적인 테스트 결과, 배포 상태, 설계 선택의 최종 결론

## 관련 링크

- [ssen-voca 조직](https://github.com/ssen-voca)
- [앱 README](https://github.com/ssen-voca/ssen-app/blob/develop/README.md)
- [서버 README](https://github.com/ssen-voca/ssen-server/blob/develop/README.md)

