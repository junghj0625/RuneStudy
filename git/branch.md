
# Branch

- 특정 커밋에서 분기되어 독립적으로 관리되는 워크플로우.

# Commands

```Bash

git branch # 브랜치 목록 표시
git branch -v # 브랜치 목록과 마지막 커밋 표시
git branch -a # 로컬과 리모트 브랜치 모두 표시
git branch --merged # 병합된 브랜치를 표시

git branch [branch-name] # 브랜치 생성

git branch -d [branch-name] # 브랜치가 Merge 되었을 경우 삭제
git branch -D [branch-name] # 브랜치를 강제 삭제

git switch [branch-name] # 브랜치로 이동
git switch -c [branch-name] # 브랜치를 생성한 후 이동
git switch - # 직전 브랜치로 이동

git merge [branch-name] # 브랜치를 병합

git push origin --delete [branch-name] # 리모트의 브랜치를 제거
git fetch --prune # 리모트의 삭제된 브랜치 상태를 동기화

```