
# Clone

- 리모트 리포지토리를 로컬로 복사하는 작업.

# Commands

```Bash

git clone [url] # 리모트에서 복제
git clone -b [branch-name] [remote-url] # 리모트에서 브랜치를 복제
git clone --recursive [url] # 서브모듈도 함께 복제

# ========================================
# git clone은 아래의 커맨드와 같은 동작을 함
# ========================================

git init # 현재 디렉토리 초기화
git remote add origin [remote-url] # 리모트 연결
git fetch # 데이터 다운로드
git checkout # 최신 커밋으로 이동

# ========================================

git fetch # 데이터 다운로드
git pull # 데이터 다운로드 + 병합

```

