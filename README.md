# Treasure Hunt - Interactive Unix Tutorial

> **[https://joonan30.github.io/treasurehunt-web/](https://joonan30.github.io/treasurehunt-web/)**

브라우저에서 바로 유닉스 명령어를 배울 수 있는 인터랙티브 보물찾기 게임입니다.

개인 컴퓨터에 터미널을 설치할 필요 없이, 웹 브라우저만 있으면 누구나 바로 시작할 수 있습니다.

## What is this?

This is a browser-based interactive Unix command tutorial, presented as a treasure hunt game. Originally created as a Perl script ([treasureHunt_v2_kor.pl](https://github.com/JunKimCNU/JunKimLabTutorial/tree/main/task01_linux_tutorial)) by **Stephan J Sanders** (UCSF / Woods Hole MBL) and translated into Korean by **Jun Kim**, this web version recreates the full experience in a virtual terminal that runs entirely in your browser — no installation required.

## How to Play

1. **[사이트 접속](https://joonan30.github.io/treasurehunt-web/)** (위 링크 클릭)
2. `cat Clue01_S.txt` 를 입력하여 첫 번째 단서를 읽기
3. 단서를 따라가며 유닉스 명령어를 하나씩 배우기
4. 총 13개의 단서를 모아 최종 보물을 찾으면 클리어!

## Commands You'll Learn

| Command | Description |
|---------|-------------|
| `cd` | 디렉토리 이동 (Change directory) |
| `ls` | 파일 목록 보기 (List files) |
| `cat` | 파일 내용 읽기 (Print file contents) |
| `mkdir` | 디렉토리 만들기 (Make directory) |
| `cp` | 파일 복사 (Copy) |
| `mv` | 파일 이동/이름변경 (Move/rename) |
| `rm` | 파일 삭제 (Remove) |
| `grep` | 문자열 검색 (Search text) |
| `tail` | 파일 끝부분 보기 (View end of file) |
| `gunzip` | 압축 해제 (Decompress) |
| `perl` | 스크립트 실행 (Run script) |
| `nano` | 텍스트 편집 (Text editor) |
| `Tab` | 자동완성 (Auto-complete) |

## Features

- **Virtual Terminal** — ~15,000개 디렉토리와 가상 파일시스템이 브라우저에서 동작
- **Tab Completion** — 실제 터미널처럼 Tab 키로 경로 자동완성
- **Command History** — 화살표 키(↑↓)로 이전 명령어 탐색
- **Guide Cat (Nabi)** — 오른쪽 패널에서 고양이 캐릭터가 힌트 제공
- **Progress Tracking** — 발견한 단서 수와 진행률 표시
- **KOR / ENG Toggle** — 가이드 패널 한국어/영어 전환
- **Celebration Effect** — 보물 발견 시 레인보우 축하 효과!

## Credits

- **Original script**: Stephan J Sanders (UCSF / Woods Hole Marine Biology Labs)
- **Korean translation**: Jun Kim ([JunKimLabTutorial](https://github.com/JunKimCNU/JunKimLabTutorial))
- **Web version**: Interactive browser terminal adaptation
