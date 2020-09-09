# nest.js boilerplate

## 로컬 Docker
Docker 빌드
```
$> docker build -f Dockerfile.local -t nestjs-docker:latest .
```

Docker 실행
```
$> docker run -p 3000:3000 nestjs-docker:latest
```