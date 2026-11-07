#Mini Clipper
터미널 환경에서 명령어와 코드 조각을 가장 빠르고 간편하게 저장하고 조회할 수 있는 초간단 파이썬 스크립트입니다.
기능스니펫 추가 및 관리: 제목과 내용을 입력하여 빠르게 저장
목록 조회: 저장된 모든 항목과 내용을 한눈에 확인
항목 삭제: 필요 없는 스니펫을 간편하게 삭제
자동 데이터 저장: JSON 파일을 이용해 프로그램 종료 후에도 데이터 유지

설치 및 실행 방법
레포지토리 클론

Bash
git clone https://github.com/username/MiniClipper.git
cd MiniClipper

스크립트 실행 Bash셸 -> python clipper_mini.py
입력값 (메뉴 선택)1: 저장된 목록 조회
2: 새로운 스니펫 추가
3: 기존 스니펫 삭제
4: 프로그램 종료

사용예시:--- [1] 목록 [2] 추가 [3] 삭제 [4] 종료 ---
선택: 2
제목: git push
내용: git push origin main --force
결과:--- [1] 목록 [2] 추가 [3] 삭제 [4] 종료 ---
선택: 1   - git push: git push origin main --force
요구사항Python 3.x   추가 라이브러리 없음 (표준 라이브러리 json, os만 사용)
