
# Branch

- 특정 커밋에서 분기되어 독립적으로 관리되는 워크플로우.

# Commands

```Bash

# 브랜치 열람
git branch # 브랜치 목록 표시
git branch -v # 브랜치 목록과 마지막 커밋 표시
git branch -a # 로컬과 리모트 브랜치 모두 표시
git branch --merged # 병합된 브랜치를 표시

# 브랜치 생성/삭제
git branch [branch-name] # 브랜치 생성
git branch -d [branch-name] # 브랜치가 Merge 되었을 경우 삭제
git branch -D [branch-name] # 브랜치를 강제 삭제

# 브랜치 이동
git switch [branch-name] # 브랜치로 이동
git switch -c [branch-name] # 브랜치를 생성한 후 이동
git switch - # 직전 브랜치로 이동

# 브랜치 병합
git merge [branch-name] # 현재 브랜치로 대상 브랜치를 병합
git merge --no-ff [branch-name] # 병합 후 첫 커밋을 포함 (표준적인 권장 옵션)
git merge --squash [branch-name] # 브랜치의 커밋을 하나의 커밋으로 합쳐서 병합
git merge --abort # 병합 충돌 시 되돌리기

# 리모트의 브랜치 생성/삭제
git push -u origin [branch-name] # 로컬의 브랜치를 리모트에 추가하고 연결
git push origin --delete [branch-name] # 리모트의 브랜치를 제거

```