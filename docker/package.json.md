
# package.json

- Node.js 프로젝트의 의존성, 메타데이터, 스크립트 실행을 기록한 문서.

# Example

```json
{
  "name": "101-app",
  "version": "1.0.0",
  "main": "index.js",
  "license": "MIT",
  "scripts": {
    "prettify": "prettier -l --write \"**/*.js\"",
    "test": "jest",
    "dev": "nodemon src/index.js"
  },

  "dependencies": {
    "express": "^4.18.2",
    "mysql2": "^2.3.3",
    "sqlite3": "^5.1.2",
    "uuid": "^9.0.0",
    "wait-port": "^1.0.4"
  },

  "resolutions": {
    "ansi-regex": "5.0.1"
  },

  "prettier": {
    "trailingComma": "all",
    "tabWidth": 4,
    "useTabs": false,
    "semi": true,
    "singleQuote": true
  },

  "devDependencies": {
    "jest": "^29.3.1",
    "nodemon": "^2.0.20",
    "prettier": "^2.7.1"
  }
}
```

- name: 프로젝트 이름
- version: 프로젝트 버전
- main: 프로젝트 시작점 (앱 Entry 혹은 라이브러리 Interface)
- license: 프로젝트 라이센스
- scripts: 단축 명령어 리스트 (대부분 관습어로 구성됨)
	- dev: 개발용 서버 실행
	- text: 테스트 실행
	- prettify: 코드 스타일 정리