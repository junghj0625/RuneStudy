
# Staging

- 변경 사항을 커밋 대상으로 지정하는 작업.

# Commands

```Bash

git add [file-name] # 파일을 스테이징
git add [directory] # 디렉토리를 스테이징
git add -A # 모든 변경 사항을 스테이징
git add -u # Tracked File의 변경 사항만을 스테이징

git restore --staged [file-name] # 파일 스테이징을 취소
git restore --staged [directory] # 디렉토리 스테이징을 취소

git status # 스테이징된 파일 표시

```