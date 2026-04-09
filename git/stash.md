
# Stash

- 변경 사항을 임시 저장하고 되돌리는 작업.

# Commands

```Bash

git stash # 트래킹되는 파일 스테시
git stash -u # 트래킹되지 않은 파일까지 스테시
git stash -m "Message" # 메시지와 함께 스테시
git stash -p # 코드 조각별로 선택 스테시

git stash list # 스테시 목록 표시
git stash show # 최근 스테시 파일 표시
git stash show -p # 최근 스테시 파일들의 diff까지 표시

git stash pop # 최근 스테시를 불러오고 스테시 삭제
git stash apply [stash-name] # 최근 스테시를 불러오고 스테시를 삭제하지 않음
git stash apply --index # 스테이징까지 포함해서 스테시 불러오기
git stash branch [branch-name] [stash-name] # 최근 스테시를 새 브랜치로서 불러오기

git stash drop [stash-name] # 스테시 삭제
git stash clear # 모든 스테시 삭제

```