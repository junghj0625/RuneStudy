
# Rebase

- 브랜치의 시작점을 변경하는 작업.
- 불필요한 커밋을 정리할 수 있다.


```Bash

# 최신 동기화
git pull --rebase # 패치 이후 리베이스 (권장)
git rebase # 리모트의 최신 커밋으로 시작점 변경
git rebase [branch-name] # 특정 브랜치의 최신 커밋으로 시작점 변경

# 커밋 정리
git rebase -i HEAD~N # 최근 N개의 커밋을 정리

```