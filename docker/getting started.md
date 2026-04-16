
# Download Materials

```Bash
docker run -dp 80:80 docker/getting-started
```

- `docker run`: 이미지로부터 컨테이너를 생성한 후 실행.
- `-d`: Detached 모드. 컨테이너를 백그라운드에서 터미널과는 독립적으로 실행.
- `-p 80:80`: 호스트의 포트(왼쪽)와 컨테이너의 포트(오른쪽)를 연결
- `docker/getting-started`: Docker Hub에서 이미지를 다운로드.

# Create Docker Project