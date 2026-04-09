
# Tag

- 특정 커밋에 태그를 붙이는 작업.
- SamVer 방식의 버전 표기나 `release`, `latest` 등을 많이 사용함.

# Commands

```Bash

git tag # 태그 목록 표시
git tag [tag-name] # 최근 커밋에 태그 붙이기
git tag -a [tag-name] -m "Message" # 태그, 메시지, 작성자, 날짜를 포함
git tag -d [tag-name] # 태그 삭제

git push origin [tag-name] # 리모트에 특정 태그 전송
git push origin --tags # 리모트에 모든 태그 전송

```