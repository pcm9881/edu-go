# 프로그래밍 언어 Go 학습 기록

## go mod
Go 1.11 및 1.12 의존성관리시스템 모듈이 사용가능하다.

### go.mod 파일 생성
```
$ go mod init
```

### go.sum
설치된 모듈 해시값 목록

## go get
go get 패키지명 명령으로 내 로컬 PC에 설치한다.

### go get -u 

#### gin install

```
$ go get -u github.com/gin-gonic/gin
```


[Go Blog](https://blog.golang.org/using-go-modules)