
# What is Checkout?

- 특정 커밋 또는 브랜치로 이동하는 작업.
- `switch`, `restore`로 대체 가능.

# Commands

```Bash

# 브랜치 관련
git checkout [branch-name] # 브랜치의 최신 커밋으로 이동
git checkout - # 직전 브랜치로 이동
git checkout -b [new-branch-name] # 브랜치를 생성하고 이동

# 파일 관련
git checkout -- [file-name] # 파일 수정 사항 버리기
git checkout [commit-hash] -- [file-name] # 파일을 특정 커밋에서 가져오기
git checkout [commit-hash] # Detached HEAD 상태로 커밋 열람

```