## github

1. 회원가입

2. github student pack 받기(학교 이메일 입력하면 됨)

3. new repository > first로 만들기

4. first폴더 > git bash창에서

   * ```
     git remote add origin https://github.com/kim3278/first.git
     ```

   * ```
     git push -u origin main
     ```

   **github 비밀번호 쳐서 로그인 연결

* 오류 나는 경우 bash 창에  밑에 명령어 따라서 치기
* ![image-20210316154454007](C:%5CUsers%5Cuser%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20210316154454007.png)

* 커밋메시지 작성시 -> 일관성 있게 작성할것

* 어떤 메세지인지 잘 알 수 있도록 작성

* [영어사전](https://blog.ull.im/engineering/2019/03/10/logs-on-git.html)

* [좋은 커밋메시지](https://meetup.toast.com/posts/106)

* 처음에는 간단하게 작성할것

* bash창에서 email  github가입시 사용한 이메일인지 확인

  ```bash
  $ git config --global -l
  $ git config --global user.name '이름'
  $ git config --global user.email '이메일 주소'
  ```



## 포트폴리오 관리-github pages

* [visual studio code 다운로드](https://code.visualstudio.com/)

  ```bash
  # repository만들때 아이디.github.io
  $ git init
  $ git status
  $ git add .
  $ git commit -m 'Add index.html'
  # remote문 복사
  $ git push origin master
  ```

  -html파일이 있다는 가정하

* 