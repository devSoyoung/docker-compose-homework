# docker-compose

```
$ git clone https://github.com/devSoyoung/docker-compose.git
$ cd docker-compose
$ docker-compose up -d
```

브라우저에서 `localhost`로 접속하면 됩니다. 포트는 브라우저 기본인 80포트로 설정해두었으므로, 생략해도 됩니다.

* 참고한 글: [Docker Compose로 localhost Nginx 리버스 프록시 구성](https://medium.com/sjk5766/docker-compose%EB%A1%9C-localhost-nginx-%EB%A6%AC%EB%B2%84%EC%8A%A4-%ED%94%84%EB%A1%9D%EC%8B%9C-%EA%B5%AC%EC%84%B1-8214d41a94fc)

각 nginx 서버의 access, error 로그는 `docker-compose.yml`의 volume 설정으로 프로젝트 내의 파일과 연결해두었습니다.
