
# Download Materials

```Bash
docker run -dp 80:80 docker/getting-started
```

- `docker run`: 이미지로부터 컨테이너를 생성한 후 실행.
- `-d`: Detached 모드. 컨테이너를 백그라운드에서 터미널과는 독립적으로 실행.
- `-p 80:80`: 호스트의 포트(왼쪽)와 컨테이너의 포트(오른쪽)를 연결
- `docker/getting-started`: Docker Hub에서 이미지를 다운로드.

# Dockerfile

```Dockerfile
# Node.js 18 alpine 버전
FROM node:18-alpine 

# 작업 경로 설정
WORKDIR /app

# 파일 복사 [SRC] [DST]
COPY . .

# yarn install 실행
RUN yarn install --production

# 컨테이너 실행 후 명령어 실행 (index.js 실행)
CMD ["node", "src/index.js"]
```

# Build

```Bash
# docker build: 빌드 실행 명령어
# -t [image-tag]: 태그(이미지 이름) 설정
# .: 빌드 컨텍스트 경로

docker build -t getting-started .
```
