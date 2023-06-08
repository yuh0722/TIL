# Github(원격저장소)
```
로컬 내에서 기록하고 관리한 파일 버전들을 원격 저장소인 github을 통해
타인과 협업하는데 주요한 역할 
```
<br>

## Github 활용
---
* **로컬 저장소 Load 절차** 

  1. new repository(원격저장소 설정) <br><br>

  2. 초기설정된 URL 확인후 ***복사*** <br><br>

  3. 로컬 저장소에 원격 저장소 정보 설정
      ```
      git remote add origin https://github.com/유저네임/원격저장소명
      ```
  <br>
  
   4. 원격 저장소에 로컬저장소 변경사항 올리기
      ```
      git push <원격 저장소이름> <브랜치 이름>
      
      git push origin main
      ````
  <br>
  cf. 원격 저장소로부터 변경된 내역 받아와 이력 병합
  <br>
  
  ```
  git pull <원격 저장소이름> <브랜치 이름>
  ``` 
  <br>

* **오픈소스 관련기여 절차**

   1. Clone <br>원격 저장소 복제후 로컬 저장소에 로드<br>
       ```
       git clone <url>
       ```
   
->pull과 차이점: pull은 이미 로컬저장소에 존재하는 파일목록중 원격 저장소내에서 변경된 버전을 가져오는 반면 Clone은 기존에 없던 저장소 로컬에 반영.<br><br> 
    &emsp;&emsp;&emsp;&emsp;&emsp;
    2. 파일변경후 원격저장소에 load<br><br>
    &emsp;&emsp;&emsp;&emsp;&emsp;
    3. ***pull request***<br>
    &emsp;&emsp;&emsp;&emsp;&emsp;
    &emsp;저장소의 생성자에게 merge요청시 pull-request 요청