
# Submodule

- Git 프로젝트 내에 있는 하위 Git 프로젝트.

# Commands

```Bash

git submodule add [url] [submodule-path] # 서브모듈 추가
git submodule update -init --recursive # 모든 서브모듈을 복제
git submodule update --remote --recursive # 모든 서브모듈의 최신 버전을 복제

```

# Note

- 클론 시 `--recursive` 옵션을 사용하지 않으면 서브모듈이 비어있는 상태로 복제된다.
- 서브모듈이 비어있을 경우 `git submodule update -init --recursive` 을 사용하자.