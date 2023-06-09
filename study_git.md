# Git의 정의 와 활용
<br>
Git이란?

---
컴퓨터 파일의 **변경사항을 추적**하고 여러 명의 사용자들 간에
해당 **파일들의 작업을 조율하기 위한 스냅샷** 스트림 기반의 분산 버전 관리 시스템

---
<br>
<br>

## 기본명령어(CLI환경)
---

### 1 . 로컬 저장소 생성
```
git init
```
-> 특정 폴더에 git 저장소를 만들어 버전관리할 파일목록 지정

<br>

### 2 . 커밋 대상 기록
```
git add .
git add <파일명>
```
-> init되어있는 파일 목록중 변경내용을 staging     area에 추가

### 3 . 커밋(버전기록)
```
git commit -m '<커밋 메시지>'
```

-> staged 파일들을 하나의 버전으로 기록 <br>
　 이때 커밋 메시지는 변경사항을 함축할수있도록 명확해야함 

### 4 . 현재 상태 확인
```
git status
git log
```

* ***git status*** <br>파일(init)의 변경사항이나 
staging 공간에 있는 파일의 목록상태를 보여줌
<br><br>
* ***git log*** <br>커밋된 버전들의 기록을 보여줌
<br><br>


 <[버전관리 흐름 도식](https://git-scm.com/book/ko/v2/Git%EC%9D%98-%EA%B8%B0%EC%B4%88-%EC%88%98%EC%A0%95%ED%95%98%EA%B3%A0-%EC%A0%80%EC%9E%A5%EC%86%8C%EC%97%90-%EC%A0%80%EC%9E%A5%ED%95%98%EA%B8%B0)>