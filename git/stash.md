
# Stash

- 변경 사항을 임시 저장하고 되돌리는 작업.
- 스테시된 내용은 스택 구조로 쌓인다.

# Commands

```Bash

git stash # Tracked File만 스테시
git stash -u # Untracked File을 포함하여 스테시
git stash -m "Message" # 메시지와 함께 스테시
git stash -p # 코드 조각별로 선택 스테시

git stash list # 스테시 목록 표시
git stash show # 최근 스테시 파일 표시

git stash pop # 최근 스테시를 불러오가 (스테시 삭제)
git stash pop stash@{n} # 특정 스테시를 불러오기 (스테시 삭제)

git stash apply # 최근 스테시를 불러오기 (스테시 보존)
git stash apply stash@{n} # 특정 스테시를 불러오고 스테시를 삭제하지 않음

git stash branch [branch-name] # 최근 스테시를 새 브랜치로서 불러오기
git stash branch [branch-name] stash@{n} # 특정 스테시를 새 브랜치로서 불러오기

git stash drop # 최근 스테시 삭제
git stash drop stash@{n} # 스테시 삭제

git stash clear # 모든 스테시 삭제

```