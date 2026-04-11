
# Tag

- 특정 커밋에 태그를 붙이는 작업.
- 하나의 태그는 하나의 커밋에만 붙음.
- SamVer 방식의 버전 표기나 `release`, `latest` 등을 많이 사용함.

# Commands

```Bash

git tag # 태그 목록 표시

git tag [tag-name] # 최근 커밋에 태그 붙이기
git tag [tag-name] [commit-hash] # 특정 커밋에 태그 붙이기

git tag -a [tag-name] -m "Message" # 태그, 메시지, 작성자, 날짜를 포함
git tag -d [tag-name] # 태그 삭제

git push origin [tag-name] # 리모트에 특정 태그 전송
git push origin --tags # 리모트에 모든 태그 전송

# 태그 삭제/수정 커맨드는 기록하지 않음.
# 태그 삭제/수정은 안 하는 것이 좋지 않을까...?

```