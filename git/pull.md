
# Pull

- 리모트와 로컬의 내용을 동기화하는 작업.

```Bash

git fetch --all --prune # 모든 리모트의 모든 브랜치 정보를 동기화

git pull # 패치 후 머지
git pull --ff-only # 패치 후 머지 (로컬에 커밋이 있을 경우 거절됨)
git pull --rebase # 패치 후 리베이스

```